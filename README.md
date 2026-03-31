# FineBadminton: A Multi-Level Fine-Grained Dataset for Badminton Video Understanding

**Xusheng He<sup>1</sup>, Wei Liu<sup>1</sup>, Shanshan Ma<sup>2</sup>, Qian Liu<sup>3</sup>, Chenghao Ma<sup>2</sup>, Jianlong Wu<sup>1</sup>**  
<sup>1</sup> Harbin Institute of Technology, Shenzhen, China  
<sup>2</sup> China Electronics Standardization Institute, China  
<sup>3</sup> Shandong University, China  
[![Project Page](https://img.shields.io/badge/Project-Page-blue)](https://ilearn-lab.github.io/MM25-FineBadminton/)
[![Dataset](https://img.shields.io/badge/%F0%9F%A4%97%20Dataset-Finebadminton--20K-f6c343)](https://huggingface.co/datasets/Moujuruo/Finebadminton-20K)
[![Benchmark](https://img.shields.io/badge/%F0%9F%A4%97%20Benchmark-FineBadmintonBenchmark-f59e0b)](https://huggingface.co/datasets/Moujuruo/FineBadmintonBenchmark)
[![License: Apache-2.0](https://img.shields.io/badge/License-Apache%202.0-green.svg)](LICENSE)

FineBadminton is a multi-level fine-grained badminton video understanding dataset with a unified annotation hierarchy spanning **Foundational Actions**, **Tactical Semantics**, and **Decision Evaluation**. FineBadmintonBenchmark (FBBench) is built from FineBadminton to evaluate spatio-temporal reasoning, action understanding, localization, tactical comprehension, and rally-level cognition in badminton videos.

## Abstract

Fine-grained analysis of complex and high-speed sports like badminton presents a significant challenge for Multimodal Large Language Models (MLLMs), despite their notable advancements in general video understanding. This difficulty arises primarily from the scarcity of datasets with sufficiently rich and domain-specific annotations. To bridge this gap, we introduce FineBadminton, a novel and large-scale dataset featuring a unique multi-level semantic annotation hierarchy for comprehensive badminton understanding. The construction of FineBadminton is powered by an annotation pipeline that combines MLLM-generated proposals with human refinement. We also present FBBench, a benchmark derived from FineBadminton, to rigorously evaluate MLLMs on nuanced spatio-temporal reasoning and tactical comprehension. Together, FineBadminton and FBBench provide a practical ecosystem for fine-grained sports video understanding.

## Resources

- [Project page](https://ilearn-lab.github.io/MM25-FineBadminton/)
- [Dataset link: Finebadminton-20K](https://huggingface.co/datasets/Moujuruo/Finebadminton-20K)
- [Benchmark link: FineBadmintonBenchmark](https://huggingface.co/datasets/Moujuruo/FineBadmintonBenchmark)

## Figures

### Annotation example

![Annotation example](figures/annotation_instance.png)

An example annotation instance from FineBadminton, showing the multi-level semantic hierarchy used to describe stroke-level actions and rally understanding.

### Benchmark example

![Benchmark example](figures/benchexample.png)

An example from FineBadmintonBenchmark illustrating the style of fine-grained badminton reasoning tasks supported by the benchmark.

## Citation

If you find FineBadminton or FineBadmintonBenchmark useful in your research, please cite:

```bibtex
@inproceedings{he2025finebadminton,
  title={Finebadminton: A multi-level dataset for fine-grained badminton video understanding},
  author={He, Xusheng and Liu, Wei and Ma, Shanshan and Liu, Qian and Ma, Chenghao and Wu, Jianlong},
  booktitle={Proceedings of the 33rd ACM International Conference on Multimedia},
  pages={12776--12783},
  year={2025}
}

@misc{he2025finebadminton_arxiv,
  title={Finebadminton: A multi-level dataset for fine-grained badminton video understanding},
  author={He, Xusheng and Liu, Wei and Ma, Shanshan and Liu, Qian and Ma, Chenghao and Wu, Jianlong},
  year={2025},
  eprint={2508.07554},
  archivePrefix={arXiv},
  primaryClass={cs.MM},
  url={https://arxiv.org/abs/2508.07554}
}
```

## License

This repository is released under the Apache-2.0 License. See [LICENSE](LICENSE) for details.
