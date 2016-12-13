# dna2proteins
This is an adaptation of https://github.com/prestevez/dna2proteins which outputs all protein sequences instead of the best one. I take no credit for writing the code.

Within this project there are two codes; 
1. dna2proteins.py which outputs all 6 frame version of your fasta to stdout 
2. 6wat_output.py which allows you to provide an output pattern which will be used to produce 6 output files, one for each frame


To use it type;

python dna2proteins.py -i FILE > OUTPUT

python 6way_output.py -i FILE -o OUTPUT
