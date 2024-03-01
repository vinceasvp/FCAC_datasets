# FCAC_datasets
The FCAC(Few-shot Class-incremental Audio Classification) problem aims to address the issue of how to maintain old class knowledge while continually learning new classes. In this problem, the categories in each session are distinct from each other. The base class training set is a large-scale dataset, so the experimental dataset should meet two main requirements: first, the experimental dataset should contain an adequate number of audio categories; second, some categories within the experimental dataset should contain a large number of samples.

Based on these two requirements, this chapter selected three corpora, which are FSD-MIX-CLIPS, NSynth, and LibriSpeech. These three audio corpora can all be used for research purposes and have been widely used in previous audio classification work. Although the aforementioned three corpora all contain sufficient audio categories, there still exists the issue of imbalanced samples between classes, with some categories having insufficient samples to effectively evaluate the FCAC problem. Therefore, this chapter used reorganized FS-89, NS-100, LS-100 as the final experimental dataset. The detailed construction process of the dataset, the required materials and procedures, and the organized constructed dataset can be found at the following link.

- FS-89: https://www.modelscope.cn/datasets/pp199124903/FSC-89/summary

- NS-100: https://www.modelscope.cn/datasets/pp199124903/NSynth-100/summary

- LS-100: https://www.modelscope.cn/datasets/pp199124903/LS-100/summary
