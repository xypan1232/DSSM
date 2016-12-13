# DSSM
DSSM is abbreviation for Deep Sequence-Structure Motifs, it trains deep learning models to infer binding sequence and structure motifs from sequences simultaneously.

Dependency <br>
<a href=https://github.com/fchollet/keras/>keras 1.1.2 library</a> <br>
<a href=https://github.com/scikit-learn/scikit-learn>sklearn</a> <br>
<a href=https://github.com/fabriziocosta/EDeN>EDeN</a> <br>
<a href=https://bibiserv.cebitec.uni-bielefeld.de/download/tools/rnashapes.html>RNAshapes</a> <br>

Content <br>
./datasets: the training and testing dataset with sequence and label indicating it is binding sites or not<br>
./seq_cnn: detected binding sequence motifs from DSSM. <br>
./structure_cnn: detected binding structure motifs from DSSM. <br>
./dssm.py: the python code, it can be ran to reproduce our results. <br>
./dssm_motif: the predicted sequence and structure motifs from DSSM.

Contact: Xiaoyong Pan (xypan172436atgmail.com)