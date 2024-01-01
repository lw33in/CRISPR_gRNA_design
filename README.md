# CRISPR/Cas9-mediated genomic deletions - gRNA design

- **Backbone plasmid**: pSpCas9(BB)-2A-Puro (PX459) V2.0 plasmid [Addgene #62988](https://www.addgene.org/62988/)
- **Genome Reference**: Homo sapiens UCSC Dec. 2013 [GRCh38/hg38](https://genome.ucsc.edu/cgi-bin/hgGateway)
- **gRNA design tool**: [CRISPOR](http://crispor.tefor.net/)

**Best practice for designing gRNAs for genomic deletion / gene knockout**:
  1. Target the promoter region of the gene of interest.
     - Priotize the dominant transcript for editing.
     
  2. dCas9-KRAB has the hightest editing efficiency at transcription start site (TSS) -50 to +300.
     - Design gRNAs every ~100 bp, ideally with gaps no bigger than 200bp.
     - An ideal indel is introduced as close as possible to the 5' end of the coding region as these indels have the highest likelihood of creating frameshifts.

  3. Design >=4 gRNAs candidates for evaluation.
     - Compare editing efficiencies, specificities, off-target numbers, etc.
     - Ideally, GC contents of gRNAs should be ~60% (40-80%).
       
  4. Use the USCS genome browser genes and gene predictions function to double-check the specificity of gRNAs.
  5. Ensure that the designed gRNAs will not affect the function of other genes or binding sites.
  6. Pay attention to the primers use for cloning gRNAs into the vectors during oligo synthesis.
     
<img width="551" alt="image" src="https://github.com/stephniw/CRISPR_gRNA_design/assets/120678930/35dab83f-bb30-4b76-b25e-d84cddedaf87">

Referece: W. Ni, A. A. Perez, S. Schreiner, C. M. Nicolet, and P. J. Farnham. Characterization of the ZFX family of transcription factors that bind downstream of the start site of CpG island promoters. Nucleic Acids Res, 2020. doi: 10.1093/nar/gkaa384.

<img width="540" alt="image" src="https://github.com/stephniw/CRISPR_gRNA_design/assets/120678930/7821ed7b-d54c-4bf4-b9c9-9947841d73c3">
<img width="540" alt="image" src="https://github.com/stephniw/CRISPR_gRNA_design/assets/120678930/3037e834-c7a8-4f39-9aac-3b1efb994615">
