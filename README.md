# 1.Deep-Cropland-CD
[2022_IEEE_深度学习农田变化检测_A CNN-Transformer Network With Multiscale Context Aggregation for Fine-Grained Cropland Change Detection](https://ieeexplore.ieee.org/document/9780164/keywords#keywords)  
(https://github.com/paperoff/CropLand-CD.git)  
CNN+transformer （MSCANet）  
主要内容：  
MSCANet 首先使用 CNN 主干从双时相图像中捕获多尺度特征；然后利用多尺度上下文聚合器 (MSCA) 通过 Transformer 架构对丰富的上下文信息进行建模和聚合；最后，应用多分支预测头（MBPH）来获得变化图，以进一步增强隐藏层的特征提取和学习。MSCANet基于CNN-transformer结构构建，可以充分结合CNN和transformer的优势，满足快速准确的农田CD的迫切需求。CLCD 由 600 对双时相图像组成，标注了各种农田变化，它可以为基于 DL 的农田 CD 任务模型提供基准。本文的贡献总结为三点:  
1.针对农田 CD 提出了一种具有 CNN-transformer 混合架构的 MSCANet，其中 MSCA 旨在编码多尺度上下文信息，MBPH 用于改进深度特征学习。  
2.为所有需要的研究提供高分辨率 CLCD，其中包含 600 对 512 × 512 图像，空间分辨率为 0.5-2 m。  
3.在HRSCD和CLCD上与六个最先进的 (SOTA) CD 模型进行比较实验表明，所提出的 MSCANet 可以分别获得 64.67% 和 71.29% 的最高 F1 分数。CD  F1=64.67% ;CLCD  F1=71.29%  
![image](https://user-images.githubusercontent.com/62208710/196014581-e12c7b2c-3780-4079-878a-541d456a2971.png)  
具体内容：   
第一部分：介绍  
第二部分：方法  
1.特征提取器Feature Extractor  
2.Multiscale Context Aggregator  
3.Multibranch Prediction Head  
第三部分：实验设置  
1.数据集 HRSCD 291*0.5m RGB航空像对 10000*10000；CropLand Change Detection  CLCD  
2.比较方法 SOTA：FC-EF,FC-EF,FC-Siam-conc,DTCDSCN,BiT,MFPNet,DSIFN,MSCANet.  
3.参数和指标  
第四部分：实验和分析  
第五部分：总结

# 2.Deep learning,Optical-SAR,time-series,Crop phenology
[Spatial-aware SAR-optical time-series deep integration for crop phenology tracking](https://www.sciencedirect.com/science/article/pii/S0034425722001602?ref=pdf_download&fr=RR-2&rr=75adbfa509c549f0)   
主要内容：  
本研究的目的是整合光学和SAR数据，以提高作物物候参数提取的准确性。具体来说，我们结合 SAR 和光学卫星观测，在地面观测的帮助下创建用于作物物候识别的空间感知深度学习模型。为此，我们首先在地面站点（例如PhenoCam）周围的小区域提取多源卫星图像，以捕获与相机观察范围一致的作物生长信息。然后，训练基于时空感知深度学习的作物物候模型 (Deep-CroP)，以提取具有 PhenoCam 获取的地面物候标签的作物时空演化特征。最后，物候变化的时间是从具有先前训练有素的深度学习模型的大范围区域的长时间序列特征中提取的。因此，本文提供了一种结合多源卫星和地面观测优势进行作物物候反演的新方法，对未来的物候研究具有潜在价值。总的来说，这项工作的贡献是：  
1.结合光学和SAR时间序列的优势，探索一种新的作物物候跟踪机制。  
2.它提出了一种有效的作物物候参数提取策略，具有空间感知深度特征和长期时间序列依赖性。 
![image](https://user-images.githubusercontent.com/62208710/196017502-937e7ed5-ddd7-4fb3-9646-b8263860f1f5.png)  
具体内容：
第一部分：介绍  
第二部分：研究区域和数据  
1.研究区域 加利福尼亚 



