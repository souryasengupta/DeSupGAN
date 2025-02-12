# DeSupGAN
This repo has relevant codes of the paper "DeSupGAN: Multi-scale Feature AveragingGenerative Adversarial Network forSimultaneous De-blurring and Super-resolutionof Retinal Fundus Images"
authored by Sourya Sengupta, Alexander Wong, Amitojdeep Singh, John Zelek, and Vasudevan Lakshminarayanan.

This paper has been accepted at 7th OMIA Workshop at MICCAI 2020. LNCS Proceedings coming soon !

Abstract: Image quality is of utmost importance for image-based clinical diagnosis. 
In this paper, a generative adversarial network-based retinal fundus quality enhancement network is proposed. With the advent of different cheaper, affordable and lighter point-of-care imaging or telemedicine devices, the chances of making a better and more accessible healthcare system in developing countries become higher. But these devices often lack the quality of images. This single network simultaneously takes into account two different image degradation problems that are common i.e. blurring and low spatial resolution. A novel convolutional multi-scale feature averaging block (MFAB) is proposed which can extract feature maps with different kernel sizes and fuse them together. Both local and global feature fusion are used to get a stable training of wide network and to learn the hierarchical global features. The results show that this network achieves better results in terms of peak-signal-to-noise ratio (PSNR) and structural similarity index (SSIM) metrics compared with other super-resolution, de-blurring methods. To the best of our knowledge, this is the first work that has combined multiple degradation models simultaneously for retinal fundus images analysis.


Other than the proposed DeSupGAN, also SRGAN, SRRESNET and combination fo SRGAN+DeBlurGAN were used. Relevant codes are uploaded which are based on the individual original papers of the models.
