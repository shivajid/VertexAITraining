## Vertex Training and ML Metadaa

There are two pipeline shown in the following notebooks:

- VertexAICifar10CustomTraining - This notebooks demonstartes running a Vertex AI Training using pre-built containers. This uses a CIFAR10 dataset. This also logs the experiment details on a tensorboard logs which can monitored in the Experiment Tab
- MLMetadata - This creates a ML Pipeline using Custom Components usning a python container. It then stiches the components in a pipeline and deploys to Vertex Pipeline. We will run two runs of the pipeline and show how Lineage is tracked and how you can compare across these runs.


