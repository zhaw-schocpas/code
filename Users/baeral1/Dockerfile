# Basis Container jupyter/minimal-notebook welcher bereits gepullt wurde
ARG BASE_CONTAINER=jupyter/minimal-notebook
FROM $BASE_CONTAINER
LABEL author="Schoch Pascal"
USER root
# Install python library
RUN pip install pandas numpy matplotlib plotly 
# Switch back to jovyan to avoid accidental container runs as root
USER $NB_UID