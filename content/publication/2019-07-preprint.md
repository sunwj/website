+++
abstract = "Deep convolutional neural network based image super-resolution (SR) models have shown superior performance in recovering the underlying high resolution (HR) images from low resolution (LR) images obtained from the predefined downscaling methods. In this paper we propose a learned image downscaling method based on content adaptive resampler (CAR) with consideration on the upscaling process. The proposed resampler network generates content adaptive image resampling kernels that are applied to the original HR input to generate pixels on the downscaled image. Moreover, a differentiable upscaling (SR) module is employed to upscale the LR result into its underlying HR counterpart. By back-propagating the reconstruction error down to the original HR input across the entire framework to adjust model parameters, the proposed framework achieves a new state-of-the-art SR performance through upscaling guided image resamplers which adaptively preserve detailed information that is essential to the upscaling. Experimental results indicate that the quality of the generated LR image is comparable to that of the traditional interpolation based method, but the significant SR performance gain is achieved by deep SR models trained jointly with the CAR model."

abstract_short = ""
authors = ["Wanjie Sun", "Zhenzhong Chen"]
date = "2019-07-01"
image_preview = ""
math = true
publication_types = ["2"]
publication = "In *arXiv preprint*"
publication_short = ""
selected = true
title = "Learned Image Downscaling for Upscaling using Content Adaptive Resampler"
url_code = "https://github.com/sunwj/CAR"
#url_dataset = "#"
url_pdf = "https://arxiv.org/pdf/1907.12904.pdf"
#url_project = ""
#url_slides = "#"
#url_video = "#"

#[[url_custom]]
#name = "Custom Link"
#url = "http://www.example.org"

# Optional featured image (relative to `static/img/` folder).
[header]
image = "headers/car.jpg"
caption = "Learned Image Downscaling for Upscaling using Content Adaptive Resampler :smile:"

+++

More detail can easily be found on <a href="#">here</a>.
