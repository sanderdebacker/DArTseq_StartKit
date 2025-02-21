# DArTseq_StartKit

## Windows WSL
Instructions for installation of Windows Subsystem for Linux:
https://www.supportyourtech.com/tech/how-to-install-ubuntu-on-windows-11-a-step-by-step-guide/

## Miniconda
Instructions for installation of Miniconda3:
https://docs.anaconda.com/miniconda/install/

Follow the instructions for Linux installation > Linux Terminal Installer > Linux x86

### DArTseq environment
> conda create -n dartseq python=3.10 --yes
> 
> conda activate dartseq
>
> conda install bioconda::fastqc --yes
>
> pip install multiqc
>
> conda install bioconda::bwa --yes
>
> conda install bioconda::samtools -yes
>
> conda install openjdk=8 --yes
>
> pip install gbprocess-ngs

Install different java versions with:
> sudo apt install openjdk-8-jre* openjdk-11-jdk-headless openjdk-11-jre-headless openjdk-17-jdk-headless openjdk-17-jre-headless

Command to find installation locations of different java versions:
> sudo update-alternatives --config java

## Download files
Download from here: https://drive.google.com/file/d/14l_7VuDb9aTMblp5sD_JjHcj0PZk-UVc/view?usp=sharing

