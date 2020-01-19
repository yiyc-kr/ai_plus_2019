# Deep Learning 모델 경량화

## Giant Models are Coming

* XLNet
340m param
512 TPU x 2.5 days x $8 = $245,000

* CNNs
GPipe
AmoebaNet
NAS

## Towards On-device AI

1. Model Size

2. Speed

3. Energe Efficiency

## Approaches for Lightweight Models

* Reduce size of operands for storage/compute
* Compact network

floating point -> fixed point

* quantization

* network pruning

* Knowledge Distilation

## Convolution

## Bottleneck Layer, Global Average Pooling

reduce params

## Group Convolution

필터별로 앞이나 뒤만 보게 

## Depthwise Separable Convolution

Depthwise + Pointwise convolutoin

## Feature Map Reuse

Dense net

## Shift

* Grouped Shift

* Active Shift

* Sparse Shift

addressing?

# Lightweight Models

MobileNet
SuffleNet

# Further Considerations

latency vs 연산량

Weights vs Energy

# Guide

메모리액세스 코스트 줄이려면 인풋과 아웃풋 채널을 똑같이 만들어라


