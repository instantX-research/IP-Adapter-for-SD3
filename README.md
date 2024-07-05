<div align="center">
<h1>IP-Adapter for SD3</h1>

[**Qixun Wang**](https://github.com/wangqixun)<sup>1+</sup> · [**Xu Bai**](https://github.com/Yue02280220)<sup>1+</sup> · [**Hu Ye**](https://github.com/xiaohu2015)<sup>12</sup> · [**Haofan Wang**](https://haofanwang.github.io/)<sup>1*</sup>


<sup>1</sup>InstantX Team · <sup>2</sup>Tencent

<sup>+</sup>equal contribution

<sup>*</sup>corresponding authors


<a href='https://github.com/instantX-research/IP-Adapter-for-SD3'><img src='https://img.shields.io/badge/Project-Page-green'></a>
<a href='xxxxx'><img src='https://img.shields.io/badge/Technique-Report-red'></a>
[![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-Model-blue)](xxxxxxxx)
[![GitHub](https://img.shields.io/github/stars/instantX-research/IP-Adapter-for-SD3?style=social)](https://github.com/instantX-research/IP-Adapter-for-SD3)


</div>


IP-Adapter-for-SD3 is an adaptation scheme of [IP-Adapter](https://github.com/tencent-ailab/IP-Adapter) on [stabilityai/stable-diffusion-3-medium](https://huggingface.co/stabilityai/stable-diffusion-3-medium), with the algorithmic structure highly referencing that of IP-Adapter. It is designed to maintain the basis of text editing while introducing image guidance. Image guidance includes the embedding of people, objects, and styles. It is also compatible with [SD3-Controlnet-Canny](https://huggingface.co/InstantX/SD3-Controlnet-Canny), [SD3-Controlnet-Tile](https://huggingface.co/InstantX/SD3-Controlnet-Tile), [SD3-Controlnet-Pose](https://huggingface.co/InstantX/SD3-Controlnet-Pose), and other SD3 plugins.

<div align="center">
<img src='assets/case.png' width = 900 >
</div>
