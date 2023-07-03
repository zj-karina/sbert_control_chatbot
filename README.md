Repository with ChatGPT dataset creation, GPT-J model training files for dialog generation, and LaBSE training for cosine proximity on instructional dialogs. 

User input is implemented in `chatbot_inferense.ipynb` . It is constructed as follows: when generating a response, 3 options are given and using the LaBSE model, we select the closest option to the dialog requests from the user. LaBSE was validated on ranking metrics in `eval_sensim.ipynb`
