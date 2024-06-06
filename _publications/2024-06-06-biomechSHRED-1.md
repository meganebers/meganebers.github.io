---
title: "Human motion data expansion from arbitrary sparse sensors with shallow recurrent decoders"
collection: publications
permalink: /publication/2024-06-06-biomechSHRED-1
excerpt: 'By using shallow recurrent decoder networks to expand datasets of human motion, wearable sensors could be used for more continuous and less intrusive monitoring of human motion in natural environments.'
date: 2024-06-06
venue: bioRxiv
paperurl: 'https://www.biorxiv.org/content/10.1101/2024.06.01.596487v1.full.pdf'
citation: 
---

![BiomechSHRED_Fig1](https://meganebers.github.io/images/BiomechSHRED_Fig1.png) 

Advances in deep learning and sparse sensing have emerged as powerful tools for monitoring human motion in natural environments. We develop a deep learning architecture, constructed from a shallow recurrent decoder network, that expands human motion data by mapping a limited (sparse) number of sensors to a comprehensive (dense) configuration, thereby inferring the motion of unmonitored body segments. Even with a single sensor, we reconstruct the comprehensive set of time series measurements, which are important for tracking and informing movement-related health and performance outcomes. Notably, this mapping leverages sensor time histories to inform the transformation from sparse to dense sensor configurations. We apply this mapping architecture to a variety of datasets, including controlled movement tasks, gait pattern exploration, and free-moving environments. Additionally, this mapping can be subject-specific (based on an individual’s unique data for deployment at home and in the community) or group-based (where data from a large group are used to learn a general movement model and predict outcomes for unknown subjects). By expanding our datasets to unmeasured or unavailable quantities, this work can impact clinical trials, robotic/device control, and human performance by improving the accuracy and availability of digital biomarker estimates.

Submitted to IEEE Transactions on Neural Systems and Rehabilitation Engineering

[Download paper here](https://www.biorxiv.org/content/10.1101/2024.06.01.596487v1.full.pdf)
