# Remote Sensing based Multi-view Models
 List of multi-view fusion learning models proposed for remote sensing (RS) multi-view data. :satellite: :earth_americas: :satellite:

This is a complementary source used in the following paper:  
```
Common Practices and Taxonomy in Deep Multi-view Fusion for Remote Sensing Applications
```

| Name | Reference | Description | Code |
|------|-----------|-------------|------|
MV CNN | [Xu et al. 2018](https://doi.org/10.1109/TGRS.2017.2756851) | Feature-level fusion with 2D CNN. | https://github.com/Hsuxu/Two-branch-CNN-Multisource-RS-classification  << Not available|
V-FuseNet | [Audebert et al. 2018](https://doi.org/10.1016/j.isprsjprs.2017.11.011)  | Dense fusion with 2D CNN and central model. | https://github.com/nshaud/DeepNetsForEO |
Multi3Net | [Rudner et al. 2019](https://doi.org/10.1609/aaai.v33i01.3301702) | Feature-level fusion with 2D CNN. | https://github.com/FrontierDevelopmentLab/multi3net |
UNet-CLSTM | [Rustowicz et al. 2019](https://openaccess.thecvf.com/content_CVPRW_2019/html/cv4gc/Rustowicz_Semantic_Segmentation_of_Crop_Type_in_Africa_A_Novel_Dataset_CVPRW_2019_paper.html)  | Decision-level fusion with 2D CNN and convolutional-LSTM | https://github.com/roserustowicz/crop-type-mapping |
HRWN | [Zhao et al. 2020](https://doi.org/10.1109/TGRS.2020.2982064) | Input-level fusion with 2D CNN and pixel graph constraints. | https://github.com/xudongzhao461/HRWN |
FusAtNet | [Mohla et al. 2020](https://doi.org/10.1109/CVPRW50498.2020.00054) | Feature-level fusion with 2D CNN and cross attention. | https://github.com/ShivamP1993/FusAtNet |
LFMC from SAR | [Rao et al](https://doi.org/10.1016/j.rse.2020.111797) | Input-level fusion with LSTM | https://github.com/kkraoj/lfmc_from_sar |
CCR-Net | [Wu et al. 2021](https://doi.org/10.1109/TGRS.2021.3124913) | Feature-level fusion with 2D CNN and cross view-reconstruction. | https://github.com/danfenghong/IEEE_TGRS_CCR-Net |
MV PSE-TAE | [Ofori-Ampofo et al. 2021](https://doi.org/10.3390/rs13224668) | Multiple fusion strategies with PSE-TAE. | https://github.com/ellaampy/CropTypeMapping |
MDL-RS | [Hong et al. 2021](https://doi.org/10.1109/TGRS.2020.3016820) | Multiple fusion strategies with NN. | https://github.com/danfenghong/IEEE_TGRS_MDL-RS |
CMGFNet | [Hosseinpour et al. 2022](https://doi.org/10.1016/j.isprsjprs.2021.12.007) | Dense fusion with 2D CNN and gated attention. | https://github.com/hamidreza2015/CMGFNet-Building_Extraction |
S2FL | [Hong et al. 2021](https://doi.org/10.1016/j.isprsjprs.2021.05.011) | Feature-level fusion with feature contrains. | https://github.com/danfenghong/ISPRS_S2FL |
CFCNN | [He et al. 2021](https://doi.org/10.1109/TGRS.2020.3028622) | Feature-level fusion with 2D and 1D CNN.  | https://github.com/SysuHe/MultiSourceData_CFCNN |
MV NN | [Danilevicz et al. 2021](https://doi.org/10.3390/rs13193976) | Feature-level fusion with tabular NN and 2D CNN. | https://github.com/mdanilevicz/maize_early_yield_prediction |
ASF2N | [Gao et al. 2022](https://doi.org/10.1016/j.jag.2022.102687) | Feature-level fusion with 2D CNN and attention. | https://github.com/zhonghaocheng/ELSEVIER_IJAEOG_AS2F2N  << Empty code|
IP-CNN | [Zhang et al. 2022](https://doi.org/10.1109/TGRS.2021.3093334) | Feature-level fusion with 2D CNN and view-reconstruction. | https://github.com/HelloPiPi/IP-CNN-code |
MV CNN | [Lu et al. 2022](https://doi.org/10.1016/j.rse.2021.112830)| Feature-level fusion with 2D CNN and adaptive attention. | https://github.com/GeoX-Lab/UnifiedDL-UFZ-extraction |
SE$^2$Net | [Fang et al. 2022](https://doi.org/10.1109/LGRS.2021.3121028) | Feature-level fusion with 2D CNN. | https://github.com/likyoo/Multimodal-Remote-Sensing-Toolkit |
EndNet | [Hong et al. 2022](https://doi.org/10.1109/LGRS.2020.3017414) | Feature-level fusion with 2D CNN and view-reconstruction. | https://github.com/danfenghong/IEEE_GRSL_EndNet |
MAHiDFNet | [Wang et al. 2022](https://doi.org/10.1016/j.inffus.2021.12.008) | Dense feature fusion with 2D CNN. | https://github.com/SYFYN0317/-MAHiDFNet |
AM$^3$Net | [Wang et al. 2022](https://doi.org/10.1109/TCSVT.2022.3148257) | Feature-level fusion with 2D CNN and cross attention. | https://github.com/Cimy-wang/AM3Net_Multimodal_Data_Fusion |
AMM-FuseNet | [Ma et al. 2022](https://doi.org/10.3390/rs14184458) | Feature-level fusion with 2D CNN and attention. | https://github.com/oktaykarakus/ReSIF/tree/main/AMM-FuseNet |
MCANet | [Li et al. 2022](https://doi.org/10.1016/j.jag.2021.102638) | Dense fusion with 2D CNN and cross attention. | https://github.com/yisun98/SOLC |
ChangeFormer | [Bandara et al. 2022](https://doi.org/10.1109/IGARSS46834.2022.9883686) | Dense fusion with transformer and attention. | https://github.com/wgcban/ChangeFormer  |
CMAFF | [Qingyun et al. 2022](https://doi.org/10.1016/j.patcog.2022.108786) | Dense fusion with 2D CNN and cross attention. | https://github.com/DocF/CMAFF |
OmbriaNet | [Drakonakis et al. 2022](https://doi.org/10.1109/JSTARS.2022.3155559) | Feature fusion with 2D CNN and skip-connections | https://github.com/geodrak/OMBRIA |
DCSA-Net | [Wang et al. 2022](https://doi.org/10.3390/rs14194941) | Hybrid fusion with 2D CNN and attention. | https://github.com/Julia90/DCSA-Net |
Siamese U-Net | [Cummings et al. 2022](https://doi.org/10.1109/IGARSS46834.2022.9884834) | Dense fusion with 2D CNN and skip-connections | https://github.com/solcummings/earthvision2021-weakly-supervised |
SatViT | [Fuller et al.](https://doi.org/10.1109/LGRS.2022.3201489) | Input-level fusion with ViT (with self-supervised training) |  https://github.com/antofuller/SatViT |
ELECTS | [Russwurm et al. 2023](https://doi.org/10.1016/j.isprsjprs.2022.12.016) | Input-level fusion with LSTM. | https://github.com/marccoru/elects |
MV CNN | [Ferrari et al. 2023](https://doi.org/10.1109/LGRS.2023.3242430) | Multiple fusion strategies with 2D CNN (encoder-decoder) | https://github.com/felferrari/deforestation-from-data-fusion |
AFCF3D-Net | [Ye et al. 2023](https://arxiv.org/abs/2302.05109) | Input-level fusion with 3D CNN. | https://github.com/wm-Githuber/AFCF3D-Net |
UnCRtainTS | [Ebel et al 2023](https://openaccess.thecvf.com/content/CVPR2023W/EarthVision/html/Ebel_UnCRtainTS_Uncertainty_Quantification_for_Cloud_Removal_in_Optical_Satellite_Time_CVPRW_2023_paper.html) | Input fusion with 2D CNN and attention. | https://github.com/PatrickTUM/UnCRtainTS |
MFT | [Roy et al. 2023](https://doi.org/10.1109/TGRS.2023.3286826) | Feature-level fusion with transformer modules (one source - LIDAR- is used as a query over the main source - optical) | https://github.com/AnkurDeria/MFT |
OOD Fusion | [Gawlikowski et al. 2023](https://doi.org/10.1186/s13634-023-01008-z) | Input-level, Feature-level, and Decision-level fusion with CNN and weighted average aggregation | https://github.com/JakobCode/OOD_DataFusion |
PRESTO | [Tseng et al. 2023](http://arxiv.org/abs/2304.14065) | Input-level fusion with transformer modules (self-supervised pretraining) | https://github.com/nasaharvest/presto |
Cross-HL | [Roy et al. 2023](https://ieeexplore.ieee.org/document/10462184) | Feature-level fusion with directed attention in transformer layers |  https://github.com/AtriSukul1508/Cross-HL |
SCT Fusion | [Hoffman et al. 2023](https://doi.org/10.1109/IGARSS52108.2023.10281927) | Dense fusion with tranformer layers and class tokens in all |  https://git.tu-berlin.de/rsim/sct-fusion |
MMST-ViT | [Lin et al. 2023](https://ieeexplore.ieee.org/abstract/document/10376769) | Feature-level fusion with transformer layers | https://github.com/fudong03/MMST-ViT |
EarthGPT | [Zhang et al. 2024](http://arxiv.org/abs/2401.16822) | Feature-level fusion with transformer layers | https://github.com/wivizhang/EarthGPT |
ContextFormer | [Benson et al. 2024](http://arxiv.org/abs/2303.16198) | Feature-level fusion with transformer | https://github.com/vitusbenson/greenearthnet |



> Feel free to ask me to update some content! 

---

Some abbrevations
| Abbrevation | name |
| --- | --- |
| CNN | convolutional neural network |
| LSTM | long-short term memory |
| NN | neural network|
| PSE-TAE | pixel set encoder - temporal attention encoder |
