The tool kit contain GSGBN and the datasets for GSGBN paper which was submitted to ICDM 2014 for peer review.

Exract the package, then use make to compile the source code.
$ tar -xvzf GSGBN-0.1.tar.gz
$ make

Usage:
    GSGBN -i input.txt -l1 1.0 -l2 0.1 -num 10 -thr 0.1
Options:
    -i,   an m * n matrix with m samples and n variables;
    -l1,  the regularization parameter lambda1 for sparsity;
    -l2,  the regularization parameter lambda2*n is used for grouping;
    -num, number of rounds for enumerating DAGs;
    -thr, threshold for filtering
