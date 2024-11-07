---
layout: default
---

Recent advances in deep learning have led to impressive progress in the field of autonomous robotic systems. These systems, however, often display overconfident behavior when interacting with the environment, as they are not aware of the uncertainty in their predictions. In this work, we present an approach of incorporating uncertainty into a learning-based locomotion controller for a quadrupedal robot. For this, we estimate the uncertainty in the internal latent state of the controller, which is then used by the controller to generate risk-averse behavior. Our approach consists of training an initial policy using a supervised loss based on demonstrations from an expert. During this stage, we also learn estimates of the uncertainty in the internal belief of the controller using ground truth data from a simulated training environment. The policy is then fine-tuned using reinforcement learning to learn risk-averse behavior given the estimate of its own uncertainty. Our results indicate that this approach leads to more careful behavior under high-uncertainty both in simulation and on a real robot.

## Video

Coming soon!
