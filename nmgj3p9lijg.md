| Format | Use | Standard | Validator | 
| ------ | ----- | ----- | ----- | 
| FASTA | Assembly Sequence Data | [NCBI standard](https://blast.ncbi.nlm.nih.gov/Blast.cgi?CMD=Web&PAGE_TYPE=BlastDocs&DOC_TYPE=BlastHelp) | perl::Bio |
| FASTQ | Raw Sequence Data | [standard](https://en.wikipedia.org/wiki/FASTQ_format) | fastqx |
| GFF3 | Genomic Feature Format | [Spec](https://github.com/The-Sequence-Ontology/Specifications/blob/master/gff3.md) [sequence ontology](http://www.sequenceontology.org) | [Todd Harris](https://github.com/kiwiroy/gff3_validator/tree/f/neaten) |
| BAM/SAM | Alignments |[Sequence Alignment/Map Format Specification](http://samtools.github.io/hts-specs/SAMv1.pdf) | [Picard](https://broadinstitute.github.io/picard/command-line-overview.html#ValidateSamFile) or [BamUtil](https://genome.sph.umich.edu/wiki/BamUtil:_validate)| 
| AGP | coordinates |[AGP Specification v2.0?](https://www.ncbi.nlm.nih.gov/assembly/agp/AGP_Specification/) |NCBI agp_validate | 
| YAML | Meta data | | | 