# VCFSleuth-Workflow

### basicVCF2TSVConversion.sh
Written in bash, the basic script simply uses the vcf2tsv software to make a tsv of 
the vcf including all columns. It also makes another tsv with a line
for each sample the record was seen in. 

### VCF2TSVWorkflow.sh
Written in bash, my workflow script does a similar thing except that it does some post
processing. The vcf perSample is subset for our labs usual columns of
interest and samples/rows are filtered out if they are not carriers
of the alternate allele.
