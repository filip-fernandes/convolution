# convolution
Implementation of convolutional layers.

I wrote this convolutional layer and convolutional network as an introduction to computer vision and applying deep learning to process and analyze graphical data.<br>

The layer I created is similar to the torch.nn.Conv2d, as shown in the ConvoNet file. It supports dilation, strides and same padding.<br>

Doing it for RGB images was challenging, and I ended up learning a lot about how to manipulate tensors and how images are processed in convolutional layers.

<table style="width:50%; table-layout:fixed;">
  <tr>
    <td><img width="150px" src="gif/no_padding_no_strides.gif"></td>
    <td><img width="150px" src="gif/arbitrary_padding_no_strides.gif"></td>
    <td><img width="150px" src="gif/same_padding_no_strides.gif"></td>
    <td><img width="150px" src="gif/full_padding_no_strides.gif"></td>
    <td><img width="150px" src="gif/padding_strides.gif"></td>
    <td><img width="150px" src="gif/dilation.gif"></td>
  </tr>
  <tr>
    <td>No padding, no strides</td>
    <td>Arbitrary padding, no strides</td>
    <td>Same padding, no strides</td>
    <td>Full padding, no strides</td>
    <td>Padding, strides</td>
    <td>Dilation</td>
  <tr>
</table>

I copied the gifs from <a href="https://github.com/vdumoulin/conv_arithmetic/blob/master/README.md?plain=1">this repo</a>.



