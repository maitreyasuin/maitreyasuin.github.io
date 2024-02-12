##  Publications and Preprints
### 2024

#### [CLR-Face: Conditional Latent Refinement for Blind Face Restoration Using Score-Based Diffusion Models (Arxiv-Preprint)](https://arxiv.org/pdf/2402.06106.pdf)

**Maitreya Suin** and Rama Chellappa.

<table>
<colgroup>
<col width="25%" />
<col width="85%" />
</colgroup>
<tbody>
<tr>
<td markdown="span"><img src="https://github.com/maitreyasuin/maitreyasuin.github.io/blob/master/images/ijcai.png?raw=true" width="182" height="102"></td>
<td markdown="span"> Generating fine-grained facial details faithful to inputs remains a challenging problem. Most existing methods produce either overly smooth outputs or alter the identity as they attempt to balance between generation and reconstruction. This may be attributed to the typical trade-off between quality and resolution in the latent space. We introduce a diffusion-based-prior inside a VQGAN architecture that focuses on learning the distribution over uncorrupted latent embeddings. We iteratively recover the clean embedding conditioning on the degraded counterpart. To ensure the reverse diffusion trajectory does not deviate from the underlying identity, we train a separate Identity Recovery Network and use its output to constrain the diffusion process. </td>
</tr>
</tbody>
</table>

#### [Spatially-Attentive Patch-Hierarchical Network with Adaptive Sampling for Motion Deblurring (Arxiv-Preprint)](https://arxiv.org/pdf/2402.06117.pdf)

**Maitreya Suin**, Kuldeep Purohit and A. N. Rajagopalan.

<table>
<colgroup>
<col width="25%" />
<col width="85%" />
</colgroup>
<tbody>
<tr>
<td markdown="span"><img src="https://github.com/maitreyasuin/maitreyasuin.github.io/blob/master/images/ext.png?raw=true" width="182" height="102"></td>
<td markdown="span"> We propose a pixel-adaptive and feature-attentive design for handling large blur variations across different spatial locations and process each test image adaptively. We design a content-aware global-local filtering module that significantly improves performance by considering not only global dependencies but also by dynamically exploiting neighboring pixel information. We further introduce a pixel-adaptive non-uniform sampling strategy that implicitly discovers the difficult-to-restore regions present in the image and, in turn, performs fine-grained refinement in a progressive manner. </td>
</tr>
</tbody>
</table>

#### [Diffuse and Restore: A Region-Adaptive Diffusion Model for Identity-Preserving Blind Face Restoration (WACV24)](https://openaccess.thecvf.com/content/WACV2024/papers/Suin_Diffuse_and_Restore_A_Region-Adaptive_Diffusion_Model_for_Identity-Preserving_Blind_WACV_2024_paper.pdf)

**Maitreya Suin**, Nithin Gopalakrishnan Nair, Chun Pong Lau, Vishal M. Patel and Rama Chellappa.

<table>
<colgroup>
<col width="25%" />
<col width="85%" />
</colgroup>
<tbody>
<tr>
<td markdown="span"><img src="https://github.com/maitreyasuin/maitreyasuin.github.io/blob/master/images/wacv.png?raw=true" width="182" height="102"></td>
<td markdown="span"> Blind face restoration (BFR) from severely degraded face images in the wild is a highly ill-posed problem. Existing generative works typically struggle to restore realistic details when the input is of poor quality. For BFR, maintaining a balance between the fidelity of the restored image and the reconstructed identity information is important. We present a conditional diffusion-based framework for BFR. We alleviate the drawbacks of existing diffusion-based approaches and design a region-adaptive strategy. This leads to a significant improvement in perceptual quality as well as face-recognition scores. </td>
</tr>
</tbody>
</table>


### 2023
#### [DIFFNAT: Improving Diffusion Image Quality Using Natural Image Statistics (Arxiv-Preprint)](https://arxiv.org/pdf/2311.09753.pdf)

Aniket Roy, **Maiterya Suin**, Anshul Shah, Ketul Shah, Jiang Liu, Rama Chellappa

<table>
<colgroup>
<col width="25%" />
<col width="85%" />
</colgroup>
<tbody>
<tr>
<td markdown="span"><img src="https://github.com/maitreyasuin/maitreyasuin.github.io/blob/master/images/diffnat.png?raw=true" width="182" height="102"></td>
<td markdown="span"> We propose a generic “naturalness” preserving loss function, viz., kurtosis concentration (KC) loss, which can be readily applied to any standard diffusion model pipeline to elevate the image quality. Our motivation stems from the projected kurtosis concentration property of natural images, which states that natural images have nearly constant kurtosis values across different band-pass versions of the image. We validate the proposed approach for three diverse tasks, viz., (1) personalized few-shot finetuning using text guidance, (2) unconditional image generation, and (3) image super-resolution. </td>
</tr>
</tbody>
</table>

#### [ATDetect: Face Detection and Keypoint Extraction at Range and Altitude (IJCB23)]()

Chun Pong Lau, **Maiterya Suin** and Rama Chellappa

<table>
<colgroup>
<col width="25%" />
<col width="85%" />
</colgroup>
<tbody>
<tr>
<td markdown="span"><img src="https://github.com/maitreyasuin/maitreyasuin.github.io/blob/master/images/atdtct.png?raw=true" width="182" height="102"></td>
<td markdown="span"> While face detection works well in ideal situations, the performance deteriorates sig-
nificantly when the image is degraded, due to factors such as blur, deformation, low resolution, and extreme headpose. This motivates us to develop a face detection and alignment algorithm that could perform effectively on
videos captured from a long range and high altitude without groundtruth annotations. We propose a single-stage face
localization model ATDetect, which detects face bounding boxes, keypoints, and meta information simultaneously with
realistic video captured at range and altitude. </td>
</tr>
</tbody>
</table>

#### [Illumination-Adaptive Unpaired Low-Light Enhancement (IEEE-TCSVT)](https://ieeexplore.ieee.org/document/10032640)

Praveen Kandula, **Maitreya Suin** and A. N. Rajagopalan

<table>
<colgroup>
<col width="25%" />
<col width="85%" />
</colgroup>
<tbody>
<tr>
<td markdown="span"><img src="https://github.com/maitreyasuin/maitreyasuin.github.io/blob/master/images/lowlight.png?raw=true" width="182" height="102"></td>
<td markdown="span"> We propose an unsupervised low-light enhancement network using context-guided illumination-adaptive norm (CIN). We address this task in two stages. In stage- I, a pixel amplifier module (PAM) is used to generate a coarse estimate with an overall improvement in visibility and aesthetic quality. Stage- II further enhances the saturated dark pixels and scene properties of the image using CIN. We propose a region-adaptive single input multiple output (SIMO) model that can generate multiple enhanced images from a single low-light image. The objective of SIMO is to let users choose the image of their liking from a pool of enhanced images. </td>
</tr>
</tbody>
</table>

#### [Exploring the Effectiveness of Mask-Guided Feature Modulation as a Mechanism for Localized Style Editing of Real Images (AAAI23-SA)](https://arxiv.org/abs/2211.11224)

Snehal Singh Tomar, **Maitreya Suin** and A. N. Rajagopalan.

<table>
<colgroup>
<col width="25%" />
<col width="85%" />
</colgroup>
<tbody>
<tr>
<td markdown="span"><img src="https://github.com/maitreyasuin/maitreyasuin.github.io/blob/master/images/aaai_snehal.png?raw=true" width="182" height="102"></td>
<td markdown="span"> Most existing style-editing methods work on the principle of inverting real images onto their latent space, followed by determining controllable directions. Both inversion of real images and determination of controllable latent directions are computationally expensive operations. This work aims to explore the effcacy of mask-guided feature modulation in the latent space of a Deep Generative Model as a solution to these bottlenecks. To this end, we present the SemanticStyle Autoencoder (SSAE), a deep Generative Autoencoder model that leverages semantic mask-guided latent space manipulation for highly localized photorealistic style editing of real
images. </td>
</tr>
</tbody>
</table>

### 2022
#### [Hybrid Transformer Based Feature Fusion for Self-Supervised Monocular Depth Estimation (ECCVW-22)](https://arxiv.org/abs/2211.11066)

Snehal Singh Tomar, **Maitreya Suin** and A. N. Rajagopalan.

<table>
<colgroup>
<col width="25%" />
<col width="85%" />
</colgroup>
<tbody>
<tr>
<td markdown="span"><img src="https://github.com/maitreyasuin/maitreyasuin.github.io/blob/master/images/depth.png?raw=true" width="182" height="102"></td>
<td markdown="span"> Most State-of-the-art (SOTA) works in the self-supervised and unsupervised domain employ a ResNet-based encoder architecture to predict disparity maps from a given input image which are eventually used alongside a camera pose estimator to predict depth without direct supervision. The fully convolutional nature of ResNets makes them susceptible to capturing per-pixel local information only, which is suboptimal for depth prediction. Our key insight for doing away with this bottleneck is to use Vision Transformers, which employ self-attention to capture the global contextual information present in an input image. Our model fuses per-pixel local information learned using two fully convolutional depth encoders with global contextual information learned by a transformer encoder at different scales. </td>
</tr>
</tbody>
</table>


### 2021
#### [Distillation-guided Image Inpainting (ICCV21)](https://openaccess.thecvf.com/content/ICCV2021/papers/Suin_Distillation-Guided_Image_Inpainting_ICCV_2021_paper.pdf)

**Maitreya Suin**, Kuldeep Purohit and A. N. Rajagopalan.

<table>
<colgroup>
<col width="25%" />
<col width="85%" />
</colgroup>
<tbody>
<tr>
<td markdown="span"><img src="https://github.com/maitreyasuin/maitreyasuin.github.io/blob/master/images/iccv_inp.gif?raw=true" width="182" height="102"></td>
<td markdown="span"> Image inpainting is a highly ill-posed problem, and existing works often create distorted structures or blurry inconsistent textures. We argue that the problem is rooted in the encoder layers’ ineffectiveness in building a complete and faithful embedding of the missing regions from scratch. We propose a distillation-based approach for inpainting, where we provide direct feature-level supervision while training. We deploy cross and self-distillation techniques and design a dedicated completion-block in encoder. Next, we demonstrate how an inpainting network’s attention module can improve by leveraging a distillation-based attention transfer technique. We conduct evaluations on multiple datasets to validate our method. </td>
</tr>
</tbody>
</table>

#### [Spatially-Adaptive Image Restoration using Distortion-Guided Networks (ICCV21)](https://openaccess.thecvf.com/content/ICCV2021/papers/Purohit_Spatially-Adaptive_Image_Restoration_Using_Distortion-Guided_Networks_ICCV_2021_paper.pdf)

Kuldeep Purohit, **Maitreya Suin**, A. N. Rajagopalan and Vishnu Naresh Boddeti.

<table>
<colgroup>
<col width="25%" />
<col width="85%" />
</colgroup>
<tbody>
<tr>
<td markdown="span"><img src="https://github.com/maitreyasuin/maitreyasuin.github.io/blob/master/images/iccv21_rest.png?raw=true" width="182" height="102"></td>
<td markdown="span"> We propose SPAIR, a network design that harnesses distortion-localization information and dynamically adjusts computation to difficult regions in the image. SPAIR comprises of two components, (1) a localization network that identifies degraded pixels, and (2) a restoration network that exploits knowledge from the localization network in filter and feature domain to selectively and adaptively restore degraded pixels. Our architecture is agnostic to physical formation model and generalizes across several types of spatially-varying degradations. We demonstrate the efficacy of SPAIR individually on four restoration tasks.
 </td>
</tr>
</tbody>
</table>
 

#### [Gated Spatio-Temporal Attention-Guided Video Deblurring (CVPR21)](https://openaccess.thecvf.com/content/CVPR2021/papers/Suin_Gated_Spatio-Temporal_Attention-Guided_Video_Deblurring_CVPR_2021_paper.pdf)

**Maitreya Suin** and A. N. Rajagopalan.

<table>
<colgroup>
<col width="25%" />
<col width="85%" />
</colgroup>
<tbody>
<tr>
<td markdown="span"><img src="https://github.com/maitreyasuin/maitreyasuin.github.io/blob/master/images/cvpr21.gif?raw=true" width="182" height="102"></td>
<td markdown="span"> Most of the existing video deblurring works depend on implicit or explicit alignment for temporal fusion, which either increases the computational cost or results in suboptimal performance due to misalignment. We investigate two key factors: how to fuse spatio-temporal information and from where to collect it. We propose a factorized gated spatio-temporal attention module to perform non-local operations across space and time to fully utilize the available information without depending on alignment. It shows superior performance compared to existing non-local fusion techniques while being considerably more efficient. To complement the attention module, we propose a reinforcement learning-based framework for selecting keyframes from the neighborhood with the most complementary and useful information.
 </td>
</tr>
</tbody>
</table>


### 2020
#### [Spatially-attentive patch-hierarchical network for adaptive motion deblurring (CVPR20)](https://openaccess.thecvf.com/content_CVPR_2020/papers/Suin_Spatially-Attentive_Patch-Hierarchical_Network_for_Adaptive_Motion_Deblurring_CVPR_2020_paper.pdf)

**Maitreya Suin**, Kuldeep Purohit and A. N. Rajagopalan.

<table>
<colgroup>
<col width="25%" />
<col width="85%" />
</colgroup>
<tbody>
<tr>
<td markdown="span"><img src="https://github.com/maitreyasuin/maitreyasuin.github.io/blob/master/images/cvpr20.gif?raw=true" width="182" height="102"></td>
<td markdown="span"> We propose an efficient pixel adaptive and feature attentive design for handling large blur variations
across different spatial locations and process each test image adaptively. We design a content-aware global-local filtering module that significantly improves performance by considering not only global dependencies but also by dynamically exploiting neighboring pixel information. We use a patch-hierarchical attentive architecture composed of the above module that implicitly discovers the spatial variations in the blur present in the input image and in turn, performs local and global modulation of intermediate features. 
 </td>
</tr>
</tbody>
</table>

#### [Degradation Aware Approach to Image Restoration Using Knowledge Distillation (IEEE-JSTSP).](https://ieeexplore.ieee.org/abstract/document/9288928)

**Maitreya Suin**, Kuldeep Purohit and A. N. Rajagopalan.

<table>
<colgroup>
<col width="25%" />
<col width="85%" />
</colgroup>
<tbody>
<tr>
<td markdown="span"><img src="https://github.com/maitreyasuin/maitreyasuin.github.io/blob/master/images/jstsp.gif?raw=true" width="182" height="102"></td>
<td markdown="span"> We present a new approach suitable for handling the image-specific and spatially-varying nature of degradation in images affected by practically occurring artifacts such as rain-streaks, haze, raindrops and motion blur. We decompose the restoration task into two stages of degradation localization and degraded region-guided restoration, unlike existing methods which directly learn a mapping between the degraded and clean images. We demonstrate that the model trained for this auxiliary task contains vital region knowledge, which can be exploited to guide the restoration network's training using knowledge distillation technique. Further, we propose mask-guided modules to focus on restoring the degraded regions. We conduct an extensive evaluation on multiple datasets corresponding to four different restoration tasks to validate our method. 
 </td>
</tr>
</tbody>
</table>

#### [An Efficient Framework for Dense Video Captioning (AAAI20 - Oral)](https://ojs.aaai.org//index.php/AAAI/article/view/6881)

**Maitreya Suin** and A. N. Rajagopalan.

<table>
<colgroup>
<col width="25%" />
<col width="85%" />
</colgroup>
<tbody>
<tr>
<td markdown="span"><img src="https://github.com/maitreyasuin/maitreyasuin.github.io/blob/master/images/aaai.png?raw=true" width="182" height="102"></td>
<td markdown="span"> We focus on the task of generating a dense description of temporally untrimmed videos and aim to significantly reduce the computational cost by processing fewer frames while maintaining accuracy. Existing video captioning methods sample frames with a predefined frequency over the entire video or use all the frames. Instead, we propose a deep reinforcement-based approach which enables an agent to describe multiple events in a video by watching a portion of the frames. The agent needs to watch more frames when it is processing an informative part of the video, and skip frames when there is redundancy. Such an efficient frame selection simplifies the event proposal task considerably. This has the added effect of reducing the occurrence of unwanted proposals. We also leverage the idea of knowledge distillation to improve the accuracy. 
 </td>
</tr>
</tbody>
</table>

### 2019
#### [Depth-guided dense dynamic filtering network for bokeh effect rendering (ICCVW19)](https://ieeexplore.ieee.org/abstract/document/9022538)

Kuldeep Purohit, **Maitreya Suin**, Praveen Kandula and A. N. Rajagopalan.

<table>
<colgroup>
<col width="25%" />
<col width="85%" />
</colgroup>
<tbody>
<tr>
<td markdown="span"><img src="https://github.com/maitreyasuin/maitreyasuin.github.io/blob/master/images/iccvw.png?raw=true" width="182" height="102"></td>
<td markdown="span"> We present a learning-based method for rendering such synthetic depth-of-field effect on input bokeh-free images acquired using ordinary monocular cameras. The proposed network is composed of an efficient densely connected encoder-decoder backbone structure with a pyramid pooling module. Our network leverages the task-specific efficacy of joint intensity estimation and dynamic filter synthesis for the spatially-aware blurring process. Since the rendering task requires distinguishing between large foreground and background regions and their relative depth, our network is further guided by pre-trained salient-region segmentation and
depth-estimation modules. Along with extensive ablation analysis and visualizations to validate its components, the effectiveness of the proposed network is also demonstrated by achieving the second-highest score in the AIM 2019 Bokeh Effect challenge: fidelity track.
 </td>
</tr>
</tbody>
</table>
 
 
##  Co-authored Workshop Proceedings
### 2021
- [NTIRE 2021 Depth Guided Image Relighting Challenge](https://arxiv.org/abs/2104.13365)
- [NTIRE 2021 Challenge on Image Deblurring]()

### 2020
- [Ntire 2020 challenge on image and video deblurring](https://openaccess.thecvf.com/content_CVPRW_2020/html/w31/Nah_NTIRE_2020_Challenge_on_Image_and_Video_Deblurring_CVPRW_2020_paper.html)
- [AIM 2020 challenge on efficient super-resolution: Methods and results](https://arxiv.org/abs/2009.06943)
- [AIM 2020: Scene relighting and illumination estimation challenge](https://arxiv.org/pdf/2009.12798)
- [AIM 2020 challenge on rendering realistic bokeh](http://people.ee.ethz.ch/~timofter/publications/Ignatov-ECCVW-2020b.pdf)

### 2019
- [Ntire 2019 challenge on image colorization: Report](http://openaccess.thecvf.com/content_CVPRW_2019/papers/NTIRE/Gu_NTIRE_2019_Challenge_on_Image_Colorization_Report_CVPRW_2019_paper.pdf)
- [Ntire 2019 image dehazing challenge report](http://openaccess.thecvf.com/content_CVPRW_2019/papers/NTIRE/Ancuti_NTIRE_2019_Image_Dehazing_Challenge_Report_CVPRW_2019_paper.pdf)
- [Aim 2019 challenge on bokeh effect synthesis: Methods and results](https://ieeexplore.ieee.org/abstract/document/9022578/)
- [AIM 2019 Challenge on Image Extreme Super-Resolution: Methods and Results](https://people.ee.ethz.ch/~timofter/publications/Gu-ICCVW-2019.pdf)
- [Aim 2019 challenge on image demoireing: Methods and results](https://ieeexplore.ieee.org/abstract/document/9022366)
- [Aim 2019 challenge on image extreme super-resolution: Methods and results](https://ieeexplore.ieee.org/abstract/document/9022627)
- [Aim 2019 challenge on real-world image super-resolution: Methods and results](https://ieeexplore.ieee.org/abstract/document/9022354)
