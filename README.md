Refer to [SpyderXu](https://github.com/SpyderXu/multi-object-tracking-paper-list) with some supplements

# 3D&Multi-Modality

|                             Name                             |                            Source                            | Publication |     Notes      |
| :----------------------------------------------------------: | :----------------------------------------------------------: | :---------: | :------------: |
| Joint 3D Tracking and Forecasting with Graph Neural Network and Diversity Sampling | [[pdf]](https://arxiv.org/abs/2003.07847) [[code]](https://github.com/xinshuoweng/GNNTrkForecast) |    arxiv    | GNNTrkForecast |
| Graph Neural Network for 3D Multi-Object Tracking with Multi-Feature Learning | [[pdf]](https://arxiv.org/abs/2006.07327) [[code]](https://github.com/xinshuoweng/GNN3DMOT) |  CVPR2020   |    GNN3DMOT    |
|         Robust Multi-Modality Multi-Object Tracking          | [[pdf]](https://arxiv.org/abs/1909.03850) [[code]](https://github.com/ZwwWayne/mmMOT#) |  ICCV2019   |     mmMOT      |
|           A baseline for 3D Multi-Object Tracking            | [[pdf]](https://arxiv.xilesou.top/pdf/1907.03961) [[code]](https://github.com/xinshuoweng/AB3DMOT) |    arXiv    |       -        |
| 3D Object Detection and Tracking Based on Streaming Data | [[pdf]](https://arxiv.org/pdf/2009.06169.pdf)  |    ICRA2020    | - |
| Factor Graph based 3D Multi-Object Tracking in Point Clouds | [[pdf]](https://arxiv.org/pdf/2008.05309)  [[video]](https://www.youtube.com/watch?v=mvZmli4jrZQ)|    IROS2020    | - |
| DeepTracking-Net: 3D Tracking with Unsupervised Learning of Continuous Flow | [[pdf]](https://arxiv.org/pdf/2006.13848) |    arXiv    | 2020.6.24 |
| Center-based 3D Object Detection and Tracking | [[pdf]](https://arxiv.org/pdf/2006.11275) [[code]](https://github.com/tianweiy/CenterPoint)|    arXiv(2020)    | rank1 on nuscene |
| 1st Place Solutions for Waymo Open Dataset Challenges -- 2D and 3D Tracking | [[pdf]](https://arxiv.org/pdf/2006.15506)| arXiv| rank1 on Waymo|
|PV-RCNN with simple KF tracker | [[code]](https://github.com/sshaoshuai/PCDet) |-| rank2 on Waymo |
| Probabilistic 3D Multi-Object Tracking for Autonomous Driving | [[pdf]](https://arxiv.org/abs/2001.05673)| arXiv2020| rank3 on Waymo|


# 3D TrackingDataSet
[nuscenes](https://www.nuscenes.org/): nuScenes包含1000个序列，其中700、150、150个分别用于训练、验证和测试。每个序列大约20秒长，激光雷达频率20 FPS。数据集为每个激光雷达帧提供校准后的车辆姿态信息，但仅每10帧(0.5秒)提供框注释。总共有28k、6k、6k带标签的帧分别用于训练、验证和测试。


[Waymo](https://waymo.com/open/): Waymo 数据集包含 3000 段驾驶记录，时长共 16.7 小时，平均每段长度约为 20 秒。整个数据集一共包含 60 万帧，共有大约 2500 万 3D 边界框、2200 万 2D 边界框。


[JRDB](https://jrdb.stanford.edu/dataset/about): 最大的用于2D-3D行人跟踪的数据集，采集自5个立体圆柱形360度RGB相机和2个激光雷达传感器采集的超过60K帧(64分钟)的传感器, 包含54个序列，分别来自室内和室外的不同位置， 超过3500条轨迹。

# 2D Online
|                             Name                             |                            Source                            | Publication | Notes  |
| :----------------------------------------------------------: | :----------------------------------------------------------: | :---------: | :----: |
| Simultaneous Detection and Tracking with Motion Modelling for Multiple Object Tracking | [[pdf]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123690613.pdf)| ECCV2020| - |
| Towards Real-Time Multi-Object Tracking | [[pdf]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123560103.pdf) [[code]](https://github.com/Zhongdao/Towards-Realtime-MOT)| ECCV2020 | - |
| Tracking Objects as Points | [[pdf]](https://arxiv.org/pdf/2004.01177.pdf) [[code]](https://github.com/xingyizhou/CenterTrack)| ECCV 2020 | CenterTrack,rank2 on KITTI |
| Chained-Tracker: Chaining Paired Attentive Regression Results for End-to-End Joint Multiple-Object Detection and Tracking | [[pdf]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123490137.pdf)| ECCV2020| - |
| Segment as Points for Efficient Online Multi-Object Tracking and Segmentation | [[pdf]](https://arxiv.org/pdf/2007.01550) [[code]](https://github.com/detectRecog/PointTrack) |  ECCV2020 oral   |  mots|
| MAT: Motion-Aware Multi-Object Tracking | [[pdf]](https://arxiv.org/pdf/2009.04794.pdf)  |  arXiv   | 2020.9.18 |
| Adopting Tubes to Track Multi-Object in a One-Step Training Model | [[pdf]](https://arxiv.org/pdf/2006.05683.pdf) [[code]](https://github.com/BoPang1996/TubeTK) |  CVPR2020   | TubeTK |
| Joint Detection and Multi-Object Tracking with Graph Neural Networks |          [[pdf]](https://arxiv.org/abs/2006.13164)           | arxiv(2020) |     JDMOT_GNN      |
|         Graph Networks for Multiple Object Tracking          | [[pdf]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9093347) [[code]](https://github.com/yinizhizhu/GNMOT) |  WACV2020   |       GNMOT        |
| Deep association: End-to-end graph-based learning for multiple object tracking with conv-graph neural network | [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3323873.3325010)  |  ICMR2019   |        DAN         |
| SQE: a Self Quality Evaluation Metric for Parameters Optimization in Multi-Object Tracking |          [[pdf]](https://arxiv.org/abs/2004.07472)           | arxiv(2020) |        SQE         |
| Autoregressive Trajectory Inpainting and Scoring for Tracking |          [[pdf]](https://arxiv.org/abs/2004.07482)           |  CVPR2020   |       ArTIST       |
|       Multiple Object Tracking with Siamese Track-RCNN       |          [[pdf]](https://arxiv.org/abs/2004.07786)           | arxiv(2020) | Siamese Track-RCNN |
|       Online Single Stage Joint Detection and Tracking       |          [[pdf]](https://arxiv.org/abs/2003.13870)           |  CVPR2020   |    RetinaTrack     |
|         A Simple Baseline for Multi-Object Tracking          | [[pdf]](http://arxiv.org/abs/2004.01888)[[code]](https://github.com/ifzhang/FairMOT) | arXiv(2019) |      FairMOT       |
|                  Tracking Objects as Points                  | [[pdf]](http://arxiv.org/abs/2004.01177) [[code]](https://github.com/xingyizhou/CenterTrack) | arXiv(2019) |    CenterTrack     |
| Refinements in Motion and Appearance for Online Multi-Object Tracking | [[pdf]](https://arxiv.org/abs/2003.07177) [[code]](https://github.com/nightmaredimple/libmot) | arXiv(2019) |        MIFT        |
|        Multiple Object Tracking by Flowing and Fusing        |          [[pdf]](https://arxiv.org/abs/2001.11180)           | arXiv(2019) |        FFT         |
| A Unified Object Motion and Affinity Model for Online Multi-Object Tracking | [[pdf]](https://arxiv.org/abs/2003.11291)[[code]](https://github.com/yinjunbo/UMA-MOT) |  CVPR2020   |        UMA         |
| DeepMOT:A Differentiable Framework for Training Multiple Object Trackers | [[pdf]](https://arxiv.org/pdf/1906.06618.pdf) [[code]](https://gitlab.inria.fr/yixu/deepmot) |  CVPR2020   |      DeepMOT       |
| Online multiple pedestrian tracking using deep temporal appearance matching association | [[pdf]](https://arxiv.org/pdf/1906.06618.pdf) [[code]](https://github.com/yyc9268/Deep-TAMA) | arXiv(2019) |     DD_TAMA19      |
| Spatial-temporal relation networks for multi-object tracking | [[pdf]](http://openaccess.thecvf.com/content_ICCV_2019/papers/Xu_Spatial-Temporal_Relation_Networks_for_Multi-Object_Tracking_ICCV_2019_paper.pdf) |  ICCV2019   |        STRN        |
|           Towards Real-Time Multi-Object Tracking            | [[pdf]](https://arxiv.org/pdf/1909.12605v1.pdf) [[code]](https://github.com/Zhongdao/Towards-Realtime-MOT) | arXiv(2019) |    JDE(private)    |
| Multi-object tracking with multiple cues and switcher-aware classification |          [[pdf]](https://arxiv.org/abs/1901.06129)           | arXiv(2019) |        LSST        |
| FAMNet: Joint learning of feature, affinity and multi-dimensional assignment for online multiple object tracking | [[pdf]](http://openaccess.thecvf.com/content_ICCV_2019/papers/Chu_FAMNet_Joint_Learning_of_Feature_Affinity_and_Multi-Dimensional_Assignment_for_ICCV_2019_paper.pdf) |  ICCV2019   |       FAMNet       |
| Online multi-object tracking with instance-aware tracker and dynamic model refreshment |      [[pdf]](https://arxiv.xilesou.top/pdf/1902.08231)       |  WACV2019   |        KCF         |
|             Tracking without bells and whistles              | [[pdf]](https://arxiv.org/pdf/1903.05625.pdf) [[code]](https://github.com/phil-bergmann/tracking_wo_bnw) |  ICCV2019   |      Tracktor      |
|         MOTS: Multi-Object Tracking and Segmentation         | [[pdf]](https://www.vision.rwth-aachen.de/media/papers/mots-multi-object-tracking-and-segmentation/MOTS.pdf) [[code]](https://github.com/VisualComputingInstitute/TrackR-CNN/tree/master) |  CVPR2019   |    Track R-CNN     |
| Eliminating Exposure Bias and Metric Mismatch in Multiple Object Tracking | [[pdf]](http://openaccess.thecvf.com/content_CVPR_2019/papers/Maksai_Eliminating_Exposure_Bias_and_Metric_Mismatch_in_Multiple_Object_Tracking_CVPR_2019_paper.pdf) [[code]](https://github.com/VisualComputingInstitute/TrackR-CNN/tree/master) |  CVPR2019   |     SAS_MOT17      |
|      Deep affinity network for multiple object tracking      | [[pdf]](https://arxiv.xilesou.top/pdf/1810.11780) [[code]](https://github.com/shijieS/SST) | PAMI(2019)  |        DAN         |
| Recurrent autoregressive networks for online multi-object tracking |      [[pdf]](https://arxiv.xilesou.top/pdf/1711.02741)       |  WACV2018   |        RAN         |
| Real-time multiple people tracking with deeply learned candidate selection and person re-identification | [[pdf]](https://www.researchgate.net/publication/326224594_Real-time_Multiple_People_Tracking_with_Deeply_Learned_Candidate_Selection_and_Person_Re-identification) [[code]](https://github.com/longcw/MOTDT) |  ICME2018   |       MOTDT        |
| Online multi-object tracking with dual matching attention networks | [[pdf]](http://openaccess.thecvf.com/content_ECCV_2018/papers/Ji_Zhu_Online_Multi-Object_Tracking_ECCV_2018_paper.pdf) [[code]](https://github.com/jizhu1023/DMAN_MOT) |  ECCV2018   |        DMAN        |
| Extending IOU Based Multi-Object Tracking by Visual Information | [[pdf]](http://elvera.nue.tu-berlin.de/typo3/files/1547Bochinski2018.pdf) [[code]](https://github.com/bochinski/iou-tracker) |  AVSS2018   |       V-IOU        |
| Online Multi-target Tracking using Recurrent Neural Networks | [[pdf]](http://www.milanton.de/files/aaai2017/aaai2017-anton-rnntracking.pdf) [[code]](https://bitbucket.org/amilan/rnntracking) |  AAAI2017   |      MOT-RNN       |
|             Detect to Track and Track to Detect              | [[pdf]](http://openaccess.thecvf.com/content_ICCV_2017/papers/Feichtenhofer_Detect_to_Track_ICCV_2017_paper.pdf) [[code]](https://github.com/feichtenhofer/Detect-Track) |  ICCV2017   |    D&T(private)    |
| Online multi-object tracking using CNN-based single object tracker with spatial-temporal attention mechanism | [[pdf]](http://openaccess.thecvf.com/content_ICCV_2017/papers/Chu_Online_Multi-Object_Tracking_ICCV_2017_paper.pdf) |  ICCV2017   |        STAM        |
| Tracking the untrackable: Learning to track multiple cues with long-term dependencies |          [[pdf]](https://arxiv.org/abs/1701.01909)           |  ICCV2017   |        AMIR        |
| Simple online and realtime tracking with a deep association metric | [[pdf]](https://arxiv.org/abs/1703.07402) [[code]](https://github.com/nwojke/deep_sort) |  ICIP2017   |      DeepSort      |
| High-speed tracking-by-detection without using image information | [[pdf]](http://elvera.nue.tu-berlin.de/files/1517Bochinski2017.pdf) [[code]](https://github.com/bochinski/iou-tracker) |  AVSS2017   |    IOU Tracker     |
|             Simple online and realtime tracking              | [[pdf]](https://arxiv.org/abs/1602.00763) [[code]](https://github.com/abewley/sort) |  ICIP2016   |        Sort        |
| Temporal dynamic appearance modeling for online multi-person tracking |         [[pdf]](https://arxiv.org/pdf/1510.02906v1)          | CVIU(2016)  |        TDAM        |
| Online multi-object tracking via structural constraint event aggregation | [[pdf]](http://openaccess.thecvf.com/content_cvpr_2016/papers/Yoon_Online_Multi-Object_Tracking_CVPR_2016_paper.pdf) |  CVPR2016   |        SCEA        |
| Online Multi-Object Tracking Via Robust Collaborative Model and Sample Selection | [[pdf]](https://users.encs.concordia.ca/~rcmss/include/Papers/CVIU2016.pdf) [[code]](https://users.encs.concordia.ca/~rcmss/) |  CVIU2016   |       RCMSS        |
| Learning to Track: Online Multi-Object Tracking by Decision Making | [[pdf]](http://openaccess.thecvf.com/content_iccv_2015/papers/Xiang_Learning_to_Track_ICCV_2015_paper.pdf) [[code]](http://cvgl.stanford.edu/projects/MDP_tracking/) |  ICCV2015   |        MDP         |
| Learning to Divide and Conquer for Online Multi-Target Tracking | [[pdf]](http://ieeexplore.ieee.org/document/7410854/) [[code]](https://github.com/francescosolera/LDCT) |  ICCV2015   |        LDCT        |
| Robust online multi-object tracking based on tracklet confidence and online discriminative appearance learning | [[pdf]](https://www.cv-foundation.org/openaccess/content_cvpr_2014/papers/Bae_Robust_Online_Multi-Object_2014_CVPR_paper.pdf) [[code]](https://cvl.gist.ac.kr/project/cmot.html) |  CVPR2014   |        CMOT        |
| The Way They Move: Tracking Targets with Similar Appearance  | [[pdf]](https://www.cv-foundation.org/openaccess/content_iccv_2013/papers/Dicle_The_Way_They_2013_ICCV_paper.pdf) [[code]](https://bitbucket.org/cdicle/smot) |  ICCV2013   |        SMOT        |
|      Online Multi-Person Tracking by Tracker Hierarchy       | [[pdf]](https://github.com/SpyderXu/multi-object-tracking-paper-list/blob/master) [[code]](http://cs-people.bu.edu/jmzhang/tracker_hierarchy/Tracker_Hierarchy.htm) |  AVSS2012   |       OMPTTH       |



# Batch
|                             Name                             |                            Source                            | Publication | Notes |
| :----------------------------------------------------------: | :----------------------------------------------------------: | :---------: | :---: |
| Lifted Disjoint Paths with Application in Multiple Object Tracking | [[pdf]](https://arxiv.org/abs/2006.14550) [[code]](https://github.com/AndreaHor/LifT_Solver) |  ICML2020   | Lif_T |
|  Learning non-uniform hypergraph for multi-object tracking   | [[pdf]](https://wvvw.aaai.org/ojs/index.php/AAAI/article/download/4928/4801) |  AAAI2019   |     NT     |
|    Learning a Neural Solver for Multiple Object Tracking     | [[pdf]](https://arxiv.xilesou.top/pdf/1912.07515) [[code]](https://github.com/selflein/GraphNN-Multi-Object-Tracking) |  CVPR2020   | MPNTracker |
|               Deep learning of graph matching                | [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Zanfir_Deep_Learning_of_CVPR_2018_paper.pdf) |  CVPR2018   | 深度图匹配 |
| muSSP: Efficient Min-cost Flow Algorithm for Multi-object Tracking | [[pdf]](http://papers.nips.cc/paper/8334-mussp-efficient-min-cost-flow-algorithm-for-multi-object-tracking) [[code]](https://github.com/yu-lab-vt/muSSP) | NIPS(2019)  |   muSSP    |
| Exploit the connectivity: Multi-object tracking with trackletnet | [[pdf]](https://arxiv.org/pdf/1909.12605v1.pdf) [[code]](https://github.com/GaoangW/TNT) | ACM mm 2019 |  TNT(eTC)  |
|   Multiple people tracking using body and joint detections   | [[pdf]](http://openaccess.thecvf.com/content_CVPRW_2019/papers/BMTT/Henschel_Multiple_People_Tracking_Using_Body_and_Joint_Detections_CVPRW_2019_paper.pdf) |  CVPRW2019  |   JBNOT    |
| Aggregate Tracklet Appearance Features for Multi-Object Tracking |  [[pdf]](https://www.sci-hub.shop/10.1109/lsp.2019.2940922)  |  SPL(2019)  |    NOTA    |
|               Customized multi-person tracker                | [[pdf]](https://is.mpg.de/uploads_file/attachment/attachment/469/0509.pdf) |  ACCV2018   |    HCC     |
| Multi-object tracking with neural gating using bilinear lstm |      [[pdf]](https://arxiv.xilesou.top/pdf/1810.11780)       |  ECCV2018   | MHT_bLSTM  |
| Trajectory Factory: Tracklet Cleaving and Re-connection by Deep Siamese Bi-GRU for Multiple Object Tracking |          [[pdf]](https://arxiv.org/abs/1804.04555)           |  ICME2018   |    GCRE    |
| Multiple People Tracking with Lifted Multicut and Person Re-identification | [[pdf]](http://openaccess.thecvf.com/content_cvpr_2017/papers/Tang_Multiple_People_Tracking_CVPR_2017_paper.pdf) |  CVPR2017   |    LMP     |
|         Deep network flow for multi-object tracking          | [[pdf]](http://openaccess.thecvf.com/content_cvpr_2017/papers/Schulter_Deep_Network_Flow_CVPR_2017_paper.pdf) |  CVPR2017   |     -      |
|   Non-markovian globally consistent multi-object tracking    | [[pdf]](http://openaccess.thecvf.com/content_ICCV_2017/papers/Maksai_Non-Markovian_Globally_Consistent_ICCV_2017_paper.pdf) [[code]](https://github.com/maksay/ptrack_cpp) |  ICCV2017   |     -      |
| Multi-Object Tracking with Quadruplet Convolutional Neural Networks | [[pdf]](http://openaccess.thecvf.com/content_cvpr_2017/papers/Son_Multi-Object_Tracking_With_CVPR_2017_paper.pdf) |  CVPR2017   |  Quad-CNN  |
|  Enhancing detection model for multiple hypothesis tracking  | [[pdf]](http://openaccess.thecvf.com/content_cvpr_2017_workshops/w34/papers/Chen_Enhancing_Detection_Model_CVPR_2017_paper.pdf) |  CVPRW2017  |    EDMT    |
| POI: Multiple Object Tracking with High Performance Detection and Appearance Feature |      [[pdf]](https://arxiv.xilesou.top/pdf/1610.06136)       |  ECCV2016   |    KNDT    |
|            Multiple hypothesis tracking revisited            | [[pdf]](https://www.cc.gatech.edu/~ckim314/papers/MHTR_ICCV2015.pdf) [[code]](http://rehg.org/mht/) |  ICCV2015   |  MHT-DAM   |
| Near-Online Multi-target Tracking with Aggregated Local Flow Descriptor | [[pdf]](http://openaccess.thecvf.com/content_iccv_2015/papers/Choi_Near-Online_Multi-Target_Tracking_ICCV_2015_paper.pdf) |  ICCV2015   |    NOMT    |
|   On Pairwise Costs for Network Flow Multi-Object Tracking   | [[pdf]](https://arxiv.org/abs/1408.3304) [[code]](http://www.di.ens.fr/willow/research/flowtrack/) |  CVPR2015   |     -      |
| Multiple Target Tracking Based on Undirected Hierarchical Relation Hypergraph | [[pdf]](http://www.cbsr.ia.ac.cn/users/lywen/papers/CVPR2014_HyperGraphMultiTargetsTracker.pdf) [[code]](http://www.cbsr.ia.ac.cn/users/lywen/) |  CVPR2014   |    H2T     |
|   Continuous Energy Minimization for Multi-Target Tracking   | [[pdf]](http://www.milanton.de/files/pami2014/pami2014-anton.pdf) [[code]](http://www.milanton.de/contracking/) |  CVPR2014   |    CEM     |
| GMCP-Tracker: Global Multi-object Tracking Using Generalized Minimum Clique Graphs | [[pdf]](http://crcv.ucf.edu/papers/eccv2012/GMCP-Tracker_ECCV12.pdf) [[code]](http://crcv.ucf.edu/projects/GMCP-Tracker/) |  ECCV2012   |    GMCP    |
| Multiple Object Tracking using K-Shortest Paths Optimization | [[pdf]](https://cvlab.epfl.ch/files/content/sites/cvlab2/files/publications/publications/2011/BerclazFTF11.pdf) [[code]](https://cvlab.epfl.ch/software/ksp) |  PAMI2011   |    KSP     |
| Global data association for multi-object tracking using network flows | [[pdf]](https://inc.ucsd.edu/mplab/wordpress/wp-content/uploads/CVPR2008/Conference/data/papers/244.pdf) [[code]](https://github.com/nwojke/mcf) |  CVPR2008   |     -      |

# MTMC

|                             Name                             |                            Source                            |    Publication    |         Notes         |
| :----------------------------------------------------------: | :----------------------------------------------------------: | :---------------: | :-------------------: |
| Locality Aware Appearance Metric for Multi-Target Multi-Camera Tracking | [[pdf]](https://arxiv.org/abs/1911.12037) [code](https://github.com/hou-yz/DeepCC-local) | CVPR2019 Workshop |         LAAM          |
| CityFlow: A City-Scale Benchmark for Multi-Target Multi-Camera Vehicle Tracking and Re-Identification | [[pdf]](http://openaccess.thecvf.com/content_CVPR_2019/papers/Tang_CityFlow_A_City-Scale_Benchmark_for_Multi-Target_Multi-Camera_Vehicle_Tracking_and_CVPR_2019_paper.pdf) |     CVPR2019      |       CityFlow        |
| Features for multi-target multi-camera tracking and re-identification | [[pdf]](https://arxiv.org/pdf/1803.10859.pdf) [[code]](https://github.com/SamvitJ/Duke-DeepCC) |     CVPR2018      |     DeepCC(MTMC)      |
| Rolling Shutter and Radial Distortion Are Features for High Frame Rate Multi-Camera Tracking | [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Bapat_Rolling_Shutter_and_CVPR_2018_paper.pdf) |     CVPR2018      |           -           |
| Towards a Principled Integration of Multi-Camera Re-Identification andTracking through Optimal Bayes Filters | [[pdf]](https://arxiv.org/pdf/1705.04608.pdf) [[code]](https://github.com/VisualComputingInstitute/towards-reid-tracking) |     CVPR2017      | towards-reid-tracking |



## Review

[Multiple Object Tracking: A Literature Review](http://pdfs.semanticscholar.org/3dff/acda086689c1bcb01a8dad4557a4e92b8205.pdf)

[Machine Learning Methods for Solving Assignment Problems in Multi-Target Tracking](https://arxiv.xilesou.top/pdf/1802.06897)

[Deep Learning in Video Multi-Object Tracking_ A Survey](https://arxiv.xilesou.top/pdf/1907.12740)

[Globally-Optimal Greedy Algorithms for Tracking a Variable Number of Objects](http://vision.stanford.edu/teaching/cs231b_spring1415/slides/greedy_fahim_albert.pdf)



## Datasets

[MOT](https://motchallenge.net/)：包含2D MOT2015、3D MOT2015、MOT16、MOT17和MOT17Det等多个子数据集，提供了ACF、DPM、Faster RCNN、SDP等多个检测器输入。包含不同的相机视角、相机运动、场景和时间变化以及密集场景。

[KITTI](http://www.cvlibs.net/datasets/kitti/eval_tracking.php)：提供了汽车和行人的标注，场景较稀疏。

[TUD Stadtmitte](https://www.d2.mpi-inf.mpg.de/node/428)：包含3D人体姿态识别、多视角行人检测和朝向检测、以及行人跟踪的标注，相机视角很低，数据集不大。

[ETHZ](https://data.vision.ee.ethz.ch/cvl/aess/dataset/)：由手机拍摄的多人跟踪数据集，包含三个场景。

[EPFL](https://cvlab.epfl.ch/data/data-pom-index-php/#terrace)：多摄像头采集的行人检测和跟踪数据集，每隔摄像头离地2米，实验人员就是一个实验室的，分为实验室、校园、平台、通道、篮球场这5个场景，每个场景下都有多个摄像头，每个摄像头拍摄2分钟左右。

[KIT AIS](https://creativecommons.org/licenses/by/3.0/)：空中拍摄的，只有行人的头

[PETS](https://motchallenge.net/data/PETS2017/)：比较早期的视频，有各式各样的行人运动。

[DukeMTMC](http://vision.cs.duke.edu/DukeMTMC/)：多摄像头多行人跟踪。

[MOTS](https://www.vision.rwth-aachen.de/page/mots)：多目标跟踪与分割。



## Evaluation

[ClearMOT](https://cvhci.anthropomatik.kit.edu/images/stories/msmmi/papers/eurasip2008.pdf)

[IDF1](https://users.cs.duke.edu/~ristani/bmtt2016/ristani2016MTMC.pdf)

Code: [python](https://github.com/cheind/py-motmetrics)、[matlab](https://motchallenge.net/devkit/)
