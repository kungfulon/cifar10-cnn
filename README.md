# cifar10-cnn

Kiến trúc CNN:
- 4 tầng convolutional, 2 tầng max pooling và 3 tầng dense
- Sau 2 tầng convolutional là 1 tầng max pooling và dropout 0.25
- Sau mỗi tầng dense là dropout 0.5
- Ngoại trừ tầng cuối sử dụng activation softmax thì các tầng khác sử dụng activation relu

Accuracy thu được với CNN này là 81.2%. Model được nén thành file cifar10.tar.gz.
