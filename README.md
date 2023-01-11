# Stable Diffusion Protogen Cog model

This is an implementation of the [Protogen v2.2](https://huggingface.co/darkstorm2150/Protogen_v2.2_Official_Release) as a Cog model. [Cog packages machine learning models as standard containers.](https://github.com/replicate/cog)

First, download the pre-trained weights:

    cog run script/download-weights 

Then, you can run predictions:

    cog predict -i prompt="monkey scuba diving"
