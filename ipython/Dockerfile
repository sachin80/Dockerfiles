FROM miniconda3
LABEL maintainer=@sagrawal
RUN conda update conda && \
	conda install --quiet --yes ipython && \
	conda clean -tipsy
CMD ["ipython"]
