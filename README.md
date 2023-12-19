# Independency Adversarial Learning (IAL)
The sound mixture separation is still challenging due to heavy sound overlapping and disturbance from noise. As sound overlapping always hinders accurate sound separation, we propose an Independency Adversarial Learning Cross-Modal Sound Separation (IAL) approach, where IAL employs adversarial learning to minimize the correlation of separated sound elements, exploring high sound independence. Cross-modal sound separation incorporates audio-visual consistent feature learning and interactive cross-attention learning to emphasize the semantic consistency among cross-modal features. Both audio-visual consistency and audio consistency are kept to guarantee accurate separation. The proposed approach is evaluated on MUSIC, VGGSound, and AudioSet. Extensive experiments certify that our approach outperforms existing ones in both supervised and unsupervised scenarios.

##  Summary of proposed approach
![Separation results of audio spectrums in the AVE dataset.](https://github.com/yanliji/IAL/blob/main/Image/AVESeparationResults.pdf)
The proposed approach is majorly composed of two major parts, (a) the Cross-Modal Separation (CMS), and (b) Independency Adversarial Learning (IAL). 

##  Code explanation and training


##  Result Visualization
![Separation results of audio spectrums in the AVE dataset.](https://github.com/yanliji/IAL/blob/main/Image/AVESeparationResults.pdf)

![Mixture separation results.](https://github.com/yanliji/IAL/blob/main/Image/Supervised%20Separation%20Results%20(1).png "Mixture separation results.")

## Citation

@inproceedings{lin2023IAL,
  title={Independence Adversarial Learning for Cross-Modal Sound Separation},  
  author={Zhenkai Lin and Yanli Ji and Yang Yang},
  booktitle={Proceedings of the 38th AAAI Conference on Artificial Intelligence},
  pages={1--1},
  year={2024}
}
