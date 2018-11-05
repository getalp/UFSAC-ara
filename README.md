This repertory contains translation in Arabic language of the UFSAC corpora.

For OMSTI, you need to concatenate the files for each part. For instance,

with omsti_part0-ATB.ar.alignment_info.ar.post-proc.xml.xz-a and omsti_part0-ATB.ar.alignment_info.ar.post-proc.xml.xz-b you will get omsti_part0-ATB.ar.alignment_info.ar.post-proc.xml.xz

On Linux or MacOS: cat omsti_part0-ATB.ar.alignment_info.ar.post-proc.xml.xz-a omsti_part0-ATB.ar.alignment_info.ar.post-proc.xml.xz-b > omsti_part0-ATB.ar.alignment_info.ar.post-proc.xml.xz-a and omsti_part0-ATB.ar.alignment_info.ar.post-proc.xml.xz

Note that every corpus has been compressed using the tool xz and therefore needs to be decompressed with unxz or similar.
