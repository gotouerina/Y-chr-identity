# Y-chr-identity

用于从组装好的染色体中鉴别哪条是Y

# Method1 BLAST genes (关键基因比对)

    conda install -c bioconda blast
    
# Method2 Quotient (male/female illumina reads + male Genome)
    
    git clone https://github.com/brantleyhall/Chromosome-Quotient.git
    
# Method3 DiscoverY (female reads + male Genome)

    git clone https://github.com/makovalab-psu/DiscoverY
