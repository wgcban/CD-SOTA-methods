# Remote sensing change detection: State-of-the-art methods and available datasets

Author: [`Wele Gedara Chaminda Bandara`](www.wgcban.com)

Last update: Apr 28 2022

In this repository, I am planning to update the state-of-the-art (SOTA) methods available for remote sensing change detection and publically available datasets.

## Introduction to remote sensing change detection
Remote sensing change detection is an important problem in remote sensing in which our goal is to identify relevant changes in bi-temporal remote sensing images that can help in various applications such as damage assessment, urban expansion monitoring, resource management, and military surveillance. Depending on the application, the changes we look for in bi-temporal images also vary. For example, in the context of military surveillance and disaster management, changes in buildings may indicate a developing threat or areas to focus on for disaster relief, respectively. Therefore, an ideal CD model should be able to detect all of these application-specific changes of interest while avoiding complex irrelevant changes typically seen in remote sensing images such as changes caused by cloud cover, building shadows, different sensing angles, etc.

<p align="center">
  <img src="/imgs/Github-RS-CD-Review.jpeg" width="400">
</p>
<p align="center">
    <em> Figure: The change detection model takes pre-change and post-change image pair as the input and outputs the corresponding pixel wise change/no-change labels. The change detection model can be trained in a supervised, semi-supervised, or unsupervised way.</em>
</p>

## Available SOTA supervised change detection modthods
These models are trained in a supervised manner using a supervised loss function such as Cross-Entropy (CE) by utilizing annotated training samples.

| Method       | Link to Paper | Link to Code | Network Architecture    | Used Datasets | Other Comments|
| :---         |     :---:     |     :---:    |     :---:               |          ---: | ---: |


