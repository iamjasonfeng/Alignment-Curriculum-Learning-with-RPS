# Alignment-Curriculum-Learning-with-RPS

[PDF](https://iamjasonfeng.github.io/Alignment-Curriculum-Learning-with-RPS/alignment_curriculum_learning_with_rps.pdf)

Abstract

This paper proposes Alignment Curriculum Learning with Regressive Plasticity Schedule (RPS), a
research direction for post-training language models on ethical behavior. The proposed curriculum has two
stages: Stage 1 uses higher optimization plasticity to teach broad and foundational ethical principles, while
Stage 2 uses lower plasticity to teach nuanced, contextual, and potentially conflicting ethical
considerations. The central hypothesis is that this schedule may preserve foundational ethical behavior
while allowing bounded refinement on harder cases, potentially producing a more nuanced understanding
of ethics than constant-plasticity training. RPS previously produced encouraging results in an ARC
program-synthesis experiment with Qwen3-8B. Relative to an Equal Plasticity Schedule (EPS) control,
RPS improved ARC-AGI-1 exact test-output accuracy from 10/419 to 17/419 and increased successful
ARC-AGI-2 program executions from 188/240 to 234/240, although neither condition solved any
ARC-AGI-2 test outputs.[1] These findings do not constitute evidence that RPS improves alignment, but
they motivate testing whether curriculum-coupled plasticity reduction transfers to ethical post-training.
This paper presents the hypothesis, curriculum, experimental controls, evaluation criteria, and potential
failure modes; it does not present empirical alignment results.
