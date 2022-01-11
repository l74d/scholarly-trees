# scholar-trees

## Treebank from arXiv title and abstracts

Compared to Penn Treebank, this dataset is free to use while being substantially larger at 1.6M sentences rather than ~50k in Penn Treebank or variants.
This dataset would not be a good choice if you are looking to train the next best constituency parser or dependency parser, as it has NOT been manually edited.
However for tasks taking parse trees as input, like information extraction, you now have a much more stuff that you can play with right away, without rolling your own data processing pipeline.

Currently this repo contains 880k files and 294k directories (Warning: potential performance hazard if you clone this repo on Windows).
Best practice would be to use a (virtual) ReiserFS (which excels at handling extremely large number of small files) partition, although anywhere on a usual Linux machine should still suffice.

#Abstracts parsed by LAL-Parser: 294101
#Abstracts parsed by Stanford Parser: 294101
#Sentences parsed by Stanford Parser: 1606696
#Sentences parsed by Stanford Parser: 1606696
#Sentences in agreement by both parsers: 75601
