pair_or_item,database,evidence,organism,reference,what_it_supports,caveat
PRL expression in pituitary endocrine cells,HPA,"Secreted protein; RNA cell-type enriched in pituitary endocrine cells (Tau 0.95, ~22000 nCPM); protein-level evidence",Homo sapiens,https://www.proteinatlas.org/,PRL is produced by the sender cell,Expression does not prove secretion or signaling in my chosen cells
PRLR expression in mammary cells,HPA,"Strongest PRLR signal is NOT mammary (enhanced in choroid plexus, parathyroid, placenta; breast luminal lower)",Homo sapiens,https://www.proteinatlas.org/,DISAGREEMENT with my receiver choice,Receiver choice rests on literature
PRL-PRLR,OmniPath,"Ligand-receptor annotation; 45 references (CellPhoneDB, CellChatDB, CellCall +31); PMIDs 2558309, 7984244, 9626554",Homo sapiens,https://explore.omnipathdb.org/,PRL signals through PRLR,General database; not cell-type specific
PRLR-JAK2,OmniPath,10 references,Homo sapiens,https://explore.omnipathdb.org/,PRLR activates JAK2,General database; not cell-type specific
JAK2-STAT5A,OmniPath,47 references,Homo sapiens,https://explore.omnipathdb.org/,JAK2 acts on STAT5A,General database; not cell-type specific
SOCS3 / CISH,OmniPath,Stimulation arrows shown,Homo sapiens,https://explore.omnipathdb.org/,Possible induced feedback proteins,Classically feedback inhibitors; feedback role is my inference
PRL regulators (POU1F1/STAT5A/ETS1/JUN/FOS),OmniPath,Regulators of PRL expression,Homo sapiens,https://explore.omnipathdb.org/,Not part of my pathway,Excluded from model
STRING network,STRING,"7 proteins (PRL, PRLR, JAK2, STAT5A, STAT5B, SOCS3, CISH); 21 edges; JAK2 central",Homo sapiens,https://string-db.org/,Functional associations among my chosen proteins,Edge is not direct binding; I chose the proteins so p<1e-16 is not independent confirmation
JAK-STAT regulation (GO:0046425),STRING,FDR 8.4e-08,Homo sapiens,https://string-db.org/,Enriched process consistent with mechanism,Enrichment of a hand-picked set
Lactation (GO:0007595),STRING,FDR 9.6e-07,Homo sapiens,https://string-db.org/,Enriched process consistent with expected response,Enrichment of a hand-picked set
Mammary gland development (GO:0030879),STRING,FDR 6.6e-07,Homo sapiens,https://string-db.org/,Enriched process consistent with receiver tissue,Enrichment of a hand-picked set
PRL-PRLR,IntAct,"direct interaction; circular dichroism (EBI-15968354) and NMR (EBI-15968373); in vitro; PRLR region 1-210",Homo sapiens,PMID 22325776 (Dagil et al. 2012),Direct PRL-PRLR binding at molecular level,One study (cd and nmr rows same paper); purified proteins; not shown in mammary cells
PRL-PRLR (isoform P16471-7),IntAct,"direct interaction / physical association; anti bait co-IP and PLA; in vitro; MI score 0.61",Homo sapiens,PMID 23048206 (Fleming et al. 2013),Additional support for PRL-PRLR,Paper focuses on a PRL-binding protein (delta-7/11); PRLR isoform; support only
PRLR-JAK2,IntAct,No record found in human P16471 search,Homo sapiens,https://www.ebi.ac.uk/intact/,None,No record found is not no interaction
PRLR-STAT5A,IntAct,No record found in human P16471 search,Homo sapiens,https://www.ebi.ac.uk/intact/,None,No record found is not no interaction
PRLR-CISH,IntAct,No record found in human P16471 search,Homo sapiens,https://www.ebi.ac.uk/intact/,None,No record found is not no interaction
PRLR-YWHAZ,IntAct,"pull down; physical association",Homo sapiens,PMID 12819209,Association only,Not on my main pathway
