# KafeenDiffStatistics
Generate data summary reports for and between Kafeen vcf output files

# To use this program:
  1. You will need to have SQLite3 (3.8.10.2) and bcftools (1.3.1-180) installed
  2. Download KafeenDiffStatistics to your local machine.
  3. There are two run options:
      1. Gather statistics on one file
        1. bash vcfComp.sh /path/to/yourfilename.vcf
      2. Gather statistics between two files
        1. bash vcfComp.sh /path/to/yourOldData.vcf /path/to/yourNewData.vcf

# Output
There will be several csv output files with the collected data that can be reviewed in excel.


