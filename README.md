# bacterial_metagenomes_pangraphs
A workflow for complete analysis of bacterial metagenomes and pagenome graphs and direct viewing in panchae. It will also analyze metagenomes from both illumina and long reads. If you want in nextflow then leave a comment and i will code in nextflow, currently it runs on slurm and pbs plus docker instances. if you are running this on the slurm or the pbs then also you can run it directly. Adding the support for the singularity containers. soon will push a docker image. 

2023-10-19: updated with complete workflow and added support for snpcalling and others. Added support for the single command and it will connect with the slurm and pbs and will connect to the working directory and will end to end process the workflow. An in-addition array is added so that all the files are added.

In the follow updates, adding the support for: 
multiple pangenomes \
multi mappers \
graph creation \
pangenome construction \
long read assembly \
evolutionary analysis \
genome comparison 

python and R code will be intergated, plus ruby bindings and also a ruby on rails application for submission to the server plus docker release.   

This workflow is still in development and will be updated soon.

```
docker pull ubuntu-bacterial-pangraphs
```

Gaurav Sablok \
ORCID: https://orcid.org/0000-0002-4157-9405 \
WOS: https://www.webofscience.com/wos/author/record/C-5940-2014 \
RubyGems Published: https://rubygems.org/profiles/sablokgaurav \
Python Packages Published : https://pypi.org/user/sablokgaurav/
