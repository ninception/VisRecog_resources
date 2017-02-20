
#Object Detection (Human Detection) using HoG

## [Link To CVPR'05 Dalal Triggs Paper](http://lear.inrialpes.fr/people/triggs/pubs/Dalal-cvpr05.pdf)

### Short Summary (Add in a way to keep it concise and insightful)

The method is quite similar to SIFT. However it is important to note differences. 
* It is a robust dense coding of spatial form , instead of a Sparse representation of an image as in SIFT.
* There is no dominant orientation alignment as in SIFT.
* SIFT descriptors are meant to be used individually and associated with a Keypoint, while HoG descriptors are associated with a block.

Normalization is done over the block, to reduce the effects of gradient changes due to illumination etc and keep it robust.
Finally Linear or Kernel SVM is used to classify results in positive(Human) or Negative Categories.


### Doubts

#### 1. (Asim) Section 6.3 in above Paper 
#### ~"To reduce aliasing, votes are interpolated bilinearly between the neighbouring bin centres in both orientation and position"
What is the meant by above?


