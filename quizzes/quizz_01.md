# Building a Video AI Application

### 1. Which of the following is a Computer Vision task for drawing insights from videos? (Choose one)

- Classification to determine which objects are in an image.

- Object Detection combines classification and localization to determine what and where objects are in an image.

- Segmentation to provide pixel-wise masks generated for each object in the image.

- **All of the above**

### 2. Which of the following is not a plugin available in DeepStream? (Choose one)

- Source

- Encoding / Decoding

- **Probe**

- Inference

- Sink

### 3. Which of the following is false about DeepStream components? (Choose one)

- Elements are the core building blocks to construct pipelines.

- Pads are the interface between elements and caps (or capabilities) are the data types that a pad is permitted to utilize or emit.

- Buffers contain the data that will pass through the pipeline, which typically consist of pointers to memory objects, a timestamp, and a count to indicate how many elements are using the buffer.

- **Data flowing through the pipeline is achieved when one element pushes a buffer through its sink pad into the source pad of another element.**

### 4. Which of the following statement about measuring video AI application success is false? (Choose one)

- **Hardware utilization and memory footprint should be high.**

- Accuracy, which can include IoU and mAP for object detection or false negative rates for classification, should be high.

- Frames-per-second of the pipeline, which considers latency and throughput, should be high.

- Time to development and cost should be low.

### 5. Which of the following is an advantage of using DeepStream for Real-Time Video AI Application? (Choose all that applies)

- [x] **Includes various hardware accelerated plugins for encoding/decoding, AI inference, scaling, and conversion.**

- [x] **Uses a plugin architecture which enables flexibility to develop highly-performant applications with different input and output requirements.**

- [x] **Provides compatibility with state-of-the-art video AI models.**

- [x] **Supports remote management for deployment in any cloud and at the edge.**