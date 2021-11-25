# Bioinformatics Minor - Homework 3

## [Google Colab (ядро Python)](https://colab.research.google.com/drive/1MDoUQhaweCdvfYOyaV3rp6o8NGopVq38?usp=sharing)

## [Google Colab (ядро R)](https://colab.research.google.com/drive/1I_HDWJl80VY-rJQhk-JOXFBfJrrWGPD1?usp=sharing)

## [Полный отчёт multiQC](/data/multiqc_report.html)

#### General Statistics
Sample Name |	% Dups |	% GC |	Length |	% Failed |	M Seqs
-|-|-|-|-|-
SRR3414629_1 |	52.6% |	49% |	65 bp |	18% |	21.1
SRR3414630_1 |	52.7% |	47% |	65 bp |	18% |	15.2
SRR3414631_1 |	54.5% |	49% |	65 bp |	18% |	24.2
SRR3414635_1 | 54.9%	| 49%	| 65 bp |	18% |	21.0
SRR3414636_1 |	54.4% |	49% |	65 bp |	18% |	20.3
SRR3414637_1 | 60.2%	| 47%	| 65 bp |	18% |	20.4

#### Sequence Quality Histograms
![](images/multiqc/fastqc_per_base_sequence_quality_plot.png)
#### Per Sequence Quality Scores
![](images/multiqc/fastqc_per_sequence_quality_scores_plot.png)
#### Per Sequence GC Content
![](images/multiqc/fastqc_per_sequence_gc_content_plot.png)
#### Sequence Duplication Levels
![](images/multiqc/fastqc_sequence_duplication_levels_plot.png)
#### Status Checks
![](images/multiqc/fastqc-status-check-heatmap.png)


## Статистика по образцам
ID | Type |	All reads number |	Aligned reads (% of all) |	Aligned 1 time (% of all) |	Reads on genes (% of all)
-|-|-|-|-|-
SRR3414629 |	reprogramming |	21 106 089 |	20 510 113 (97.18 %) |	18 375 888 (87.06 %) |	16 049 609 (76.04 %)
SRR3414630 |	reprogramming |	15 244 711 |	14 832 680 (97.30 %) |	13 186 139 (86.50 %) |	11 465 324 (75.21 %)
SRR3414631 |	reprogramming |	24 244 069 |	23 547 686 (97.13 %) |	20 928 945 (86.33 %) | 18 408 851 (75.93 %)
SRR3414635 | control	| 20 956 475	| 20 395 865 (97.32 %) |	18 428 317 (87.94 %) |	16 275 997 (77.67 %)
SRR3414636 | control |	20 307 147 |	19 757 059 (97.29 %) |	17 825 380 (87.78 %) |	15 757 580 (77.60 %)
SRR3414637 | control	| 20 385 570	| 19 847 291 (97.36 %) |	17 844 858 (87.54 %) |	15 736 978 (77.20 %)

## MA-plot
![](images/MA-plot.png)

## Heatmap
![](images/heatmap.png)


## Дифференциально экспрессированные гены (примеры)

##### ENSMUSG00000020758.15
![](images/ENSMUSG00000020758.15.png)

##### ENSMUSG00000037820.15
![](images/ENSMUSG00000037820.15.png)

##### ENSMUSG00000026413.12
![](images/ENSMUSG00000026413.12.png)

##### ENSMUSG00000074796.10
![](images/ENSMUSG00000074796.10.png)
