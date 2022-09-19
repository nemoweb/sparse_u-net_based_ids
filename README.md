# Solution approach
An unsupervised deep learning based approach for detecting DoS and DDoS attacks in a NIDS scenario. Basically, our solution includes two main stages: (i) a preprocessing phase in which correlated features are dropped and a number of additional features are created by applying non linear functions to the original input, (ii) an unsupervised learning phase in which a hybrid architecture combining Sparse AEs with U-Net-like models is trained only against legitimate traffic to reveal the presence of abnormal behaviors (possibly related to attacks). A Data Augmentation strategy is embedded in the neural architecture to mitigate the risk of overfitting and yield more reliable models.

## Dataset
The dataset can be found at [CICIDS17](https://www.unb.ca/cic/datasets/ids-2017.html).

## Authors

The code is developed and maintained by Nunziato Cassavia, Massimo Guarascio and Francesco Folino (nunziato.cassavia@icar.cnr.it, massimo.guarascio@icar.cnr.it , francesco.folino@icar.cnr.it)

## Environment details
complete me - @Nunzio

### Input details
The prototype requires two input variables in order to be executed i.e. the paths relative to the training and test set (csv format). The former one can be set by changing the value of the variable "training" (cell number 6 at row 2). The last one correspond to the variable "testset" (cell number 23 at row 3).
