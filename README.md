# dialogue-summarization
in the folder data have 2 sub-folder: samsum and samsum_vi.

Samsum is the original dataset in English;

Samsum_vi is the dataset which translate to vietnamese but it already have 2 files about test and val. Because of the huge amount of the train sample so it will take more time to translate!

About 2 models for the testing part i suggest you should test on the huggigface's inference API here the link:

PEGASUS: https://huggingface.co/chamdentimem/pegasus-samsum

T5: https://huggingface.co/chamdentimem/pegasus-samsum

The PEGASUS is created for summarization tasks so it takes less time to train than the other one and the performace is more correctly!
