# Decoupled Prompt-Adapter Tuning for Continual Activity Recognition

This is the official implementation of the paper:

**Decoupled Prompt-Adapter Tuning for Continual Activity Recognition**  
[Di Fu](https://github.com/fylk317), [Thanh Vinh Vo], [Haozhe Ma], [Tze-Yun Leong]
[arXiv Paper](https://arxiv.org/abs/2407.14811)

## Abstract

Action recognition technology plays a vital role in enhancing security through surveillance systems,
enabling better patient monitoring in healthcare, providing in-depth performance analysis in sports,
and facilitating seamless human-AI collaboration in domains such as manufacturing and assistive
technologies. The dynamic nature of data in these areas underscores the need for models that can
continuously adapt to new video data without losing previously acquired knowledge, highlighting
the critical role of advanced continual action recognition. To address these challenges, we propose
Decoupled Prompt-Adapter Tuning (DPAT), a novel framework that integrates adapters for
capturing spatial-temporal information and learnable prompts for mitigating catastrophic forgetting
through a decoupled training strategy. DPAT uniquely balances the generalization benefits of prompt
tuning with the plasticity provided by adapters in pretrained vision models, effectively addressing
the challenge of maintaining model performance amidst continuous data evolution without necessitating
extensive finetuning. DPAT consistently achieves state-of-the-art performance across several
challenging action recognition benchmarks, thus demonstrating the effectiveness of our model in the
domain of continual action recognition.

## Code

The code for this project is currently being prepared for release. We anticipate making it publicly available in the near future. Please check back soon for updates.

## Citation

If you find our work useful in your research, please consider citing:

```bibtex
@article{fu2024decoupled,
  title={Decoupled Prompt-Adapter Tuning for Continual Activity Recognition},
  author={Fu, Di and Vo, Thanh Vinh and Ma, Haozhe and Leong, Tze-Yun},
  journal={arXiv preprint arXiv:2407.14811},
  year={2024}
}
