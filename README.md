# Pre-Train BERT from Scratch with TPU

Steps:	

	- `pip install -r requirements.txt`

	- In the notebook, we are using create_pretraining_data.py and run_pretraining.py from BERT &
	  convert_tf_to_pytorch.py from HuggingFace's transformers.

	- Add TPU address in $TPU_NAME ($TPU_NAME is the environment variable name in Kaggle environment)

	- Instead of absolute paths, one should use Google Cloud Storage Bucket addresses.
