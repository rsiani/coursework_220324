# coursework_220324

## 1. Inspect your Sanger Trace (.ab1) file

This can be done on a variety of tool (locally or online).

https://www.gear-genomics.com/teal/ this is online

https://labsquare.github.io/CutePeaks/ this you can download and has a bit more features

Remember to check both forward and reverse and trim at need. 

## 2. Reverse-complement the reverse read

16S are long and shady. Just a forward read doens't quite get you there with confidence. 
So we sequence both wasy to have better quality coverage. 

We can use https://www.ebi.ac.uk/jdispatcher/sfc

Look for emboss_seqret

## 3. Pairwise alignment

Same website. There is diffrent one you can use (MSA are also fine generally speaking). 

https://www.ebi.ac.uk/jdispatcher/psa

## 4. Merge

We want to generate a consensus sequence to get a better taxonomic inference

https://www.ebi.ac.uk/jdispatcher/msa/emboss_cons

## 5. Find your suspect

We can use good old blast for that

https://blast.ncbi.nlm.nih.gov/Blast.cgi?PROGRAM=blastn&PAGE_TYPE=BlastSearch&LINK_LOC=blasthome

or directly on SILVA

https://www.arb-silva.de/

This is also a cool website to look at environmental distribution of the subject

https://microbeatlas.org/

Once you have taxonomic info, you can also search on BacDive for more phenotypical infos

https://bacdive.dsmz.de/

also

https://omnicrobe.migale.inrae.fr/

## 6. Phylogenetic tree

You can either download the alignment directly from NCBI, or select a few sequences and make a new one. Then make a tree out of it and download it for viz

https://www.ebi.ac.uk/jdispatcher/phylogeny/simple_phylogeny

Finally, you can head iTOL to view and edit your tree 

https://itol.embl.de 

