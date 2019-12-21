<!-- No Heading Fix -->
Collection of papers, datasets, code and other resources for object detection and tracking using deep learning
<!-- MarkdownTOC -->

- [Papers](#paper_s_)
    - [Static Detection](#static_detectio_n_)
        - [Region Proposal](#region_proposal_)
        - [RCNN](#rcn_n_)
        - [YOLO](#yol_o_)
        - [SSD](#ssd_)
        - [RetinaNet](#retinanet_)
        - [Anchor Free](#anchor_free_)
        - [Misc](#mis_c_)
    - [Video Detection](#video_detectio_n_)
        - [Tubelet](#tubelet_)
        - [FGFA](#fgf_a_)
        - [RNN](#rnn_)
    - [Multi Object Tracking](#multi_object_tracking_)
        - [Deep Learning](#deep_learning_)
        - [RNN](#rnn__1)
        - [Unsupervised Learning](#unsupervised_learning_)
        - [Reinforcement Learning](#reinforcement_learning_)
        - [Network Flow](#network_flow_)
        - [Graph Optimization](#graph_optimization_)
        - [Baseline](#baselin_e_)
    - [Single Object Tracking](#single_object_tracking_)
        - [Reinforcement Learning](#reinforcement_learning__1)
        - [Siamese](#siamese_)
        - [Misc](#mis_c__1)
    - [Deep Learning](#deep_learning__1)
        - [Synthetic Gradients](#synthetic_gradient_s_)
    - [Unsupervised Learning](#unsupervised_learning__1)
    - [Interpolation](#interpolation_)
    - [Autoencoder](#autoencoder_)
        - [Variational](#variational_)
- [Datasets](#dataset_s_)
    - [Multi Object Tracking](#multi_object_tracking__1)
    - [Single Object Tracking](#single_object_tracking__1)
    - [Video Detection](#video_detectio_n__1)
        - [Video Understanding / Activity Recognition](#video_understanding___activity_recognitio_n_)
    - [Static Detection](#static_detectio_n__1)
        - [Animals](#animals_)
    - [Boundary Detection](#boundary_detectio_n_)
    - [Static Segmentation](#static_segmentation_)
    - [Video Segmentation](#video_segmentation_)
    - [Classification](#classificatio_n_)
    - [Optical Flow](#optical_flow_)
- [Code](#cod_e_)
    - [Multi Object Tracking](#multi_object_tracking__2)
    - [Single Object Tracking](#single_object_tracking__2)
        - [GUI Application / Large Scale Tracking / Animals](#gui_application___large_scale_tracking___animal_s_)
    - [Video Detection](#video_detectio_n__2)
    - [Static Detection and Matching](#static_detection_and_matching_)
        - [Frameworks](#framework_s_)
        - [Region Proposal](#region_proposal__1)
        - [FPN](#fpn_)
        - [RCNN](#rcn_n__1)
        - [SSD](#ssd__1)
        - [YOLO](#yol_o__1)
        - [Anchor Free](#anchor_free__1)
        - [Misc](#mis_c__2)
        - [Matching](#matchin_g_)
        - [Boundary Detection](#boundary_detectio_n__1)
    - [Optical Flow](#optical_flow__1)
    - [Instance Segmentation](#instance_segmentation_)
        - [Frameworks](#framework_s__1)
    - [Semantic Segmentation](#semantic_segmentation_)
    - [Video Segmentation](#video_segmentation__1)
    - [Autoencoders](#autoencoder_s_)
    - [Classification](#classificatio_n__1)
    - [Misc](#mis_c__3)
- [Collections](#collections_)
    - [Datasets](#dataset_s__1)
    - [Static Detection](#static_detectio_n__2)
    - [Single Object Tracking](#single_object_tracking__3)
    - [Multi Object Tracking](#multi_object_tracking__3)
    - [Segmentation](#segmentatio_n_)
    - [Deep Compressed Sensing](#deep_compressed_sensin_g_)
    - [Misc](#mis_c__4)
- [Tutorials](#tutorials_)
    - [Static Detection](#static_detectio_n__3)
    - [Video Detection](#video_detectio_n__3)
    - [Instance Segmentation](#instance_segmentation__1)
    - [Deep RL](#deep_rl_)
    - [Autoencoders](#autoencoder_s__1)

<!-- /MarkdownTOC -->

<a id="paper_s_"></a>
# Papers

<a id="static_detectio_n_"></a>
## Static Detection

<a id="region_proposal_"></a>
### Region Proposal
- **Scalable Object Detection Using Deep Neural Networks**
[cvpr14]
[[pdf]](static_detection/region_proposal/Scalable%20Object%20Detection%20Using%20Deep%20Neural%20Networks%20cvpr14.pdf)
[[notes]](static_detection/notes/Scalable%20Object%20Detection%20Using%20Deep%20Neural%20Networks%20cvpr14.pdf)
- **Selective Search for Object Recognition**
[ijcv2013]
[[pdf]](static_detection/region_proposal/Selective%20Search%20for%20Object%20Recognition%20ijcv2013.pdf)
[[notes]](static_detection/notes/Selective%20Search%20for%20Object%20Recognition%20ijcv2013.pdf)

<a id="rcn_n_"></a>
### RCNN
- **Faster R-CNN Towards Real-Time Object Detection with Region Proposal Networks**
[tpami17]
[[pdf]](static_detection/rcnn/Faster%20R-CNN%20Towards%20Real-Time%20Object%20Detection%20with%20Region%20Proposal%20Networks%20tpami17%20ax16_1.pdf)
[[notes]](static_detection/notes/Faster_R-CNN.pdf)
- **RFCN - Object Detection via Region-based Fully Convolutional Networks**
[nips16]
[Microsoft Research]
[[pdf]](static_detection/rcnn/RFCN-Object%20Detection%20via%20Region-based%20Fully%20Convolutional%20Networks%20nips16.pdf)
[[notes]](static_detection/notes/RFCN.pdf)  
- **Mask R-CNN**
[iccv17]
[Facebook AI Research]
[[pdf]](static_detection/rcnn/Mask%20R-CNN%20ax17_4%20iccv17.pdf)
[[notes]](static_detection/notes/Mask%20R-CNN%20ax17_4%20iccv17.pdf)
[[arxiv]](https://arxiv.org/abs/1703.06870)
[[code (keras)]](https://github.com/matterport/Mask_RCNN)
[[code (tensorflow)]](https://github.com/CharlesShang/FastMaskRCNN)

<a id="yol_o_"></a>
### YOLO
- **You Only Look Once Unified, Real-Time Object Detection**
[ax1605]
[[pdf]](static_detection/yolo/You%20Only%20Look%20Once%20Unified,%20Real-Time%20Object%20Detection%20ax1605.pdf)
[[notes]](static_detection/notes/You%20Only%20Look%20Once%20Unified,%20Real-Time%20Object%20Detection%20ax1605.pdf)
- **YOLO9000 Better, Faster, Stronger**
[ax1612]
[[pdf]](static_detection/yolo/YOLO9000%20Better,%20Faster,%20Stronger%20ax16_12.pdf)
[[notes]](static_detection/notes/YOLO9000%20Better,%20Faster,%20Stronger%20ax16_12.pdf)
- **YOLOv3 An Incremental Improvement**
[ax1804]
[[pdf]](static_detection/yolo/YOLOv3%20An%20Incremental%20Improvement%20ax180408.pdf)
[[notes]](static_detection/notes/YOLOv3%20An%20Incremental%20Improvement%20ax180408.pdf)

<a id="ssd_"></a>
### SSD
- **SSD Single Shot MultiBox Detector**
[ax1612/eccv16]
[[pdf]](static_detection/ssd/SSD%20Single%20Shot%20MultiBox%20Detector%20eccv16_ax16_12.pdf)
[[notes]](static_detection/notes/SSD.pdf)
- **DSSD  Deconvolutional Single Shot Detector**
[ax1701]
[[pdf]](static_detection/ssd/DSSD%20Deconvolutional%20Single%20Shot%20Detector%20ax1701.06659.pdf)
[[notes]](static_detection/notes/DSSD.pdf)

<a id="retinanet_"></a>
### RetinaNet
- **Feature Pyramid Networks for Object Detection**
[ax1704]
[[pdf]](static_detection/retinanet/Feature%20Pyramid%20Networks%20for%20Object%20Detection%20ax170419.pdf)
[[notes]](static_detection/notes/FPN.pdf)
- **Focal Loss for Dense Object Detection**
[ax180207/iccv17]
[[pdf]](static_detection/retinanet/Focal%20Loss%20for%20Dense%20Object%20Detection%20ax180207%20iccv17.pdf)
[[notes]](static_detection/notes/focal_loss.pdf) 

<a id="anchor_free_"></a>
### Anchor Free

- **FoveaBox: Beyond Anchor-based Object Detector**
[ax1904]
[[pdf]](static_detection/anchor_free/FoveaBox%20Beyond%20Anchor-based%20Object%20Detector%20ax1904.03797.pdf)
[[notes]](static_detection/notes/FoveaBox%20Beyond%20Anchor-based%20Object%20Detector%20ax1904.03797.pdf)
[[code]](https://github.com/taokong/FoveaBox)
- **CornerNet: Detecting Objects as Paired Keypoints**
[ax1903/ijcv19]
[[pdf]](static_detection/anchor_free/CornerNet%20Detecting%20Objects%20as%20Paired%20Keypoints%20ax1903%20ijcv19.pdf)
[[notes]](static_detection/notes/CornerNet%20Detecting%20Objects%20as%20Paired%20Keypoints%20ax1903%20ijcv19.pdf)
[[code]](https://github.com/princeton-vl/CornerNet)

<a id="mis_c_"></a>
### Misc
- **OverFeat Integrated Recognition, Localization and Detection using Convolutional Networks**
[ax1402/iclr14]
[[pdf]](static_detection/OverFeat%20Integrated%20Recognition,%20Localization%20and%20Detection%20using%20Convolutional%20Networks%20ax1402%20iclr14.pdf)
[[notes]](static_detection/notes/OverFeat%20Integrated%20Recognition,%20Localization%20and%20Detection%20using%20Convolutional%20Networks%20ax1402%20iclr14.pdf)
- **LSDA Large scale detection through adaptation**
[ax1411/nips14]
[[pdf]](static_detection/LSDA%20Large%20scale%20detection%20through%20adaptation%20nips14%20ax14_11.pdf)
[[notes]](static_detection/notes/LSDA%20Large%20scale%20detection%20through%20adaptation%20nips14%20ax14_11.pdf)
- **Acquisition of Localization Confidence for Accurate Object Detection**
[ax1807/eccv18]
[[pdf]](static_detection/Acquisition%20of%20Localization%20Confidence%20for%20Accurate%20Object%20Detection%201807.11590%20eccv18.pdf)
[[notes]](static_detection/notes/IOU-Net.pdf)
[[code]](https://github.com/vacancy/PreciseRoIPooling)
    
<a id="video_detectio_n_"></a>
## Video Detection

<a id="tubelet_"></a>
### Tubelet
* **Object Detection from Video Tubelets with Convolutional Neural Networks**
[cvpr16]
[[pdf]](video_detection/tubelets/Object_Detection_from_Video_Tubelets_with_Convolutional_Neural_Networks_CVPR16.pdf)
[[notes]](video_detection/notes/Object_Detection_from_Video_Tubelets_with_Convolutional_Neural_Networks_CVPR16.pdf)
* **Object Detection in Videos with Tubelet Proposal Networks**
[ax1704/cvpr17]
[[pdf]](video_detection/tubelets/Object_Detection_in_Videos_with_Tubelet_Proposal_Networks_ax1704_cvpr17.pdf)
[[notes]](video_detection/notes/Object_Detection_in_Videos_with_Tubelet_Proposal_Networks_ax1704_cvpr17.pdf)

<a id="fgf_a_"></a>
### FGFA
* **Deep Feature Flow for Video Recognition**
[cvpr17]
[Microsoft Research]
[[pdf]](video_detection/fgfa/Deep%20Feature%20Flow%20For%20Video%20Recognition%20cvpr17.pdf)
[[arxiv]](https://arxiv.org/abs/1611.07715)
[[code]](https://github.com/msracver/Deep-Feature-Flow)   
* **Flow-Guided Feature Aggregation for Video Object Detection**
[ax1708/iccv17]
[[pdf]](video_detection/fgfa/Flow-Guided%20Feature%20Aggregation%20for%20Video%20Object%20Detection%20ax1708%20iccv17.pdf)
[[notes]](video_detection/notes/Flow-Guided%20Feature%20Aggregation%20for%20Video%20Object%20Detection%20ax1708%20iccv17.pdf)
* **Towards High Performance Video Object Detection**
[ax1711]
[Microsoft]
[[pdf]](video_detection/fgfa/Towards%20High%20Performance%20Video%20Object%20Detection%20ax171130%20microsoft.pdf)
[[notes]](video_detection/notes/Towards%20High%20Performance%20Video%20Object%20Detection%20ax171130%20microsoft.pdf)

<a id="rnn_"></a>
### RNN
* **Online Video Object Detection using Association LSTM**
[iccv17]
[[pdf]](video_detection/rnn/Online%20Video%20Object%20Detection%20using%20Association%20LSTM%20iccv17.pdf)
[[notes]](video_detection/notes/Online%20Video%20Object%20Detection%20using%20Association%20LSTM%20iccv17.pdf)
* **Context Matters Reﬁning Object Detection in Video with Recurrent Neural Networks**
[bmvc16]
[[pdf]](video_detection/rnn/Context%20Matters%20Reﬁning%20Object%20Detection%20in%20Video%20with%20Recurrent%20Neural%20Networks%20bmvc16.pdf)
[[notes]](video_detection/notes/Context%20Matters%20Reﬁning%20Object%20Detection%20in%20Video%20with%20Recurrent%20Neural%20Networks%20bmvc16.pdf)

<a id="multi_object_tracking_"></a>
##  Multi Object Tracking

<a id="deep_learning_"></a>
### Deep Learning

* **Online Multi-Object Tracking Using CNN-based Single Object Tracker with Spatial-Temporal Attention Mechanism**
[ax1708/iccv17]
[[pdf]](multi_object_tracking/deep_learning/Online%20Multi-Object%20Tracking%20Using%20CNN-based%20Single%20Object%20Tracker%20with%20Spatial-Temporal%20Attention%20Mechanism%201708.02843%20iccv17.pdf)
[[arxiv]](https://arxiv.org/abs/1708.02843)
[[notes]](multi_object_tracking/notes/Online%20Multi-Object%20Tracking%20Using%20CNN-based%20Single%20Object%20Tracker%20with%20Spatial-Temporal%20Attention%20Mechanism%201708.02843%20iccv17.pdf)
* **Online multi-object tracking with dual matching attention networks**
[ax1902/eccv18]
[[pdf]](multi_object_tracking/deep_learning/Online%20multi-object%20tracking%20with%20dual%20matching%20attention%20networks%201902.00749%20eccv18.pdf)
[[arxiv]](https://arxiv.org/abs/1902.00749)
[[notes]](multi_object_tracking/notes/Online%20multi-object%20tracking%20with%20dual%20matching%20attention%20networks%201902.00749%20eccv18.pdf)
[[code]](https://github.com/jizhu1023/DMAN_MOT)
* **FAMNet Joint Learning of Feature, Affinity and Multi-Dimensional Assignment for Online Multiple Object Tracking**
[iccv19]
[[pdf]](multi_object_tracking/deep_learning/FAMNet%20Joint%20Learning%20of%20Feature,%20Affinity%20and%20Multi-Dimensional%20Assignment%20for%20Online%20Multiple%20Object%20Tracking%20iccv19.pdf)
[[notes]](multi_object_tracking/notes/FAMNet%20Joint%20Learning%20of%20Feature,%20Affinity%20and%20Multi-Dimensional%20Assignment%20for%20Online%20Multiple%20Object%20Tracking%20iccv19.pdf)
* **MOTS Multi-Object Tracking and Segmentation**
[cvpr19]
[[pdf]](multi_object_tracking/deep_learning/MOTS%20Multi-Object%20Tracking%20and%20Segmentation%20ax1904%20cvpr19.pdf)
[[notes]](multi_object_tracking/notes/MOTS%20Multi-Object%20Tracking%20and%20Segmentation%20ax1904%20cvpr19.pdf)
[[code]](https://github.com/VisualComputingInstitute/TrackR-CNN)
[[project/data]](https://www.vision.rwth-aachen.de/page/mots)

<a id="rnn__1"></a>
### RNN
* **Tracking The Untrackable: Learning To Track Multiple Cues with Long-Term Dependencies**
[ax1704/iccv17]
[Stanford]
[[pdf]](multi_object_tracking/rnn/Tracking%20The%20Untrackable%20Learning%20To%20Track%20Multiple%20Cues%20with%20Long-Term%20Dependencies%20ax17_4_iccv17.pdf)
[[notes]](multi_object_tracking/notes/Tracking_The_Untrackable_Learning_To_Track_Multiple_Cues_with_Long-Term_Dependencies.pdf)
[[arxiv]](https://arxiv.org/abs/1701.01909)
[[project]](http://web.stanford.edu/~alahi/),
* **Multi-object Tracking with Neural Gating Using Bilinear LSTM**
[eccv18]
[[pdf]](multi_object_tracking/rnn/Multi-object%20Tracking%20with%20Neural%20Gating%20Using%20Bilinear%20LSTM_eccv18.pdf)
[[notes]](multi_object_tracking/notes/Multi-object%20Tracking%20with%20Neural%20Gating%20Using%20Bilinear%20LSTM_eccv18.pdf)

<a id="unsupervised_learning_"></a>
### Unsupervised Learning
* **Tracking by Animation: Unsupervised Learning of Multi-Object Attentive Trackers**
[ax1809/cvpr19]
[[pdf]](multi_object_tracking/unsupervised/Tracking%20by%20Animation%20Unsupervised%20Learning%20of%20Multi-Object%20Attentive%20Trackers%20cvpr19%20ax1809.03137.pdf)
[[arxiv]](https://arxiv.org/abs/1809.03137)
[[notes]](multi_object_tracking/notes/Tracking%20by%20Animation%20Unsupervised%20Learning%20of%20Multi-Object%20Attentive%20Trackers%20cvpr19%20ax1809.03137.pdf)
[[code]](https://github.com/zhen-he/tracking-by-animation)

<a id="reinforcement_learning_"></a>
### Reinforcement Learning
* **Learning to Track: Online Multi-object Tracking by Decision Making**
[iccv15]
[Stanford]
[[pdf]](multi_object_tracking/rl/Learning%20to%20Track%20Online%20Multi-object%20Tracking%20by%20Decision%20Making%20%20iccv15.pdf)
[[notes]](multi_object_tracking/notes/Learning_to_Track_Online_Multi-object_Tracking_by_Decision_Making__iccv15.pdf)
[[code (matlab)]](https://github.com/yuxng/MDP_Tracking)
[[project]](https://yuxng.github.io/)
* **Collaborative Deep Reinforcement Learning for Multi-Object Tracking**
[eccv18]
[[pdf]](multi_object_tracking/rl/Collaborative%20Deep%20Reinforcement%20Learning%20for%20Multi-Object%20Tracking_eccv18.pdf)
[[notes]](multi_object_tracking/notes/Collaborative%20Deep%20Reinforcement%20Learning%20for%20Multi-Object%20Tracking_eccv18.pdf)

<a id="network_flow_"></a>
### Network Flow
* **Near-Online Multi-target Tracking with Aggregated Local Flow Descriptor**
[iccv15]
[NEC Labs]
[[pdf]](multi_object_tracking/network_flow/Near-online%20multi-target%20tracking%20with%20aggregated%20local%20%EF%AC%82ow%20descriptor%20iccv15.pdf)
[[author]](http://www-personal.umich.edu/~wgchoi/)
[[notes]](multi_object_tracking/notes/NOMT.pdf)  
* **Deep Network Flow for Multi-Object Tracking**
[cvpr17]
[NEC Labs]
[[pdf]](multi_object_tracking/network_flow/Deep%20Network%20Flow%20for%20Multi-Object%20Tracking%20cvpr17.pdf)
[[supplementary]](multi_object_tracking/network_flow/Deep%20Network%20Flow%20for%20Multi-Object%20Tracking%20cvpr17_supplemental.pdf)
[[notes]](multi_object_tracking/notes/Deep%20Network%20Flow%20for%20Multi-Object%20Tracking%20cvpr17.pdf)  

<a id="graph_optimization_"></a>
### Graph Optimization
* **A Multi-cut Formulation for Joint Segmentation and Tracking of Multiple Objects**
[ax1607]
[highest MT on MOT2015]
[University of Freiburg, Germany]
[[pdf]](multi_object_tracking/batch/A%20Multi-cut%20Formulation%20for%20Joint%20Segmentation%20and%20Tracking%20of%20Multiple%20Objects%20ax16_9%20%5Bbest%20MT%20on%20MOT15%5D.pdf)
[[arxiv]](https://arxiv.org/abs/1607.06317)
[[author]](https://lmb.informatik.uni-freiburg.de/people/keuper/publications.html)
[[notes]](multi_object_tracking/notes/A_Multi-cut_Formulation_for_Joint_Segmentation_and_Tracking_of_Multiple_Objects.pdf)

<a id="baselin_e_"></a>
### Baseline
* **Simple Online and Realtime Tracking**
[icip16]
[[pdf]](multi_object_tracking/baseline/Simple%20Online%20and%20Realtime%20Tracking%20ax1707%20icip16.pdf)
[[notes]](multi_object_tracking/notes/Simple%20Online%20and%20Realtime%20Tracking%20ax1707%20icip16.pdf)
[[code]](https://github.com/abewley/sort)
* **High-Speed Tracking-by-Detection Without Using Image Information**
[avss17]
[[pdf]](multi_object_tracking/baseline/High-Speed%20Tracking-by-Detection%20Without%20Using%20Image%20Information%20avss17.pdf)
[[notes]](multi_object_tracking/notes/High-Speed%20Tracking-by-Detection%20Without%20Using%20Image%20Information%20avss17.pdf)
[[code]](https://github.com/bochinski/iou-tracker)
      
<a id="single_object_tracking_"></a>
## Single Object Tracking

<a id="reinforcement_learning__1"></a>
### Reinforcement Learning
* **Deep Reinforcement Learning for Visual Object Tracking in Videos**
[ax1704] [USC-Santa Barbara, Samsung Research]
[[pdf]](single_object_tracking/reinforcement_learning/Deep%20Reinforcement%20Learning%20for%20Visual%20Object%20Tracking%20in%20Videos%20ax17_4.pdf)
[[arxiv]](https://arxiv.org/abs/1701.08936)
[[author]](http://www.cs.ucsb.edu/~dazhang/)
[[notes]](single_object_tracking/notes/Deep_Reinforcement_Learning_for_Visual_Object_Tracking_in_Videos.pdf)  
* **Visual Tracking by Reinforced Decision Making**
[ax1702] [Seoul National University, Chung-Ang University]
[[pdf]](single_object_tracking/reinforcement_learning/Visual%20Tracking%20by%20Reinforced%20Decision%20Making%20ax17_2.pdf)
[[arxiv]](https://arxiv.org/abs/1702.06291)
[[author]](http://cau.ac.kr/~jskwon/)   
[[notes]](single_object_tracking/notes/Visual_Tracking_by_Reinforced_Decision_Making_ax17.pdf)
* **Action-Decision Networks for Visual Tracking with Deep Reinforcement Learning**
[cvpr17] [Seoul National University]
[[pdf]](single_object_tracking/reinforcement_learning/Action-Decision%20Networks%20for%20Visual%20Tracking%20with%20Deep%20Reinforcement%20Learning%20%20cvpr17%20supplementary.pdf)
[[supplementary]](single_object_tracking/reinforcement_learning/Action-Decision%20Networks%20for%20Visual%20Tracking%20with%20Deep%20Reinforcement%20Learning%20%20cvpr17.pdf)
[[project]](https://sites.google.com/view/cvpr2017-adnet)
[[notes]](single_object_tracking/notes/Action-Decision_Networks_for_Visual_Tracking_with_Deep_Reinforcement_Learning_cvpr17.pdf) 
[[code]](https://github.com/ildoonet/tf-adnet-tracking) 
* **End-to-end Active Object Tracking via Reinforcement Learning**
[ax1705]
[Peking University, Tencent AI Lab]
[[pdf]](single_object_tracking/reinforcement_learning/End-to-end%20Active%20Object%20Tracking%20via%20Reinforcement%20Learning%20ax17_5.pdf)
[[arxiv]](https://arxiv.org/abs/1705.10561)

<a id="siamese_"></a>
### Siamese
* **Fully-Convolutional Siamese Networks for Object Tracking**
[eccv16]
[[pdf]](single_object_tracking/siamese/Fully-Convolutional%20Siamese%20Networks%20for%20Object%20Tracking%20eccv16_9.pdf)
[[project]](https://www.robots.ox.ac.uk/~luca/siamese-fc.html)
[[notes]](single_object_tracking/notes/SiameseFC.pdf)  
* **High Performance Visual Tracking with Siamese Region Proposal Network**
[cvpr18]
[[pdf]](single_object_tracking/siamese/High%20Performance%20Visual%20Tracking%20with%20Siamese%20Region%20Proposal%20Network_cvpr18.pdf)
[[author]](http://www.robots.ox.ac.uk/~qwang/)
[[notes]](single_object_tracking/notes/High%20Performance%20Visual%20Tracking%20with%20Siamese%20Region%20Proposal%20Network_cvpr18.pdf)  

<a id="mis_c__1"></a>
### Misc
* **ATOM Accurate Tracking by Overlap Maximization**
[cvpr19]
[[pdf]](single_object_tracking/ATOM%20Accurate%20Tracking%20by%20Overlap%20Maximization%20ax1811.07628%20cvpr19.pdf)
[[notes]](single_object_tracking/notes/ATOM%20Accurate%20Tracking%20by%20Overlap%20Maximization%20ax1811.07628%20cvpr19.pdf)
[[code]](https://github.com/visionml/pytracking)

<a id="deep_learning__1"></a>
##  Deep Learning

- **Do Deep Nets Really Need to be Deep**
[nips14]
[[pdf]](deep_learning/theory/Do%20Deep%20Nets%20Really%20Need%20to%20be%20Deep%20ax1410%20nips14.pdf)
[[notes]](deep_learning/notes/Do%20Deep%20Nets%20Really%20Need%20to%20be%20Deep%20ax1410%20nips14.pdf)

<a id="synthetic_gradient_s_"></a>
### Synthetic Gradients
- **Decoupled Neural Interfaces using Synthetic Gradients**
[ax1608]
[[pdf]](deep_learning/synthetic_gradients/Decoupled%20Neural%20Interfaces%20using%20Synthetic%20Gradients%20ax1608.05343.pdf)
[[notes]](deep_learning/notes/Decoupled%20Neural%20Interfaces%20using%20Synthetic%20Gradients%20ax1608.05343.pdf)    
- **Understanding Synthetic Gradients and Decoupled Neural Interfaces**
[ax1703]
[[pdf]](deep_learning/synthetic_gradients/Understanding%20Synthetic%20Gradients%20and%20Decoupled%20Neural%20Interfaces%20ax1703.00522.pdf)
[[notes]](deep_learning/notes/Understanding%20Synthetic%20Gradients%20and%20Decoupled%20Neural%20Interfaces%20ax1703.00522.pdf)

<a id="unsupervised_learning__1"></a>
## Unsupervised Learning
- **Learning Features by Watching Objects Move**
(cvpr17)
[[pdf]](unsupervised/segmentation/Learning%20Features%20by%20Watching%20Objects%20Move%20ax170412%20cvpr17.pdf)
[[notes]](unsupervised/notes/Learning%20Features%20by%20Watching%20Objects%20Move%20ax170412%20cvpr17.pdf)
    
<a id="interpolation_"></a>
##  Interpolation
- **Video Frame Interpolation via Adaptive Convolution**
[cvpr17 / iccv17]
[[pdf (cvpr17)]](interpolation/Video%20Frame%20Interpolation%20via%20Adaptive%20Convolution%20ax1703.pdf)
[[pdf (iccv17)]](interpolation/Video%20Frame%20Interpolation%20via%20Adaptive%20Separable%20Convolution%20iccv17.pdf)
[[ppt]](interpolation/notes/Video%20Frame%20Interpolation%20via%20Adaptive%20Convolution%20ax1703.pdf)

<a id="autoencoder_"></a>
## Autoencoder

<a id="variational_"></a>
### Variational
- **beta-VAE Learning Basic Visual Concepts with a Constrained Variational Framework** [iclr17]
[[pdf]](autoencoder/variational/beta-VAE%20Learning%20Basic%20Visual%20Concepts%20with%20a%20Constrained%20Variational%20Framework%20iclr17.pdf)
[[notes]](autoencoder/notes/beta-VAE%20Learning%20Basic%20Visual%20Concepts%20with%20a%20Constrained%20Variational%20Framework%20iclr17.pdf)
- **Disentangling by Factorising** [ax1806]
[[pdf]](autoencoder/variational/Disentangling%20by%20Factorising%20ax1806.pdf)
[[notes]](autoencoder/notes/Disentangling%20by%20Factorising%20ax1806.pdf)  
    
<a id="dataset_s_"></a>
# Datasets

<a id="multi_object_tracking__1"></a>
## Multi Object Tracking

- [IDOT](https://www.cs.uic.edu/Bits/YanziJin)
- [UA-DETRAC Benchmark Suite](http://detrac-db.rit.albany.edu/)
- [GRAM Road-Traffic Monitoring](http://agamenon.tsc.uah.es/Personales/rlopez/data/rtm/)
- [Stanford Drone Dataset](http://cvgl.stanford.edu/projects/uav_data/)
- [Ko-PER Intersection Dataset](http://www.uni-ulm.de/in/mrm/forschung/datensaetze.html)
- [TRANCOS](http://agamenon.tsc.uah.es/Personales/rlopez/data/trancos/)
- [Urban Tracker](https://www.jpjodoin.com/urbantracker/dataset.html)
- [DARPA VIVID / PETS 2005](http://vision.cse.psu.edu/data/vividEval/datasets/datasets.html) [Non stationary camera]
- [KIT-AKS](http://i21www.ira.uka.de/image_sequences/) [No ground truth]
- [CBCL StreetScenes Challenge Framework](http://cbcl.mit.edu/software-datasets/streetscenes/) [No top down viewpoint]
- [MOT 2015](https://motchallenge.net/data/2D_MOT_2015/) [mostly street level viewpoint]
- [MOT 2016](https://motchallenge.net/data/MOT16/) [mostly street level viewpoint]
- [MOT 2017](https://motchallenge.net/data/MOT17/) [mostly street level viewpoint]
- [MOTS: Multi-Object Tracking and Segmentation](https://www.vision.rwth-aachen.de/page/mots) [MOT and KITTI]
- [CVPR 2019](https://motchallenge.net/data/11) [mostly street level viewpoint]
- [PETS 2009](http://www.cvg.reading.ac.uk/PETS2009/a.html) [No vehicles]
- [PETS 2017](https://motchallenge.net/data/PETS2017/) [Low density] [mostly pedestrians]
- [DukeMTMC](http://vision.cs.duke.edu/DukeMTMC/) [multi camera] [static background] [pedestrians] [above-street level viewpoint] [website not working]
- [KITTI Tracking Dataset](http://www.cvlibs.net/datasets/kitti/eval_tracking.php) [No top down viewpoint] [non stationary camera]
- [The WILDTRACK Seven-Camera HD Dataset](https://cvlab.epfl.ch/data/data-wildtrack/) [pedestrian detection and tracking]
- [3D Traffic Scene Understanding from Movable Platforms](http://www.cvlibs.net/projects/intersection/) [intersection traffic] [stereo setup] [moving camera]
- [LOST : Longterm Observation of Scenes with Tracks](http://lost.cse.wustl.edu/) [top down and street level viewpoint] [no ground truth]
 
<a id="single_object_tracking__1"></a>
## Single Object Tracking

- [TrackingNet: A Large-Scale Dataset and Benchmark for Object Tracking in the Wild](https://tracking-net.org/) [eccv18]
- [LaSOT: Large-scale Single Object Tracking](https://cis.temple.edu/lasot/) [cvpr19]
- [Need for speed: A benchmark for higher frame rate object tracking](http://ci2cv.net/nfs/index.html) [iccv17]
- [Long-term Tracking in the Wild A Benchmark](https://oxuva.github.io/long-term-tracking-benchmark/) [eccv18]
- [UAV123: A benchmark and simulator for UAV tracking](https://uav123.org/) [eccv16] [[project]](https://ivul.kaust.edu.sa/Pages/pub-benchmark-simulator-uav.aspx)
- [Sim4CV A Photo-Realistic Simulator for Computer Vision Applications](https://sim4cv.org/) [ijcv18]   

<a id="video_detectio_n__1"></a>
## Video Detection

- [YouTube-BB](https://research.google.com/youtube-bb/download.html)

<a id="video_understanding___activity_recognitio_n_"></a>
### Video Understanding / Activity Recognition
 
- [YouTube-8M](https://research.google.com/youtube8m/)
- [AVA: A Video Dataset of Atomic Visual Action](https://research.google.com/ava/)
- [VIRAT Video Dataset](http://www.viratdata.org/)

<a id="static_detectio_n__1"></a>
## Static Detection
- [PASCAL Visual Object Classes](http://host.robots.ox.ac.uk/pascal/VOC/)
- [A Large-Scale Dataset for Vehicle Re-Identification in the Wild](https://github.com/PKU-IMRE/VERI-Wild)
[cvpr19]
- [Object Detection-based annotations for some frames of the VIRAT dataset](https://github.com/ahrnbom/ViratAnnotationObjectDetection)
 
<a id="animals_"></a>
### Animals

- [Wildlife Image and Localization Dataset (species and bounding box labels)](https://lev.cs.rpi.edu/public/datasets/wild.tar.gz)
[wacv18]
- [Stanford Dogs Dataset](http://vision.stanford.edu/aditya86/ImageNetDogs/)
[cvpr11]
- [Oxford-IIIT Pet Dataset](http://www.robots.ox.ac.uk/~vgg/data/pets/)
[cvpr12]
- [Caltech-UCSD Birds 200](http://www.vision.caltech.edu/visipedia/CUB-200.html) [rough segmentation] [attributes]
- [Gold Standard Snapshot Serengeti Bounding Box Coordinates](https://dataverse.scholarsportal.info/dataset.xhtml?persistentId=doi:10.5683/SP/TPB5ID)

<a id="boundary_detectio_n_"></a>
## Boundary Detection

- [Semantic Boundaries Dataset and Benchmark](http://home.bharathh.info/pubs/codes/SBD/download.html)

<a id="static_segmentation_"></a>
## Static Segmentation

- [COCO - Common Objects in Context](http://cocodataset.org/#download)
- [Open Images](https://storage.googleapis.com/openimages/web/index.html)
- [ADE20K](https://groups.csail.mit.edu/vision/datasets/ADE20K/) [cvpr17]
- [SYNTHIA](http://synthia-dataset.net/download-2/) [cvpr16]
- [UC Berkeley Computer Vision Group - Contour Detection and Image Segmentation](https://www2.eecs.berkeley.edu/Research/Projects/CS/vision/grouping/resources.html)

<a id="video_segmentation_"></a>
## Video Segmentation

- [DAVIS: Densely Annotated VIdeo Segmentation](https://davischallenge.org/)
- [Mapillary Vistas Dataset](https://www.mapillary.com/dataset/vistas?pKey=0_xJqX3-c-KyTb90oG_8HQ&lat=20&lng=0&z=1.5) [street scenes] [semi-free]
- [BDD100K](https://bair.berkeley.edu/blog/2018/05/30/bdd/) [street scenes] [autonomous driving]
- [ApolloScape](http://apolloscape.auto/) [street scenes] [autonomous driving]
- [Cityscapes](https://www.cityscapes-dataset.com/) [street scenes] [instance-level]

<a id="classificatio_n_"></a>
## Classification

- [ImageNet Large Scale Visual Recognition Competition 2012](http://www.image-net.org/challenges/LSVRC/2012/)
- [Animals with Attributes 2](https://cvml.ist.ac.at/AwA2/)
- [CompCars Dataset](http://mmlab.ie.cuhk.edu.hk/datasets/comp_cars/index.html)
- [ObjectNet](https://objectnet.dev/) [only test set]

<a id="optical_flow_"></a>
## Optical Flow

- [Middlebury](http://vision.middlebury.edu/flow/data/)
- [MPI Sintel](http://sintel.is.tue.mpg.de/)
- [KITTI Flow](http://www.cvlibs.net/datasets/kitti/eval_scene_flow.php?benchmark=flow)

<a id="cod_e_"></a>
# Code

<a id="multi_object_tracking__2"></a>
## Multi Object Tracking
* [Globally-optimal greedy algorithms for tracking a variable number of objects](http://www.csee.umbc.edu/~hpirsiav/papers/tracking_release_v1.0.tar.gz) [cvpr11] [matlab] [[author]](https://www.csee.umbc.edu/~hpirsiav/)    
* [Continuous Energy Minimization for Multitarget Tracking](https://bitbucket.org/amilan/contracking) [cvpr11 / iccv11 / tpami  2014] [matlab]
* [Discrete-Continuous Energy Minimization for Multi-Target Tracking](http://www.milanton.de/files/software/dctracking-v1.0.zip) [cvpr12] [matlab] [[project]](http://www.milanton.de/dctracking/index.html)
* [The way they move: Tracking multiple targets with similar appearance](https://bitbucket.org/cdicle/smot/src/master/) [iccv13] [matlab]   
* [3D Traffic Scene Understanding from Movable Platforms](http://www.cvlibs.net/projects/intersection/) [[2d_tracking]](http://www.cvlibs.net/software/trackbydet/) [pami14/kit13/iccv13/nips11] [c++/matlab]
* [Multiple target tracking based on undirected hierarchical relation hypergraph](http://www.cbsr.ia.ac.cn/users/lywen/codes/MultiCarTracker.zip) [cvpr14] [C++] [[author]](http://www.cbsr.ia.ac.cn/users/lywen/)
* [Robust online multi-object tracking based on tracklet confidence and online discriminative appearance learning](https://drive.google.com/open?id=1YMqvkrVI6LOXRwcaUlAZTu_b2_5GmTAM) [cvpr14] [matlab] [(project)](https://sites.google.com/view/inuvision/research)
* [Learning to Track: Online Multi-Object Tracking by Decision Making](https://github.com/yuxng/MDP_Tracking) [iccv15] [matlab]
* [Joint Tracking and Segmentation of Multiple Targets](https://bitbucket.org/amilan/segtracking) [cvpr15] [matlab]
* [Multiple Hypothesis Tracking Revisited](http://rehg.org/mht/) [iccv15] [highest MT on MOT2015 among open source trackers] [matlab]
* [Simple Online and Realtime Tracking](https://github.com/abewley/sort) [icip 2016] [python]
* [Deep SORT : Simple Online Realtime Tracking with a Deep Association Metric](https://github.com/nwojke/deep_sort) [icip17] [python]
* [Combined Image- and World-Space Tracking in Traffic Scenes](https://github.com/aljosaosep/ciwt) [icra 2017] [c++]
* [High-Speed Tracking-by-Detection Without Using Image Information](https://github.com/bochinski/iou-tracker) [avss17] [python]    
* [Online Multi-Target Tracking with Recurrent Neural Networks](https://bitbucket.org/amilan/rnntracking/src/default/) [aaai17] [lua/torch7]    
* [Beyond Pixels: Leveraging Geometry and Shape Cues for Online Multi-Object Tracking](https://github.com/JunaidCS032/MOTBeyondPixels) [icra18] [matlab]    
* [Online Multi-Object Tracking with Dual Matching Attention Network](https://github.com/jizhu1023/DMAN_MOT) [eccv18] [matlab/tensorflow]    
* [Tracking by Animation: Unsupervised Learning of Multi-Object Attentive Trackers](https://github.com/zhen-he/tracking-by-animation) [cvpr19] [python/c++/pytorch]    
* [TrackR-CNN - Multi-Object Tracking and Segmentation](https://github.com/VisualComputingInstitute/TrackR-CNN) [cvpr19] [tensorflow] [[project]](https://www.vision.rwth-aachen.de/page/mots) 
* [Robust Multi-Modality Multi-Object Tracking](https://github.com/ZwwWayne/mmMOT) [iccv19] [pytorch]    

<a id="single_object_tracking__2"></a>
## Single Object Tracking
* [A collection of common tracking algorithms (2003-2012)](https://github.com/zenhacker/TrackingAlgoCollection) [c++/matlab]
* [SenseTime Research platform for single object tracking, implementing algorithms like SiamRPN and SiamMask](https://github.com/STVIR/pysot/) [pytorch]
* [In Defense of Color-based Model-free Tracking](https://github.com/jbhuang0604/CF2) [cvpr15] [c++]
* [Hierarchical Convolutional Features for Visual Tracking](https://github.com/jbhuang0604/CF2) [iccv15] [matlab]
* [Visual Tracking with Fully Convolutional Networks](https://github.com/scott89/FCNT) [iccv15] [matlab]
* [DeepTracking: Seeing Beyond Seeing Using Recurrent Neural Networks](https://github.com/pondruska/DeepTracking) [aaai16] [torch 7]
* [Learning Multi-Domain Convolutional Neural Networks for Visual Tracking](https://github.com/HyeonseobNam/MDNet) [cvpr16] [vot2015 winner] [matlab/matconvnet]
* [Beyond Correlation Filters: Learning Continuous Convolution Operators for Visual Tracking](https://github.com/martin-danelljan/Continuous-ConvOp) [eccv 2016] [matlab]
* [Fully-Convolutional Siamese Networks for Object Tracking](https://github.com/bertinetto/siamese-fc) [eccvw 2016] [matlab/matconvnet] [[project]](http://www.robots.ox.ac.uk/~luca/siamese-fc.html) [[pytorch]](https://github.com/huanglianghua/siamfc-pytorch) [[pytorch (only training)]](https://github.com/rafellerc/Pytorch-SiamFC)
* [DCFNet: Discriminant Correlation Filters Network for Visual Tracking](https://arxiv.org/abs/1704.04057) [ax1704] [[matlab/matconvnet]](https://github.com/foolwood/DCFNet/) [[pytorch]](https://github.com/foolwood/DCFNet_pytorch/)
* [End-to-end representation learning for Correlation Filter based tracking](https://arxiv.org/abs/1704.06036)
[cvpr17]
[[matlab/matconvnet]](https://github.com/bertinetto/cfnet) [[tensorflow/inference_only]](https://github.com/torrvision/siamfc-tf) [[project]](http://www.robots.ox.ac.uk/~luca/siamese-fc.html)
* [A simplified PyTorch implementation of Siamese networks for tracking: SiamFC, SiamRPN, SiamRPN++, SiamVGG, SiamDW, SiamRPN-VGG](https://github.com/zllrunning/SiameseX.PyTorch) [pytorch]
* [RATM: Recurrent Attentive Tracking Model](https://github.com/saebrahimi/RATM) [cvprw17] [python]
* [ROLO : Spatially Supervised Recurrent Convolutional Neural Networks for Visual Object Tracking](https://github.com/Guanghan/ROLO) [iscas 2017] [tensorfow]
* [ECO: Efficient Convolution Operators for Tracking](https://arxiv.org/abs/1611.09224)
[cvpr17]
[https://github.com/martin-danelljan/ECO[matlab]]()
[python/cuda](https://github.com/StrangerZhang/pyECO)
[pytorch](https://github.com/visionml/pytracking)
* [Action-Decision Networks for Visual Tracking with Deep Reinforcement Learning](https://github.com/ildoonet/tf-adnet-tracking) [cvpr17] [tensorflow]
* [Detect to Track and Track to Detect](https://github.com/feichtenhofer/Detect-Track) [iccv17] [matlab]
* High Performance Visual Tracking with Siamese Region Proposal Network [cvpr18] [[pytorch]](https://github.com/zkisthebest/Siamese-RPN) [[pytorch]](https://github.com/songdejia/Siamese-RPN-pytorch)  [[pytorch/no_train]](https://github.com/huanglianghua/siamrpn-pytorch) [[pytorch]](https://github.com/HelloRicky123/Siamese-RPN) 
* [Distractor-aware Siamese Networks for Visual Object Tracking](https://github.com/foolwood/DaSiamRPN) [eccv18] [vot18 winner] [pytorch]
* [Fast Online Object Tracking and Segmentation: A Unifying Approach (SiamMask)](https://github.com/foolwood/SiamMask) [cvpr19] [pytorch] [[project]](http://www.robots.ox.ac.uk/~qwang/SiamMask/)
* [PyTracking: A general python framework for training and running visual object trackers, based on PyTorch](https://github.com/visionml/pytracking) [ECO/ATOM/DiMP] [cvpr17/cvpr19/iccv19] [pytorch] 

<a id="gui_application___large_scale_tracking___animal_s_"></a>
### GUI Application / Large Scale Tracking / Animals
* [BioTracker An Open-Source Computer Vision Framework for Visual Animal Tracking](https://github.com/BioroboticsLab/biotracker_core)[opencv/c++]
* [Tracktor: Image‐based automated tracking of animal movement and behaviour](https://github.com/vivekhsridhar/tracktor)[opencv/c++]
* [MARGO (Massively Automated Real-time GUI for Object-tracking), a platform for high-throughput ethology](https://github.com/de-Bivort-Lab/margo)[matlab]
* [idtracker.ai: Tracking all individuals in large collectives of unmarked animals](https://gitlab.com/polavieja_lab/idtrackerai)
[tensorflow]
[[project]](https://idtracker.ai/)
    

<a id="video_detectio_n__2"></a>
## Video Detection
* [Flow-Guided Feature Aggregation for Video Object Detection](https://github.com/msracver/Flow-Guided-Feature-Aggregation)
[nips16 / iccv17]
[mxnet]
* [T-CNN: Tubelets with Convolution Neural Networks](https://github.com/myfavouritekk/T-CNN) [cvpr16] [python]  
* [TPN: Tubelet Proposal Network](https://github.com/myfavouritekk/TPN) [cvpr17] [python]
* [Deep Feature Flow for Video Recognition](https://github.com/msracver/Deep-Feature-Flow) [cvpr17] [mxnet]
* [Mobile Video Object Detection with Temporally-Aware Feature Maps](https://github.com/tensorflow/models/tree/master/research/lstm_object_detection) [cvpr18] [Google] [tensorflow]    

<a id="static_detection_and_matching_"></a>
## Static Detection and Matching

<a id="framework_s_"></a>
### Frameworks
+ [Tensorflow object detection API](https://github.com/tensorflow/models/tree/master/object_detection)
+ [Detectron](https://github.com/facebookresearch/Detectron)
+ [Open MMLab Detection Toolbox with PyTorch](https://github.com/open-mmlab/mmdetection)

<a id="region_proposal__1"></a>
### Region Proposal   
+ [MCG : Multiscale Combinatorial Grouping - Object Proposals and Segmentation](https://github.com/jponttuset/mcg)  [(project)](https://www2.eecs.berkeley.edu/Research/Projects/CS/vision/grouping/mcg/) [tpami16/cvpr14] [python]
+ [COB : Convolutional Oriented Boundaries](https://github.com/kmaninis/COB)  [(project)](http://www.vision.ee.ethz.ch/~cvlsegmentation/cob/) [tpami18/eccv16] [matlab/caffe]

<a id="fpn_"></a>
### FPN
* [Feature Pyramid Networks for Object Detection](https://github.com/unsky/FPN) [caffe/python]  

<a id="rcn_n__1"></a>
### RCNN
* [RFCN (author)](https://github.com/daijifeng001/r-fcn) [caffe/matlab]
* [RFCN-tensorflow](https://github.com/xdever/RFCN-tensorflow) [tensorflow]
* [PVANet: Lightweight Deep Neural Networks for Real-time Object Detection](https://github.com/sanghoon/pva-faster-rcnn) [intel] [emdnn16(nips16)]
* Mask R-CNN [[tensorflow]](https://github.com/CharlesShang/FastMaskRCNN) [[keras]](https://github.com/matterport/Mask_RCNN)
* [Light-head R-CNN](https://github.com/zengarden/light_head_rcnn) [cvpr18] [tensorflow]    
* [Evolving Boxes for Fast Vehicle Detection](https://github.com/Willy0919/Evolving_Boxes) [icme18] [caffe/python]
* [Cascade R-CNN (cvpr18)](http://www.svcl.ucsd.edu/publications/conference/2018/cvpr/cascade-rcnn.pdf) [[detectron]](https://github.com/zhaoweicai/Detectron-Cascade-RCNN) [[caffe]](https://github.com/zhaoweicai/cascade-rcnn)  
* [A MultiPath Network for Object Detection](https://arxiv.org/abs/1604.02135) [[torch]](https://github.com/facebookresearch/multipathnet) [bmvc16] [facebook]

<a id="ssd__1"></a>
### SSD
* [SSD-Tensorflow](https://github.com/ljanyst/ssd-tensorflow) [tensorflow]
* [SSD-Tensorflow (tf.estimator)](https://github.com/HiKapok/SSD.TensorFlow) [tensorflow]
* [SSD-Tensorflow (tf.slim)](https://github.com/balancap/SSD-Tensorflow) [tensorflow]
* [SSD-Keras](https://github.com/rykov8/ssd_keras) [keras]
* [SSD-Pytorch](https://github.com/amdegroot/ssd.pytorch) [pytorch]
* [Enhanced SSD with Feature Fusion and Visual Reasoning](https://github.com/CVlengjiaxu/Enhanced-SSD-with-Feature-Fusion-and-Visual-Reasoning) [nca18] [tensorflow]
* [RefineDet - Single-Shot Refinement Neural Network for Object Detection](https://github.com/sfzhang15/RefineDet) [cvpr18] [caffe]

<a id="yol_o__1"></a>
### YOLO  
+ [Darknet: Convolutional Neural Networks](https://github.com/pjreddie/darknet) [c/python]
+ [YOLO9000: Better, Faster, Stronger - Real-Time Object Detection. 9000 classes!](https://github.com/philipperemy/yolo-9000)  [c/python]
+ [Darkflow](https://github.com/thtrieu/darkflow) [tensorflow]
+ [Pytorch Yolov2 ](https://github.com/marvis/pytorch-yolo2) [pytorch]
+ [Yolo-v3 and Yolo-v2 for Windows and Linux](https://github.com/AlexeyAB/darknet) [c/python]
+ [YOLOv3 in PyTorch](https://github.com/ultralytics/yolov3) [pytorch]
+ [pytorch-yolo-v3 ](https://github.com/ayooshkathuria/pytorch-yolo-v3) [pytorch] [no training] [[tutorial]](https://blog.paperspace.com/how-to-implement-a-yolo-object-detector-in-pytorch/)
+ [YOLOv3_TensorFlow](https://github.com/wizyoung/YOLOv3_TensorFlow) [tensorflow]
+ [tensorflow-yolo-v3](https://github.com/mystic123/tensorflow-yolo-v3) [tensorflow slim]
+ [tensorflow-yolov3](https://github.com/YunYang1994/tensorflow-yolov3) [tensorflow slim]
+ [keras-yolov3](https://github.com/qqwweee/keras-yolo3) [keras]  

<a id="anchor_free__1"></a>
### Anchor Free

* [FoveaBox: Beyond Anchor-based Object Detector](https://github.com/taokong/FoveaBox) [ax1904] [pytorch/mmdetection]
* [Cornernet: Detecting objects as paired keypoints](https://github.com/princeton-vl/CornerNet) [ax1903/eccv18] [pytorch]
* [FCOS: Fully Convolutional One-Stage Object Detection](https://github.com/tianzhi0549/FCOS) [iccv19] [pytorch]
* [SNIPER: Efficient Multi-Scale Training/An Analysis of Scale Invariance in Object Detection-SNIP](https://github.com/mahyarnajibi/SNIPER) [cvpr18 / nips18/cvpr18]  [mxnet]

<a id="mis_c__2"></a>
### Misc
* [Relation Networks for Object Detection](https://github.com/msracver/Relation-Networks-for-Object-Detection) [cvpr18] [mxnet]
* [DeNet: Scalable Real-time Object Detection with Directed Sparse Sampling](https://github.com/lachlants/denet) [iccv17(poster)] [theano]
* [Multi-scale Location-aware Kernel Representation for Object Detection](https://github.com/Hwang64/MLKP) [cvpr18]  [caffe/python]

<a id="matchin_g_"></a>
### Matching  
+ [Matchnet](https://github.com/hanxf/matchnet)
+ [Stereo Matching by Training a Convolutional Neural Network to Compare Image Patches](https://github.com/jzbontar/mc-cnn)

<a id="boundary_detectio_n__1"></a>
### Boundary Detection  
+ [Holistically-Nested Edge Detection (HED) (iccv15)](https://github.com/s9xie/hed) [caffe]       
+ [Edge-Detection-using-Deep-Learning (HED)](https://github.com/Akuanchang/Edge-Detection-using-Deep-Learning) [tensorflow]
+ [Holistically-Nested Edge Detection (HED) in OpenCV](https://github.com/opencv/opencv/blob/master/samples/dnn/edge_detection.py) [python/c++]       
+ [Crisp Boundary Detection Using Pointwise Mutual Information (eccv14)](https://github.com/phillipi/crisp-boundaries) [matlab]

<a id="optical_flow__1"></a>
## Optical Flow
* [FlowNet 2.0: Evolution of Optical Flow Estimation with Deep Networks (cvpr17)](https://arxiv.org/abs/1612.01925) [[caffe]](https://github.com/lmb-freiburg/flownet2) [[pytorch/nvidia]](https://github.com/NVIDIA/flownet2-pytorch)
* [SPyNet: Spatial Pyramid Network for Optical Flow (cvpr17)](https://arxiv.org/abs/1702.02295) [[lua]](https://github.com/anuragranj/spynet) [[pytorch]](https://github.com/sniklaus/pytorch-spynet)
* [Guided Optical Flow Learning (cvprw17)](https://arxiv.org/abs/1702.02295) [[caffe]](https://github.com/bryanyzhu/GuidedNet) [[tensorflow]](https://github.com/bryanyzhu/deepOF)
* [Fast Optical Flow using Dense Inverse Search (DIS)](https://github.com/tikroeger/OF_DIS) [eccv16] [C++]
* [A Filter Formulation for Computing Real Time Optical Flow](https://github.com/jadarve/optical-flow-filter) [ral16] [c++/cuda - matlab,python wrappers]
* [PatchBatch - a Batch Augmented Loss for Optical Flow](https://github.com/DediGadot/PatchBatch) [cvpr16] [python/theano]
* [Piecewise Rigid Scene Flow](https://github.com/vogechri/PRSM) [iccv13/eccv14/ijcv15] [c++/matlab]
* [DeepFlow v2](https://arxiv.org/abs/1611.00850) [iccv13] [[c++/python/matlab]](https://github.com/zimenglan-sysu-512/deep-flow), [[project]](http://lear.inrialpes.fr/src/deepflow/)
* [An Evaluation of Data Costs for Optical Flow](https://github.com/vogechri/DataFlow) [gcpr13] [matlab]

<a id="instance_segmentation_"></a>
## Instance Segmentation
* [Fully Convolutional Instance-aware Semantic Segmentation](https://github.com/msracver/FCIS) [cvpr17] [coco16 winner] [mxnet]
* [Instance-aware Semantic Segmentation via Multi-task Network Cascades](https://github.com/daijifeng001/MNC) [cvpr16] [caffe] [coco15 winner]    
* [DeepMask/SharpMask](https://arxiv.org/abs/1603.08695) [nips15/eccv16] [facebook] [[torch]](https://github.com/facebookresearch/deepmask) [[tensorflow]](https://github.com/aby2s/sharpmask)  [[pytorch/deepmask]](https://github.com/foolwood/deepmask-pytorch/) 
* [Simultaneous Detection and Segmentation](https://github.com/bharath272/sds_eccv2014) [eccv14] [matlab] [[project]](https://www2.eecs.berkeley.edu/Research/Projects/CS/vision/shape/sds/)    
* [RetinaMask](https://github.com/chengyangfu/retinamask) [arxviv1901] [pytorch]
* [Mask Scoring R-CNN](https://github.com/zjhuang22/maskscoring_rcnn) [cvpr19] [pytorch]

<a id="framework_s__1"></a>
### Frameworks
* [Fast, modular reference implementation of Instance Segmentation and Object Detection algorithms in PyTorch](https://github.com/facebookresearch/maskrcnn-benchmark) [pytorch] [facebook]

<a id="semantic_segmentation_"></a>
## Semantic Segmentation
* [Learning from Synthetic Data: Addressing Domain Shift for Semantic Segmentation](https://github.com/swamiviv/LSD-seg) [cvpr18] [spotlight] [pytorch]
* [Few-shot Segmentation Propagation with Guided Networks](https://github.com/shelhamer/revolver) [ax1806] [pytorch] [incomplete]
* [Pytorch-segmentation-toolbox](https://github.com/speedinghzl/pytorch-segmentation-toolbox) [DeeplabV3 and PSPNet] [pytorch]
* [DeepLab](https://github.com/tensorflow/models/tree/master/research/deeplab) [tensorflow]
* [Auto-DeepLab](https://github.com/MenghaoGuo/AutoDeeplab) [pytorch]
* [DeepLab v3+](https://github.com/jfzhang95/pytorch-deeplab-xception) [pytorch]
* [FastFCN: Rethinking Dilated Convolution in the Backbone for Semantic Segmentation](https://github.com/wuhuikai/FastFCN)[ax1903][[project]](http://wuhuikai.me/FastFCNProject/) [pytorch]

<a id="video_segmentation__1"></a>
## Video Segmentation
* [Improving Semantic Segmentation via Video Prediction and Label Relaxation
](https://github.com/NVIDIA/semantic-segmentation) [cvpr19] [pytorch] [nvidia]

<a id="autoencoder_s_"></a>
## Autoencoders
* [β-VAE: Learning Basic Visual Concepts with a Constrained Variational Framework](https://openreview.net/forum?id=Sy2fzU9gl) [iclr17] [deepmind] [[tensorflow]](https://github.com/miyosuda/disentangled_vae) [[tensorflow]](https://github.com/LynnHo/VAE-Tensorflow) [[pytorch]](https://github.com/1Konny/Beta-VAE)
* [Disentangling by Factorising](https://github.com/1Konny/FactorVAE) [ax1806] [pytorch]   

<a id="classificatio_n__1"></a>
## Classification
* [Learning Efficient Convolutional Networks Through Network Slimming](https://github.com/miyosuda/async_deep_reinforce) [iccv17] [pytorch]
* Deep RL
* [Asynchronous Methods for Deep Reinforcement Learning ](https://github.com/miyosuda/async_deep_reinforce)

<a id="mis_c__3"></a>
## Misc
* [Deformable Convolutional Networks](https://github.com/msracver/Deformable-ConvNets)
* [RNNexp](https://github.com/asheshjain399/RNNexp)

<a id="collections_"></a>
# Collections

<a id="dataset_s__1"></a>
## Datasets

* [Awesome Public Datasets](https://github.com/awesomedata/awesome-public-datasets) 
* [List of traffic surveillance datasets](https://github.com/gustavovelascoh/traffic-surveillance-dataset) 
* [Machine learning datasets: A list of the biggest machine learning datasets from across the web](https://www.datasetlist.com/) 
* [Labeled Information Library of Alexandria: Biology and Conservation](http://lila.science/datasets)
[[other conservation data sets]](http://lila.science/otherdatasets) 
* [THOTH: Data Sets & Images](https://thoth.inrialpes.fr/data) 
* [Google AI Datasets](https://ai.google/tools/datasets/) 
* [Google Cloud Storage public datasets](https://cloud.google.com/storage/docs/public-datasets/) 
* [Microsoft Research Open Data](https://msropendata.com/) 
* [Earth Engine Data Catalog](https://developers.google.com/earth-engine/datasets/catalog/) 
* [Registry of Open Data on AWS](https://registry.opendata.aws/) 
* [Kaggle Datasets](https://www.kaggle.com/datasets) 

<a id="static_detectio_n__2"></a>
## Static Detection
- [Object Detection with Deep Learning](https://handong1587.github.io/deep_learning/2015/10/09/object-detection.html)

<a id="single_object_tracking__3"></a>
## Single Object Tracking
- [List of deep learning based tracking papers](https://github.com/handong1587/handong1587.github.io/blob/master/_posts/deep_learning/2015-10-09-tracking.md)
- [List of single object trackers with results on OTB](https://github.com/foolwood/benchmark_results)
- [Collection of Correlation Filter based trackers with links to papers, codes, etc](https://github.com/lukaswals/cf-trackers)
- [VOT2018 Trackers repository](http://www.votchallenge.net/vot2018/trackers.html)
- [CUHK Datasets](http://mmlab.ie.cuhk.edu.hk.login.ezproxy.library.ualberta.ca/datasets.html)
    
<a id="multi_object_tracking__3"></a>
## Multi Object Tracking

* [List of multi object tracking papers](http://perception.yale.edu/Brian/refGuides/MOT.html)   
* [A collection of Multiple Object Tracking (MOT) papers in recent years, with notes](https://github.com/huanglianghua/mot-papers)  
* [Papers with Code : Multiple Object Tracking](https://paperswithcode.com/task/multiple-object-tracking/codeless)  

<a id="segmentatio_n_"></a>
## Segmentation

* [Segmentation Papers and Code](https://handong1587.github.io/deep_learning/2015/10/09/segmentation.html)  
* [Segmentation.X : Papers and Benchmarks about semantic segmentation, instance segmentation, panoptic segmentation and video segmentation](https://github.com/wutianyiRosun/Segmentation.X)  

<a id="deep_compressed_sensin_g_"></a>
## Deep Compressed Sensing

* [Reproducible Deep Compressive Sensing](https://github.com/AtenaKid/Reproducible-Deep-Compressive-Sensing)  

<a id="mis_c__4"></a>
## Misc 

* [Papers With Code : the latest in machine learning](https://paperswithcode.com/)
* [Awesome Deep Ecology](https://github.com/patrickcgray/awesome-deep-ecology)
* [List of Matlab frameworks, libraries and software](https://github.com/uhub/awesome-matlab)
* [Face Recognition](https://github.com/ChanChiChoi/awesome-Face_Recognition)
* [A Month of Machine Learning Paper Summaries](https://medium.com/@hyponymous/a-month-of-machine-learning-paper-summaries-ddd4dcf6cfa5)

<a id="tutorials_"></a>
# Tutorials
<a id="static_detectio_n__3"></a>
## Static Detection
* [Deep Learning for Object Detection: A Comprehensive Review](https://towardsdatascience.com/deep-learning-for-object-detection-a-comprehensive-review-73930816d8d9)
* [Review of Deep Learning Algorithms for Object Detection](https://medium.com/comet-app/review-of-deep-learning-algorithms-for-object-detection-c1f3d437b852)  
* [A Simple Guide to the Versions of the Inception Network](https://towardsdatascience.com/a-simple-guide-to-the-versions-of-the-inception-network-7fc52b863202)    
* [R-CNN, Fast R-CNN, Faster R-CNN, YOLO - Object Detection Algorithms](https://towardsdatascience.com/r-cnn-fast-r-cnn-faster-r-cnn-yolo-object-detection-algorithms-36d53571365e)
* [A gentle guide to deep learning object detection](https://www.pyimagesearch.com/2018/05/14/a-gentle-guide-to-deep-learning-object-detection/)
* [The intuition behind RetinaNet](https://medium.com/@14prakash/the-intuition-behind-retinanet-eb636755607d)
* [YOLO—You only look once, real time object detection explained](https://towardsdatascience.com/yolo-you-only-look-once-real-time-object-detection-explained-492dc9230006)
* [Understanding Feature Pyramid Networks for object detection (FPN)](https://medium.com/@jonathan_hui/understanding-feature-pyramid-networks-for-object-detection-fpn-45b227b9106c)
* [Fast object detection with SqueezeDet on Keras](https://medium.com/omnius/fast-object-detection-with-squeezedet-on-keras-5cdd124b46ce)
* [Region of interest pooling explained](https://deepsense.ai/region-of-interest-pooling-explained/)

<a id="video_detectio_n__3"></a>
## Video Detection
* [How Microsoft Does Video Object Detection - Unifying the Best Techniques in Video Object Detection Architectures in a Single Model](https://medium.com/nurture-ai/how-microsoft-does-video-object-detection-unifying-the-best-techniques-in-video-object-detection-b78b63e3f1d8)

<a id="instance_segmentation__1"></a>
## Instance Segmentation
* [Splash of Color: Instance Segmentation with Mask R-CNN and TensorFlow](https://engineering.matterport.com/splash-of-color-instance-segmentation-with-mask-r-cnn-and-tensorflow-7c761e238b46)
* [Simple Understanding of Mask RCNN](https://medium.com/@alittlepain833/simple-understanding-of-mask-rcnn-134b5b330e95)
* [Learning to Segment](https://research.fb.com/blog/2016/08/learning-to-segment/)
* [Analyzing The Papers Behind Facebook's Computer Vision Approach](https://adeshpande3.github.io/Analyzing-the-Papers-Behind-Facebook's-Computer-Vision-Approach/)
* [Review: MNC — Multi-task Network Cascade, Winner in 2015 COCO Segmentation](https://towardsdatascience.com/review-mnc-multi-task-network-cascade-winner-in-2015-coco-segmentation-instance-segmentation-42a9334e6a34)
* [Review: FCIS — Winner in 2016 COCO Segmentation](https://towardsdatascience.com/review-fcis-winner-in-2016-coco-segmentation-instance-segmentation-ee2d61f465e2)
* [Review: InstanceFCN — Instance-Sensitive Score Maps](https://towardsdatascience.com/review-instancefcn-instance-sensitive-score-maps-instance-segmentation-dbfe67d4ee92)

<a id="deep_rl_"></a>
## Deep RL
* [Deep Reinforcement Learning: Pong from Pixels](http://karpathy.github.io/2016/05/31/rl/)
* [Demystifying Deep Reinforcement Learning](https://www.intelnervana.com/demystifying-deep-reinforcement-learning/)

<a id="autoencoder_s__1"></a>
## Autoencoders
* [Guide to Autoencoders](https://yaledatascience.github.io/2016/10/29/autoencoders.html)
* [Applied Deep Learning - Part 3: Autoencoders](https://towardsdatascience.com/applied-deep-learning-part-3-autoencoders-1c083af4d798)
* [Denoising Autoencoders](http://deeplearning.net/tutorial/dA.html)
* [Stacked Denoising Autoencoders](https://skymind.ai/wiki/stacked-denoising-autoencoder)
* [A Gentle Introduction to LSTM Autoencoders](https://machinelearningmastery.com/lstm-autoencoders/)
* [Variational Autoencoder in TensorFlow](https://jmetzen.github.io/2015-11-27/vae.html)
* [Variational Autoencoders with Tensorflow Probability Layers](https://medium.com/tensorflow/variational-autoencoders-with-tensorflow-probability-layers-d06c658931b7)
