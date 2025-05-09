# IntelliCardiac
This repository is the official implementation of our paper [IntelliCardiac: An Intelligent Platform for Cardiac Image Segmentation and Classification](https://arxiv.org/abs/2505.03838).
## This platform is a prototype and not intended for industry-level or commercial use.

## ❗️User Warning❗️
Please note: Our platform is not yet connected to the official doctors’ license database, so we are currently unable to verify the authenticity of doctors. We advise you not to upload highly private or sensitive data at this stage. 

For now, you can use our guest account to log in and a test image to try out the platform.

## Legal Notice
All rights to this platform and its content are reserved by the University at Albany (UAlbany). If you accidentally upload sensitive information that you do not wish to share with unverified doctors, please promptly update your privacy settings by setting the record to “Private” under the Manage Privacy section on the Check History page. If you would like your account and all associated data to be permanently deleted from this platform, please contact a member of the development team.

## Application link
**[IntelliCardiac Web App](https://intellicardiac.ualbany.org/)**

## Testing Data
**Sample testing data** can be found in the [testing_image/](testing_image/) folder.

**Patient guest user you can use:**  
- **Username:** `guest123`  
- **Password:** `Pass1234`

❗️**Important:** After the patient uploads an image, please wait approximately 1 minute for the results to appear. Do not refresh the page during this time, as it may interrupt the processing.

## Introduction
IntelliCardiac is a full-stack medical imaging web platform designed for cardiac segmentation and disease classification using cine MRI.

By combining a deep learning-based segmentation model with a two-stage classification pipeline, IntelliCardiac achieves a segmentation accuracy of 92.6%. The classification module—trained on features extracted from segmented heart structures—reaches 98% accuracy across five diagnostic categories.

These results outperform current state-of-the-art systems that integrate both segmentation and classification. Supporting real-time visualization, workflow integration, and AI-assisted diagnostics, IntelliCardiac shows strong promise as a scalable, accurate tool for clinical decision-making in cardiac imaging.


## Overview of IntelliCardiac system pipeline
<img src="https://github.com/user-attachments/assets/5329a135-397b-40e9-bb37-030c949b3d5d" width="600"/>

## Cardiac Image Process Architecture in the System
<img src="https://github.com/user-attachments/assets/2ed1246a-43b4-426a-8ee1-a8e42bf09200" width="600"/>

## Demo Video
<a href="https://www.youtube.com/watch?v=pIJTYQt0mTI&list=PLSQub-M9Idos0JTEIylqGn5x_ROq3BQcF" target="_blank">
  <img src="https://github.com/user-attachments/assets/da6ff659-6f2e-49ca-b586-1355a47608ec" width="600">
</a>

## Contributors
Ting Yu Tsai, An Yu, Meghana Spurthi  Maadugundu, Ishrat Jahan Mohima, Umme Habiba Barsha, Mei-Hwa F. Chen, Ming-Ching Chang, Balakrishnan Prabhakaran

## Citation
Please kindly consider citing our papers in your publications. 
```bash
@misc{tsai2025intellicardiac,
      title={IntelliCardiac: An Intelligent Platform for Cardiac Image Segmentation and Classification}, 
      author={Ting Yu Tsai and An Yu and Meghana Spurthi Maadugundu and Ishrat Jahan Mohima and Umme Habiba Barsha and Mei-Hwa F. Chen and Balakrishnan Prabhakaran and Ming-Ching Chang},
      year={2025},
      eprint={2505.03838},
      archivePrefix={arXiv},
      primaryClass={eess.IV},
      url={https://arxiv.org/abs/2505.03838}, 
}
```

