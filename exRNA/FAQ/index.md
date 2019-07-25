# FAQ for exRNA

## exRNA: extra-cellular RNA

#### How many types of exRNAs?

**exRNA** (extra-cellular RNA) includes long and short RNAs, which can be derived from the whole plamsa/serum (called cell -free RNA, **cf-RNA**), or enriched from the exosomes/EVs of plasma/serum (called **exoRNA**).

* long RNA: mRNA, lncRNA
* small RNA: miRNA, piRNA, siRNA
* ohter RNA: rRNA, tRNA, Y RNA, snRNA, snoRNA, srp RNA, etc

## RNA-seq

#### What is TSO?

**Answer:** The TSO (template switch oligo) is an oligo that hybridizes to untemplated C nucleotides added by the reverse transcriptase during reverse transcription. The TSO adds a common 5' sequence to full length cDNA that is used for downstream cDNA amplification.

The TSO is used differently in the Single Cell 3' assay compared to the Single Cell 5' assay. In the 3' assay, the polyd(T) sequence is part of the gel bead oligo (which also contains the 10x Barcode, UMI, and partial Illumina Read 1 sequence), with the TSO supplied in the RT Primer. In the 5' assay, the polyd(T) is supplied in the RT Primer, and the TSO is part of the gel bead oligo.


Single Cell 3' assay after reverse transcription:


![TSO-3](TSO-3.png)

 

Single Cell 5' assay after reverse transcription:

![TSP-5](TSO-5.png)

Products: Single Cell 3', VDJ


> See more in [PDF](TSO.pdf) or [Web](https://kb.10xgenomics.com/hc/en-us/articles/360001493051-What-is-a-template-switch-oligo-TSO-)



#### What is UMI?

#### What is barcode and multiplex?

