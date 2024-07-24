## This is the repository for my thesis on LLM finetuning for interactive game dialogues
### Author: Giorgos Artopoulos

Below  you will find the following files:
- `README.md`: This file
- `dataset_final_prep.ipynb`: The notebook used to prepare the dataset for the experiments
- `mistral_dialogue_data_finetune.ipynb`: The notebook used to finetune the LLM on the dialogues dataset with qlora
- `mistral_monologue_data_finetune.ipynb`: The notebook used to finetune the LLM on the monologues dataset with qlora
- `llama2_dialogue_data_finetune.ipynb`: The notebook used to finetune the LLM on the dialogues dataset with qlora
- `llama2_monologue_data_finetune.ipynb`: The notebook used to finetune the LLM on the monologues dataset with qlora
- `model_results`: The directory containing the excel files with the answers given by the models based on the evaluation sets.
- `testing_for_error`: The directory containing the json files used to test that the datageneration tokenization work correctly
- `dataset_final_results`: The irectory containing the json files with the training testing and validation sets
- `testing_excel.xlsx`: The excel containing the datasets used, it was created using the dialogues in the following pages [Skyrim:Generic](https://en.uesp.net/wiki/Skyrim:Generic_Dialogue)
 and [Skyrim:Guard Dialogue](https://en.uesp.net/wiki/Skyrim:Guard_Dialogue), as well as introductory monologues found in YouTube videos.
