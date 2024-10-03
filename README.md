# Rethinking Mixture-of-Agents: Is Mixing Different Large Language Models Beneficial?
> Wenzhe Li*, Yong Lin*, Mengzhou Xia, Chi Jin

## Abstract
Ensembling outputs from diverse sources is a straightforward yet effective approach to boost performance. Mixture-of-Agents (MoA [1]) is one such popular ensemble method that aggregates outputs from multiple _different_ Large Language Models (LLMs). This paper raises the question in the context of language models: is mixing different LLMs truly beneficial?  We propose **Self-MoA**, an ensemble method that aggregates outputs from only the _single_ top-performing LLM. Our extensive experiments reveal that, surprisingly, Self-MoA outperforms standard MoA that mixes different LLMs in a large number of scenarios: Self-MoA achieves $6.6\%$ improvement over MoA on the AlpacaEval 2.0 benchmark, and an average of $3.8\%$ improvement across various benchmarks, including MMLU, CRUX, and MATH. Applying Self-MoA to one of the top-ranking models in AlpacaEval 2.0 directly achieves the new state-of-the-art performance ranking $1^{\text{st}}$ on the leaderboard. To understand the effectiveness of Self-MoA, we systematically investigate the trade-off between diversity and quality of outputs under various MoA settings. We confirm that the MoA performance is rather sensitive to the quality, and mixing different LLMs often lowers the average quality of the models. To complement the study, we identify the scenarios where mixing different LLMs could be helpful. This paper further introduces a sequential version of self-MoA, that is capable of aggregating a large number of LLM outputs on-the-fly over multiple rounds, and is as effective as aggregating all outputs at once.

<img width="811" alt="iShot_2024-09-25_20 23 47" src="https://github.com/user-attachments/assets/ff30752e-d48d-4c7c-9d12-13f1900bbae8">

Stay tuned for the preprint version coming soon!

[1] Wang, Junlin, Jue Wang, Ben Athiwaratkun, Ce Zhang, and James Zou. “Mixture-of-Agents Enhances Large Language Model Capabilities.” arXiv, June 7, 2024. http://arxiv.org/abs/2406.04692.
