# BPE Models

Here are the BPE models that you can use for your project.

## How to Use BPE Models

1. Download the BPE model file from the provided source.
2. Install the necessary dependencies for using BPE models in your project.
4. Tokenize your text using the BPE model to obtain subword units.
5. Use the subword units for further processing or analysis in your project.


## Example

You can install `subword-nmt` using pip. Open your terminal and run the following command:

```bash
pip install subword-nmt
```

```bash
echo "your text here" | subword-nmt apply-bpe -c path_to_your_model.model
```

The ctranslate2 model is available in HuggingFace

Here are the models for different language pairs:
- [English to Galician (en-gl)](https://huggingface.co/proxectonos/Nos_MT-OpenNMT-en-gl)
- [Spanish to Galician (es-gl)](https://huggingface.co/proxectonos/Nos_MT-OpenNMT-es-gl)
- [Basque to Galician (eu-gl)](https://huggingface.co/proxectonos/Nos_MT-OpenNMT-eu-gl)
- [Catalan to Galician (ca-gl)](https://huggingface.co/proxectonos/Nos_MT-OpenNMT-ca-gl)

To download and use these models, follow these steps:

1. Open the respective link for the desired language pair.
2. Download or clone the repository.
3. Install the necessary dependencies for using the models in your project.
4. Load the downloaded model using the ctranslate2 API as explained in the HuggingFace repository.
5. Use the loaded model for translation or other language-related tasks in your project (see documentation in HuggingFace).
