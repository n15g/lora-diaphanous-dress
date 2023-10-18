# LoRA - Diaphanous Dress

Open-sourced LoRA configuration and training data for Stable Diffusion 1.5.

| `f3e`                           | `dreamshaper_8`                              |
|---------------------------------|----------------------------------------------|
| ![2D](1.0/f3e-1.0-2b73b869.png) | ![Realistic](1.0/dreamshaper_8-eff91f64.png) |

_It's like wearing nothing at all! nothing at all! nothing at all!_

Light, silky dresses made from sheer fabrics that drape in ethereal ripples over
the body.

https://civitai.com/models/167598/diaphanous-dress

## Parameters

Recommended weight: `0.8`

Activation tags: `diaphanous dress`

Secondary tags:

* `<color> diaphanous dress`
* `puffy sleeves`
* `long dress`

## Version History

![XYZ0](1.0/xyz0.png)

#### v1.0

* Release

## Training

* Load config into [Kohya SS](https://github.com/bmaltais/kohya_ss)
* Download a base model. I use a custom mix that I created called [f3e - Forge](https://civitai.com/models/160315)
* Download or create regularization images for the chosen model.
  For Forge use [reg-f3e-1girl](https://github.com/n15g/reg-f3e-1girl).
* Update paths for the model, image, output and logging folders
* Adjust the batch size for your GPU

| VRAM       | 24 GiB | 12 GiB | 8GiB |
|------------|--------|--------|------|
| Batch Size | 10     | 4      | 2-3  |
