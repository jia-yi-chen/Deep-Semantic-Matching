# Illumination-guided Non-photorealistic Neural Style Transfer

A semi-supervised learning method.
The code Providing lighting maps for input images, to guide the correct drawing style (stroke, colow, texture) to put on correct place.
Doing PatchMatch on 
calculating lighting context.

* good to express lighting , 
* good to protect scene structure, because of protection of lighting
* good to draw lanscapes, sky, and human faces
 PYTHON implementation of master thesis "". will be uploaded soon.

## Requirements

* python 3
* pytorch 1.0+

## References

1. Connelly Barnes, Eli Shechtman, Adam Finkelstein, and Dan B Goldman.
**PatchMatch: A Randomized Correspondence Algorithm for Structural Image Editing**.
ACM Transactions on Graphics (Proc. SIGGRAPH) 28(3), August 2009. [PatchMatch](https://gfx.cs.princeton.edu/pubs/Barnes_2009_PAR/index.php)

2. Gatys, Leon A., Alexander S. Ecker, and Matthias Bethge. "Image style transfer using convolutional neural networks." Proceedings of the IEEE conference on computer vision and pattern recognition. 2016. [Neural Style Transfer](http://openaccess.thecvf.com/content_cvpr_2016/html/Gatys_Image_Style_Transfer_CVPR_2016_paper.html)

3. Liao, Jing, et al. "Visual attribute transfer through deep image analogy." ACM Transactions on Graphics (TOG) 36.4 (2017): 120. [Deep Image Analogy](https://arxiv.org/abs/1705.01088)

4. Champandard, Alex J. "Semantic style transfer and turning two-bit doodles into fine artworks." arXiv preprint arXiv:1603.01768 (2016). [Semantic style transfer]()

5. Fišer, Jakub, et al. "StyLit: illumination-guided example-based stylization of 3D renderings." ACM Transactions on Graphics (TOG) 35.4 (2016): 92. [StyLit](https://dl.acm.org/citation.cfm?id=2925948)

## Some Results

### Task #1: Painterly Rendering 3D Models

![image](https://github.com/jia-yi-chen/Deep-Semantic-Matching/blob/master/results/2.jpg)

### Task #2: Lanscape Painting

* robust to input photos containing a lot of sunlight (e.g., drawing sky)

![image](https://github.com/jia-yi-chen/Deep-Semantic-Matching/blob/master/results/1.jpg)
