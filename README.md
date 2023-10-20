# promoter_emergence_mobile_DNA
A repository for the data and scripts from our manuscript: "Mobile DNA is replete with hotspots for the de novo emergence of gene regulation."

The raw sequencing reads from the deep mutational scanning experiment are available on the Sequence Read Archive (SRA) at the following link: https://www.ncbi.nlm.nih.gov/sra/PRJNA1021969 or with Project Accession Number: PRJNA1021969.

To reproduce the figures and analysis in the text, we provide a Jupyter notebook in the "data" folder. To run these python scripts, download the "data" folder and run the scripts in Jupyter. The "data" folder also contains a list of requirements to create an Anaconda environment called "requirements.txt". For the most reproducible results, we encourage you to run the scripts with the provided environment.

To create the Anaconda environment, create a new envirnoment: 
conda install -n <env_name> requirements.txt

You can also manually download the packages listed within "requirements.txt" if this does not work.
