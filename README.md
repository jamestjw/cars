# cars

At attempt at the Stanford Cars dataset. We finetune a ResNet model on the Cars dataset with Mixup, eventually moving over to PairWise Confusion. To carry out <strong>inference</strong>, kindly refer to notebook 5 which has the relevant instructions.

Before running any notebooks, kindly install fastai via `conda install -c pytorch -c fastai fastai` or `pip install fastai`.

The first four notebooks includes my initial attempts at the model and illustrates all the steps I took to reaching the final results. The final notebook is for inference only and can be run without running the previous notebooks first. For inference, I recommend cloning the whole repo, steps to download the final model can be found in notebook 5 and it requires the meta files suchs as `classes.pkl` and `labels.pkl` (which are in this repo).
