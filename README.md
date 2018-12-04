# Unlocking the Hidden Potential of Unstructuctured News Data with NLP

This repository provides Python codes and Jupyter Notebooks for the Dow Jones applied research paper "Unlocking the Hidden Potential of Unstructured News Data with NLP &mdash; Understanding Advanced Analytics through Real-World Case Studies".

<img src="http://hilpisch.com/images/dna_paper_cover.png" width="500">

To **download** the PDF version of the paper visit http://go.dowjones.com/dna-research-paper.

## Setup and Installation

The instructions that follow assume that you run a **Docker container** or a **cloud instance** with the latest version of Ubunutu (18.10 at the time of this writing).

The following assumes that you have set up a cloud instance (e.g. on DigitalOcean) and have used `ssh` to login as `root` or have started a Docker container locally. To start a Docker container locally e.g. execute on the shell:

    docker run -ti -h dnanlp -p 9999:9999 ubuntu:latest /bin/bash

Then on the shell of the Docker container or the cloud instance execute the following:

    wget http://hilpisch.com/nlp/setup_dna_nlp.sh
    bash setup_dna_nlp.sh

Follow the **instructions** of the script to e.g. provide a password for the Jupyter Notebook server.

After the installation, you can access the **Jupyter Notebook server** under

    http://localhost:9999

or

    http://CLOUD_IP_ADDRESS:9999

with your chosen password. Navigate via Jupyter to the code folder and open a notebook to get started.

## Disclaimer

All codes and Jupyter notebooks come with no representations or warranties, to the extent permitted by applicable law. The codes and Jupyter notebooks are for illustration purposes only.

## Company Information

© Dr. Yves J. Hilpisch \| The Python Quants GmbH

http://tpq.io \| team@tpq.io \|
http://twitter.com/dyjh \| http://pqp.io

**Python for Finance & Algorithmic Trading online trainings** \| http://training.tpq.io

**University Certificate Program in Python for Algorithmic Trading** \| http://certificate.tpq.io


