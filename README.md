# Deep-Learning-Pixel-to-Predictions

> There are two versions of the full version of the Notebook: One for Google Colab and One for Kaggle. There are minor differences between the two with certain parameters being adjusted to better suit the limitations of the GPU and keep training time to an acceptable amount. Paths to access inputs are also different.

> The A100 GPU was used for testing in the Google Colab while the GPU T4 x2 was used in Kaggle. 

## Notebook can be broken down to three sections:
> The notebook is compromised of three parts: the preprocessing of data, training the model and inference for output generation.
> Two smaller notebooks were created that can be run on their own (dl-final-training-notebook-kaggle.ipynb, and dl-final-generation-inference-kaggle.ipynb)

### 1. Preprocessing
> This section focuses on preprocessing the data provided from train.csv, val.csv and testing.csv to make datasets out of them

> Make sure notebook has access to all the data as an input or adjust path for notebook to access it 

### 2. Training
> This section focuses on training the model on the training dataset and validating on the validation dataset


### 3. Inference/Generation
> This section focuses on generating outputs with the model

> Make sure notebook has access to test.csv as an input if you want to test the model against it and access to a HuggingFace Token to use the fine-tuned model!

> Here we focus on generating outputs based on given inputs. There are two versions of outputting: single prompt output and batch prompt outputs

## Instructions (Full Version)
> 1. Choose a version of the notebook based on your notebook enivornment (Google Colab or Kaggle)
> 2. Download and access the notebook in its environment
> 3. Upload train.csv, val.csv and test.csv as inputs that the notebook can access
> 4. Make sure notebook can you use your HuggingFace token key
> 5. Run each cell block step-by-step

## Instructions for Mini Notebooks based on section 
> 1. Choose a notebook section (training, inference)
> 2. Download and access the notebook in its environment
> 3. Upload necessary data that the notebook can access
> 4. Make sure notebook can you use your HuggingFace token key
>   - training needs WRITE HuggingFace Token if you are saving the model to HuggingFace
>   - inference needs HuggingFace Token to access model weight cloud saved in HuggingFace
> 5. Run each cell block step-by-step 

## **Important**
> Make sure that train.csv, val.csv, test.csv and all their corresponding images are downloaded to upload them as inputs for the notebooks to access!

> Have a HuggingFace Token Key for Reading and Writing. Make sure notebook has access to them before running it!

## Misc
> If you want to see a graphs of the training and validation datasets along with graph on validation accuracy, check out the [Submission and Figures Folder](https://github.com/tk2558/Deep-Learning-Pixel-to-Predictions/tree/main/Submission%20and%20Figures)

> You can also see all the outputs the model generated for 1000 test prompts in [submission.csv](https://github.com/tk2558/Deep-Learning-Pixel-to-Predictions/blob/main/Submission%20and%20Figures/top_submission.csv)

## **Links**

> [Finals Report in ACL Format](https://drive.google.com/file/d/1nSo2DcXHcBo1jlaVpNXREW8AyKPuANgW/view?usp=sharing)

> [Model Weights in Hugging Face](https://huggingface.co/tk2558/DL_Finals_Model)

> [SmolVLM-500M-Instruct Model](https://huggingface.co/HuggingFaceTB/SmolVLM-500M-Instruct)

> [Github Repo](https://github.com/tk2558/Deep-Learning-Pixel-to-Predictions/tree/main)
