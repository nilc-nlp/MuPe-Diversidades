# MuPe-Diversidades
MuPe-Diversidades is a diverse selection of samples of audios in Brazilian Portuguese, extracted from CORAA MuPe ASR, and their respective transcriptions with prosodic segmentation annotation. It includes samples of speech of approximately 10 minutes for each state, around 5 minutes for each speaker from a singular state, who are diverse in gender and age.


**Version-0**

Includes anonymized audios and transcriptions with automatic prosodic segmentation annotation

Note: audios were cut every 30 seconds automatically at pre-processing steps and put back together, which was found to jeopardize the quality of prosodic segmentation annotation, so version 1.0 will soon be available with the correction of the problem


**Version 1.0**

Audios without cuts 

With manual review of the prosodic segmentation annotation

Note: Speaker 0 is always the interviewee, and the other speakers are different interviewers. However, it was necessary to correct  PA1, PA2, RJ1, RO1, SE1 by inverting names of tiers of speaker 0 and speaker 1, as when we first made all files available,speakers 0 and 1 were inverted in those cases. Version 0 (obsolete) continues with speakers 0 and 1 not inverted.

The following table presents characteristics from the speakers whose voice is included in MuPe-Diversidades

![Captura de tela de 2025-03-18 15-03-04](https://github.com/user-attachments/assets/639cfd79-b8af-45ab-b7f9-07948f5610b3)

Table 1: Characteristics of the speakers, whose interviews/life storys form MuPe-Diversidades. The table contains information about each interviewee (first column presents the Story ID in our dataset), including sex (S) (M:male, F:female), region/state of origin,indicated by its abbreviation (PA stands for Pará, MG for Minas Gerais, PE for Pernambuco, RJ for Rio de Janeiro, RO for Rondônia, RS for Rio Grande do Sul, PB for Paraíba, AL for Alagoas, GO for Goiás, PI for Piauí, MS for Mato Grosso do Sul, ES for Espírito Santo, SE for Sergipe, and SP for São Paulo;) city of origin, year of birth (YOB), and education level. Given the nature
of this data, which was collected through the interview, one information about YOB is lacking, which is marked with "unk" (date of the interview) for "unknown".

# Sponsors / Funding

This work was carried out at the Center for Artificial Intelligence (C4AI-USP), with support by the São Paulo Research Foundation (FAPESP grant #2019/07665-4) and by the IBM Corporation. This project was also supported by the Ministry of Science, Technology and Innovation, with resources of Law No. 8.248, of October 23, 1991, within the scope of PPI-SOFTEX, coordinated by Softex and published Residence in TIC 13, DOU 01245.010222/2022-44.


# Citation

```
@InProceedings{Craveiro2024Bracis,
author= {Craveiro, Giovana Meloni
and Galdino, Julio Cesar},
editor={Paes, A.
and Verri, F.A.N.},
title={Diversity in Data for Speech Processing in {B}razilian Portuguese},
booktitle={Intelligent Systems: 34th Brazilian Conference, Bracis 2024, Bel{\'e}m Do Par{\'a}, Brazil, November 17-21, 2024, Proceedings, Part I},
year={2025},
publisher={Springer Nature Switzerland},
isbn={9783031790287},
url={https://books.google.com.br/books?id=g_n90AEACAAJ}
}

```


# CORAA MUPE ASR

Available at: https://huggingface.co/datasets/nilc-nlp/CORAA-MUPE-ASR
