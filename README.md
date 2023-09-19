Clone the repository and install the required packages.

```
git clone https://github.com/hadi19999/finetuner.git
cd simple-llm-finetuner
pip install -r requirements.txt
```

Launch it

```
python app.py
```

Open http://127.0.0.1:7860/ in your browser. Prepare your training data by separating each sample with 2 blank lines. Paste the whole training dataset into the textbox. Specify the new LoRA adapter name in the "New PEFT Adapter Name" textbox, then click train. You might need to adjust the max sequence length and batch size to fit your GPU memory. The model will be saved in the `lora/` directory.

After training is done, navigate to "Inference" tab, select your LoRA, and play with it.
