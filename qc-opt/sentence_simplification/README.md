WikiLarge dataset comprises of 359 test sentences, 2000 development sentences and 300k training sentences. These are pairs of complex and simplified sentences. Each source sentences in test set has 8 simplified references. Refer the following for WikiLarge - https://github.com/XingxingZhang/dress. We have curated our labelled dataset where every source (complex) sentence has been prepended with 2 tokens indicating the BERTScore between that sentence and the target sentence in the dataset and the ration of number of tokens between the source and target sentences using the OpenAIÕs tiktoken tokeniser.

Example -

<BERTSCORE_0.95> <NUMTOKENSRATIO_0.8> Archaeological evidence
suggests a history of settlement in the area since roughly 2000 BC.

Archaeological evidence shows settlement in the area since 2000 BC.
