# SiamFRN Visual Object Tracker
## Siamese High-Level Feature Refine Network for Visual Object Tracking. 
MDPI Electronics 2020. [Paper](https://www.mdpi.com/2079-9292/9/11/1918/htm)

This work proposes a feature refined end-to-end tracking framework with a balanced performance using a high-level feature refine tracking framework. The feature refine module enhances the target feature representation power that allows the network to capture salient information to locate the target. The attention module is employed inside the feature refine mechanism to improve network discrimination power that augments the network ability to track the target in challenging scenarios.
</br>

![example](./images/main_framework.jpg)

### Comparison with SOTA

<p align="center">
  <img src="bolt2-final.gif" />
</p>



### Tracker comparison on challenging attributes
#### [Success Plots]
![example](./results/success100_challenges.jpg)

#### [Precision Plots]
![example](./results/precision100_challenges.jpg)

### Qualitative performance on challenging sequences

![example](./results/qualative_results.jpg)


