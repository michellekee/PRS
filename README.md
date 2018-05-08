# PRS
Scripts for PRS


spark-submit PRS_run.py IndianForPRS.dosages.vcf pgc_mdd_full_no_header.txt --GWAS_no_header PRS-MDD-IndianForPRSdosages --sample_file Indian.sample --sample_file_ID 0 --sample_file_skip 2 --sample_file_delim " "  --gwas_id 0 --gwas_p 7 --gwas_or 5 --gwas_a1 3 --gwas_a2 4 --gwas_a1f 10 --snp_log  --no_maf --log_or --thresholds 0.2 0.1 0.05







PRS-resilience

spark-submit PRS_run.py ChineseForPRS.vcf GWAS_Resilience_clumpByShantala_noambi.txt PRS-resilienceChinese --no_maf --sample_file Chinese.sample --thresholds 0.2 0.1 0.05 --snp_log --GWAS_delim "\t" --sample_file_skip 2 --sample_file_delim " "

PRS-Nirmala (BR-MDD)

spark-submit PRS_run.py PFC_DEG_3_humanGenePos_AllEthnicIntersection.txt GWAS_pgc.mdd.clump.2012-04.txt PRS-PFC-DEG --sample_file AllEthnic.samples --sample_file_ID 0 --sample_file_skip 2 --sample_file_delim " " --gwas_id 0 --gwas_p 1 --gwas_or 2 --gwas_a1 3 --gwas_a2 4 --GWAS_delim "\t" --snp_log --no_maf --threshold_seq 0.01 1.00 0.01 --filetype GEN



PRS-Nirmala(Anx)

spark-submit PRS_run.py ChineseForPRS.vcf GWAS_Amygdala.txt PRS-Anx_Amygdala_Chinese —sampe_file Chinese.sample —sample_file_ID 0 —sample_file_skip 2 —sample_file_dlim “ “ —gwas_id 0 —gwas_p 8 —gwas_a1f 5 —gwas_or 6—snp_log —no_maf —thresholds 0.2 0.1 0.05


PRS-ASD (WorldWide - Mar 2016)

spark-submit PRS_run.py AllEthnicIntersection.vcf PGC-ASD-WW-Mar2016.txt PRS-ASD-AllEthnicIntersection --sample_file AllEthnic.samples --sample_file_ID 0 --sample_file_skip 2 --sample_file_delim " " --gwas_id 2 --gwas_p 10 --gwas_or 5 --gwas_a1 3 --gwas_a2 4 --gwas_a1f 11 --GWAS_delim "\t" --GWAS_no_header --snp_log --no_maf --log_or --thresholds 0.5 0.4 0.3 0.2 0.1 0.05

PRS-Depressive Symptomms 

spark-submit PRS_run.py AllEthnicIntersection.vcf DS_Full.txt PRS-DepSymp-AllEthnicIntersection --sample_file AllEthnic.samples --sample_file_ID 0 --sample_file_skip 2 --sample_file_delim " " --gwas_id 0 --gwas_p 8 --gwas_or 6 --gwas_a1 3 --gwas_a2 4 --gwas_a1f 5 --GWAS_delim "\t" --snp_log --no_maf --thresholds 0.5 0.4 0.3 0.2 0.1 0.05


PRS-EA

spark-submit PRS_run.py AllEthnicIntersection.vcf EduYears_Discovery_5000.txt PRS-EA-Dis-AllEthnicIntersection --sample_file AllEthnic.samples --sample_file_ID 0 --sample_file_skip 2 --sample_file_delim " " --gwas_id 0 --gwas_p 8 --gwas_or 6 --gwas_a1 3 --gwas_a2 4 --gwas_a1f 5 --GWAS_delim "\t" --snp_log --no_maf --thresholds 0.5 0.4 0.3 0.2 0.1 0.05



PRS-ADHD-LC

spark-submit PRS_run.py AllEthnicIntersection.vcf GWAS_ADHD_zscore_withaf_full_noambi_Lawrence_custom171129.txt PRS-ADHD-LC-AllEthnicIntersection --sample_file AllEthnic.samples --sample_file_ID 0 --sample_file_skip 2 --sample_file_delim " " --GWAS_delim "\t" --threshold_seq 0.01 1.00 0.01 --no_maf --snp_log



PRS-MDD-Han

spark-submit PRS_run.py AllEthnicIntersection.vcf GWAS_MDD_Han_clumped.txt PRS-MDD-Han-AllEthnicIntersection --sample_file AllEthnic.samples --sample_file_ID 0 --sample_file_skip 2 --sample_file_delim " " --GWAS_delim "\t" --threshold_seq 0.01 1.00 0.01 --no_maf --snp_log --gwas_id 0 --gwas_p 1 --gwas_or 2 --gwas_a1 3 --gwas_a2 4 --gwas_a1f 5 --log_or


