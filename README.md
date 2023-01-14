# Ai-paraphraserwriter
This code is an example of a hybrid approach to text summarization using AI. It uses a combination of the transformers library and GPT-2 to generate a summary of the given text. 

This code is using a hybrid approach to summarizing text by combining two different methods. The first method uses the transformers library to paraphrase the input text using the PegasusForConditionalGeneration model which is trained to generate a new text that is semantically similar to the input text. The second method uses the GPT-2 model from the transformers library to generate a summary of the paraphrased text.

The code starts by importing the necessary libraries and loading the PegasusForConditionalGeneration model and its corresponding tokenizer. Then it uses the nltk library to tokenize the input text into sentences. The number of returned sequences is set to the number of sentences in the input text.

The paraphrased text is then passed to the GPT-2 model to generate a summary. This is done by creating a TextGenerationPipeline from the transformers library and passing the paraphrased text and the desired number of words for the summary to the generate() method. The generated text is then cleaned up by replacing newline characters with a single space and removing any remaining backslashes.

Overall this code uses the transformer library and nltk library and uses a hybrid approach which includes paraphrasing input text using PegasusForConditionalGeneration model and generating summary using GPT-2 model.




