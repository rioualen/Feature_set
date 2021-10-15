README

Defined TSS, TTS and TU based on the study of DOI: 10.1038/s41467-018-05997-6

All the files have 0-coordination.

The reference genome used for analysis:
NC_000913.3 Escherichia coli str. K-12 substr. MG1655, complete genome

The annoation used for analysis:
GCF_000005845.2_ASM584v2_genomic.gene.gff


1. TSS annotation files
M9_RegulonDB_TSS (2186 entries)
Rich_RegulonDB_TSS (1902 entries)

2. TTS annoation files
M9_RegulonDB_TTS (408 entries)
Rich_RegulonDB_TTS (455 entries)

Note:
TTS is defined as significant accumulation of reads (at least 20% from TSS). See our manuscript for details.

Currently I do not have all the information required for the TTS structure.
Instead, I list the useful information that I can provide:
Free Energy (∆G(kcal/mol) is calculated using 40bp RNA upstream of TTS position with tool RNAstructure version 5.8.1 (doi: 10.1002/0471250953.bi1206s13).

I compare our result with the existing Terminator listed in RegulonDB Terminator Set (release 9.3 Date: 02-14-2017, having 282 known sites) as shown in column knownTerminator. NA means that no known termination site.

3. TU annotation files

M9_RegulonDB_TU_definedEnd (389 entries)
Rich_RegulonDB_TU_definedEnd (423 entries)
M9_RegulonDB_TU_longestRead (2077 entries)
Rich_RegulonDB_TU_longestRead (1797 entries)

Note:
TU is defined by either (1) a defined TSS and TTS pair or (2) the longest read from a defined TSS.
The genes listed in column Name_covered_genes are ordered from 5'end to 3'end.
In addition to all the information required, I add another two columns describing the fraction of most 5'end or 3'end gene coverted by our defined TU. If the fraction<1.0, means the TU starts or terminates in the middle of a gene.