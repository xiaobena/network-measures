# Network Measures

Recently, network measures have been proposed to predict bug-prone modules. Leveraging the dependency relationships between software 
entities, network measures describe the structural features of software systems. The aim of this project is to provide a comprehensive 
evaluation on the predictive effectiveness of network measures. My study investigates their ability of high severity bug prediction and 
effort-aware bug prediction under both ranking and classification scenarios.

1. Predicting high severity bugs

    This work discusses the effectiveness of network measures in fault-proneness prediction at high severity level. By examining four 
open-source projects, we conclude that 1) most of the network measures are significantly correlated with high severity fault-proneness;
2)generally, when used together, network measures can predict high severity faults effectively as the selected code metrics can, and 
their predictive powers are comparable to those of the selected code metrics for forward-release high severity fault-proneness prediction; 
and 3) network measures are very unstable for cross-project predictions of high severity faults.

    ● Paper: SCIS'16 (https://link.springer.com/article/10.1007%2Fs11432-015-5426-3)

2. Effort-aware bug prediction

    This work aims to make a thorough investigation into the actual usefulness of network measures with the effort needed to inspect the 
code taken into account. By conducting our study on multiple releases of 11 open-source projects with various sizes, programming languages 
and application domains, we find that 1) most network measures are significantly and positively related to fault-proneness, bug only a few 
of them have a notably effect; 2) although network measures almost offer no improvement in inter-project predicion compared with code 
metrics, they do improve the prediction performance in most cases within the same projects; and 3) the performance of network measures 
varies across different projects, probably dependent on the various software structures.

    ● Paper: IST'16 (https://www.sciencedirect.com/science/article/pii/S0950584915001524)

