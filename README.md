# flownet
An implementation of the FlowNetC correlation layer in tensorflow
[jgorgenucsd/corr_tf](https://github.com/jgorgenucsd/corr_tf)
The FlowNetC architecture (https://arxiv.org/abs/1504.06852) uses a novel cross correlation layer

This is an implementation of that cross correlation layer in tensorflow
The function correlation_layer.corr expects two arguments, 4 dim tensors of size (batch_size,height,width,num_channels)

I eliminate custom CUDA code to use keras lamda only.
