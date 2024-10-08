# Translation Application

Language Translation is the communication of the meaning of a source-language text by means of an equivalent target-language text.

Translation architecture shows below:

![architecture](./assets/img/translation_architecture.png)

This Translation use case performs Language Translation Inference on Intel Gaudi2 or Intel Xeon Scalable Processors. The Intel Gaudi2 accelerator supports both training and inference for deep learning models in particular for LLMs. Visit [Habana AI products](https://habana.ai/products) for more details.

## Deploy Translation Service

The Translation service can be effortlessly deployed on either Intel Gaudi2 or Intel Xeon Scalable Processors.

### Deploy Translation on Gaudi

Refer to the [Gaudi Guide](./docker_compose/intel/hpu/gaudi/README.md) for instructions on deploying Translation on Gaudi.

### Deploy Translation on Xeon

Refer to the [Xeon Guide](./docker_compose/intel/cpu/xeon/README.md) for instructions on deploying Translation on Xeon.
