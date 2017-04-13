# Base Image
FROM biocontainers/biocontainers:latest

# Metadata
LABEL base.image="biocontainers:latest"
LABEL version="1"
LABEL software="htseq-count"
LABEL software.version="0.6.1"
LABEL description="Given a file with aligned sequencing reads and a list of genomic features, count how many reads map to each feature."
LABEL website="http://www-huber.embl.de/users/anders/HTSeq/"
LABEL documentation="http://www-huber.embl.de/users/anders/HTSeq/"
LABEL license="https://sourceforge.net/p/htseq/code/HEAD/tree/trunk/LICENSE"
LABEL tags="Genomics"

# Maintainer
MAINTAINER Kenneth Daily <kenneth.daily@sagebase.org>

RUN conda install -c bioconda htseq=0.6.1

WORKDIR /data/

CMD ["htseq-count"]
