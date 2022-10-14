# Ground-Fusion

We propose Ground-Fusion: a multi-sensor fusion SLAM algorithm that features robust initialization and stable tracking in corner cases including sensor failures. Firstly, we implement a baseline system which tightly couples the sensory information of RGB-D images, inertial information and wheel odometer measurements within a factor graph. Secondly, we improve the initialization and tracking phase of the system. More specifically, we adopt an adaptive sensor selection strategy for different corner cases like severe visual occlusion, wheel drift or even wheel suspension. Finally, extensive experiments conducted on public datasets and in real world demonstrate that our system outperforms existing algorithms in both accuracy and robustness. For the benefit of research community, codes and datasets will be released here upon paper publication.
