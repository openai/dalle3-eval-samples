# DALL-E 3 Evaluation Samples

This repository contains text-to-image samples collected for the evaluations of DALL-E 3 in the whitepaper. We provide samples not only from DALL-E 3, but from the competitors we compare against in the paper. 

The intent of this repository is to enable researchers in the text-to-image space to reproduce our results and foster forward progress of the text-to-image field as a whole. The samples from this repository are *not* meant to be demonstrations of the DALL-E 3 system.

## Structure

There are six directories in this repository:

### coco

Contains ~32,000 samples from each model derived from ~8,000 captions from the MSCOCO 2014 evaluation set. These samples are intended to be used for CLIP score calculation.

### drawbench

Contains 4 samples for each prompt from the [drawbench dataset](https://imagen.research.google/) for each model. In the paper, we evaluate these samples using GPT-4 with Vision and using human raters.

### drawbench_upsampled

Contains 4 samples for each prompt in our upsampled drawbench dataset, which was derived using the caption upsampling methodology described in the paper. We evaluate these samples using GPT-4 with Vision.

### prompts

Contains the prompts used to generate all of the samples in the other directories. Prompt files are simple text files. The order of the prompts in these files corresponds with the order of the respective image samples.

### t2i_compbench

Contains 4 samples for each prompt in the [T2I CompBench evaluation](https://github.com/Karine-Huang/T2I-CompBench). We use the scripts provided with that evaluation to measure the performance of the models in our comparison.
