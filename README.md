# reddit-anxiety-detection
Finetuned model calculates the anxiety of a given text on a scale of 0 to 1

1. `dataset_script` scrapes Reddit posts from the internet, which are displayed using IPython Display
2. `bert_training` uses distilbert-base-uncased and finetunes it on this particular task
