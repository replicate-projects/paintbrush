# paintbrush

Web Demoe and API: 
[![Replicate](https://replicate.com/timothybrooks/instruct-pix2pix/badge)](https://replicate.com/timothybrooks/instruct-pix2pix)

github app[paintbrush: Learning to Follow Image Editing Instructions](https://github.com/replicate-projects/paintbrush) framework [diffuser](https://github.com/huggingface/diffusers)


First, download the weights (update the corresponding `model_id` of the model, which need to be available on HuggingFace):

    cog run script/download-weights 

Then, you can run predictions:

    cog predict -i prompt="..." -i image=@...

Or, push to a Replicate page:

    cog push r8.im/...






