# Starter for deploying [fast.ai](https://www.fast.ai) models on [Render](https://render.com)

This repo is a fork of the following : https://github.com/render-examples/fastai-v3 

This repo can be used as a starting point to deploy [fast.ai](https://github.com/fastai/fastai) models on Render.

The model used for classifying images was created using Fastai Library using [this code](https://colab.research.google.com/drive/1wg0VuVgtzqV8b-zNh8a_R_pTVYLP1vMp)

You can test your changes locally by installing Docker and using the following command:

```
docker build -t fastai-v3 . && docker run --rm -it -p 5000:5000 fastai-v3
```

The guide for production deployment to Render is at https://course.fast.ai/deployment_render.html.
