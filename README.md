# effendy-unified-grasping.github.io
We present a novel transformer-based framework for whole-body grasping that addresses both pose generation and motion infilling, enabling realistic and stable object interactions. Our pipeline comprises three stages: \emph{Grasp Pose Generation} for full-body grasp generation, \emph{Temporal Infilling} for smooth motion continuity, and a \emph{LiftUp Transformer} that refines downsampled joints back to high-resolution markers. To overcome the scarcity of hand-object interaction data, we introduce a data-efficient \emph{Generalized Pretraining} stage on large, diverse motion datasets, yielding robust spatio-temporal representations transferable to grasping tasks. Experiments on the GRAB dataset show that our method outperforms state-of-the-art baselines in terms of coherence, stability, and visual realism. The modular design also supports easy adaptation to other human-motion applications. The code will be released upon acceptance.