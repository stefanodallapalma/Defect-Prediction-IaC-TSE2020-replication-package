# RQ2 - Effect of Metric Sets

## IaC-Oriented (ICO)

|       |     roc_auc |   std_roc_auc |     pr_auc |   std_pr_auc |   precision |   std_precision |     recall |   std_recall |         f1 |      std_f1 |        mcc |    std_mcc |
|:------|------------:|--------------:|-----------:|-------------:|------------:|----------------:|-----------:|-------------:|-----------:|------------:|-----------:|-----------:|
| count | 104         |   104         | 104        |  104         | 104         |      104        | 104        |   104        | 104        | 104         | 104        | 104        |
| mean  |   0.96139   |     0.0628438 |   0.896177 |    0.134857  |   0.820771  |        0.210808 |   0.882682 |     0.171308 |   0.825393 |   0.185108  |   0.804064 |   0.206613 |
| std   |   0.0505268 |     0.0603968 |   0.142529 |    0.0993133 |   0.178554  |        0.105477 |   0.13376  |     0.110481 |   0.169437 |   0.0957933 |   0.179924 |   0.117089 |
| min   |   0.744257  |     0         |   0.234347 |    0         |   0.0645545 |        0        |   0.111111 |     0        |   0.117409 |   0         |   0.123137 |   0        |
| 25%   |   0.953339  |     0.0153832 |   0.863208 |    0.0500996 |   0.778464  |        0.150836 |   0.849671 |     0.103499 |   0.781475 |   0.126076  |   0.757327 |   0.136676 |
| 50%   |   0.979206  |     0.0491723 |   0.943311 |    0.134556  |   0.875     |        0.209048 |   0.916808 |     0.169318 |   0.868519 |   0.184541  |   0.853008 |   0.192544 |
| 75%   |   0.993985  |     0.0911975 |   0.981917 |    0.196679  |   0.93227   |        0.272856 |   0.961218 |     0.220839 |   0.929046 |   0.228883  |   0.921408 |   0.25745  |
| max   |   1         |     0.311805  |   1        |    0.389899  |   1         |        0.471405 |   1        |     0.5      |   1        |   0.436436  |   1        |   0.640095 |
<br>

## Total

|       |     roc_auc |   std_roc_auc |     pr_auc |   std_pr_auc |   precision |   std_precision |     recall |   std_recall |         f1 |     std_f1 |        mcc |    std_mcc |
|:------|------------:|--------------:|-----------:|-------------:|------------:|----------------:|-----------:|-------------:|-----------:|-----------:|-----------:|-----------:|
| count | 102         |   102         | 102        |  102         |  102        |      102        | 102        |   102        | 102        | 102        | 102        | 102        |
| mean  |   0.952805  |     0.0701908 |   0.874779 |    0.142161  |    0.771883 |        0.232233 |   0.836295 |     0.205005 |   0.766808 |   0.20751  |   0.741107 |   0.229799 |
| std   |   0.0595484 |     0.0705157 |   0.156831 |    0.105553  |    0.207766 |        0.113468 |   0.16259  |     0.124031 |   0.199233 |   0.103259 |   0.210818 |   0.120869 |
| min   |   0.65      |     0         |   0.1406   |    0         |    0        |        0        |   0        |     0        |   0        |   0        |  -0.012241 |   0        |
| 25%   |   0.943678  |     0.0185465 |   0.814713 |    0.0505291 |    0.700823 |        0.171395 |   0.778488 |     0.132397 |   0.683552 |   0.155491 |   0.656272 |   0.166542 |
| 50%   |   0.972358  |     0.0541799 |   0.929638 |    0.139621  |    0.824876 |        0.229954 |   0.886411 |     0.214802 |   0.82198  |   0.202652 |   0.797233 |   0.230491 |
| 75%   |   0.993139  |     0.0962699 |   0.983523 |    0.218235  |    0.916464 |        0.302955 |   0.943493 |     0.275497 |   0.900736 |   0.260649 |   0.885245 |   0.280589 |
| max   |   1         |     0.35      |   1        |    0.4375    |    1        |        0.471405 |   1        |     0.484123 |   1        |   0.471405 |   1        |   0.671855 |
<br>

## ICO-Process

|       |     roc_auc |   std_roc_auc |     pr_auc |   std_pr_auc |   precision |   std_precision |     recall |   std_recall |         f1 |     std_f1 |        mcc |    std_mcc |
|:------|------------:|--------------:|-----------:|-------------:|------------:|----------------:|-----------:|-------------:|-----------:|-----------:|-----------:|-----------:|
| count | 104         |   104         | 104        |  104         | 104         |      104        | 104        |   104        | 104        | 104        | 104        | 104        |
| mean  |   0.953959  |     0.0704179 |   0.879565 |    0.144237  |   0.800529  |        0.231174 |   0.853817 |     0.197722 |   0.791935 |   0.206713 |   0.769806 |   0.228004 |
| std   |   0.0589396 |     0.0698318 |   0.151229 |    0.105648  |   0.176104  |        0.113438 |   0.141471 |     0.114502 |   0.175289 |   0.100217 |   0.18319  |   0.118988 |
| min   |   0.65      |     0         |   0.247201 |    0         |   0.0719424 |        0        |   0.111111 |     0        |   0.130089 |   0        |   0.143853 |   0        |
| 25%   |   0.941347  |     0.0180165 |   0.827257 |    0.0506538 |   0.715625  |        0.165359 |   0.786678 |     0.129407 |   0.712777 |   0.145746 |   0.677521 |   0.164042 |
| 50%   |   0.974413  |     0.057573  |   0.939891 |    0.140144  |   0.855987  |        0.239619 |   0.902365 |     0.187046 |   0.832888 |   0.200119 |   0.816357 |   0.212721 |
| 75%   |   0.992714  |     0.0927423 |   0.98456  |    0.224778  |   0.923077  |        0.293711 |   0.949038 |     0.270262 |   0.913304 |   0.260753 |   0.903903 |   0.281356 |
| max   |   1         |     0.35      |   1        |    0.4375    |   1         |        0.471405 |   1        |     0.473853 |   1        |   0.439978 |   1        |   0.612372 |
<br>

## ICO-Delta

|       |     roc_auc |   std_roc_auc |     pr_auc |   std_pr_auc |   precision |   std_precision |     recall |   std_recall |         f1 |      std_f1 |          mcc |    std_mcc |
|:------|------------:|--------------:|-----------:|-------------:|------------:|----------------:|-----------:|-------------:|-----------:|------------:|-------------:|-----------:|
| count | 104         |   104         | 104        |  104         |  104        |     104         | 104        |   104        | 104        | 104         | 104          | 104        |
| mean  |   0.957652  |     0.0666202 |   0.890054 |    0.134908  |    0.79573  |       0.213191  |   0.874314 |     0.17977  |   0.801815 |   0.189062  |   0.778985   |   0.212066 |
| std   |   0.0572445 |     0.0670645 |   0.147929 |    0.0995073 |    0.201184 |       0.0991938 |   0.134431 |     0.109534 |   0.187114 |   0.0901415 |   0.196573   |   0.113541 |
| min   |   0.65      |     0         |   0.194039 |    0         |    0        |       0         |   0        |     0        |   0        |   0         |  -0.00859831 |   0        |
| 25%   |   0.947718  |     0.0185132 |   0.844936 |    0.0521654 |    0.733063 |       0.143782  |   0.848527 |     0.115171 |   0.749295 |   0.137153  |   0.706289   |   0.140954 |
| 50%   |   0.978202  |     0.0490112 |   0.938393 |    0.131309  |    0.869318 |       0.218719  |   0.905757 |     0.189517 |   0.866667 |   0.192074  |   0.833944   |   0.20944  |
| 75%   |   0.99322   |     0.0961358 |   0.981141 |    0.209698  |    0.921592 |       0.282691  |   0.952635 |     0.245889 |   0.922857 |   0.251075  |   0.915437   |   0.27205  |
| max   |   1         |     0.35      |   1        |    0.4375    |    1        |       0.444444  |   1        |     0.451754 |   1        |   0.392677  |   1          |   0.533594 |
<br>

## Process

|       |     roc_auc |   std_roc_auc |      pr_auc |   std_pr_auc |   precision |   std_precision |      recall |   std_recall |          f1 |     std_f1 |         mcc |    std_mcc |
|:------|------------:|--------------:|------------:|-------------:|------------:|----------------:|------------:|-------------:|------------:|-----------:|------------:|-----------:|
| count | 104         |    104        | 104         |   104        | 104         |      104        | 104         |   104        | 104         | 104        | 104         | 104        |
| mean  |   0.589846  |      0.17059  |   0.343591  |     0.194304 |   0.208335  |        0.243182 |   0.325766  |     0.294636 |   0.198421  |   0.199605 |   0.0837342 |   0.212797 |
| std   |   0.0834978 |      0.080789 |   0.207216  |     0.106216 |   0.162347  |        0.140001 |   0.242923  |     0.172062 |   0.16712   |   0.12493  |   0.127574  |   0.140833 |
| min   |   0.435819  |      0        |   0.0140039 |     0        |   0         |        0        |   0         |     0        |   0         |   0        |  -0.12499   |   0        |
| 25%   |   0.530158  |      0.114705 |   0.184219  |     0.117751 |   0.0835507 |        0.148266 |   0.0800245 |     0.133872 |   0.0658653 |   0.115848 |   0.0112421 |   0.118918 |
| 50%   |   0.569374  |      0.164781 |   0.31316   |     0.184987 |   0.176637  |        0.256543 |   0.364369  |     0.34748  |   0.175902  |   0.184777 |   0.0589315 |   0.183143 |
| 75%   |   0.632424  |      0.222698 |   0.492417  |     0.270299 |   0.310838  |        0.357485 |   0.509007  |     0.456612 |   0.28621   |   0.296656 |   0.124378  |   0.329161 |
| max   |   0.946429  |      0.440698 |   0.964286  |     0.472954 |   0.839286  |        0.481046 |   1         |     0.5      |   0.845238  |   0.481046 |   0.821429  |   0.715819 |
<br>

## Process-Delta

|       |     roc_auc |   std_roc_auc |     pr_auc |   std_pr_auc |   precision |   std_precision |     recall |   std_recall |          f1 |     std_f1 |         mcc |    std_mcc |
|:------|------------:|--------------:|-----------:|-------------:|------------:|----------------:|-----------:|-------------:|------------:|-----------:|------------:|-----------:|
| count | 104         |    104        | 104        |   104        | 104         |      104        | 104        |   104        | 104         | 104        | 104         | 104        |
| mean  |   0.590446  |      0.172017 |   0.347988 |     0.191981 |   0.211341  |        0.244212 |   0.319874 |     0.300938 |   0.200385  |   0.201894 |   0.0910396 |   0.215699 |
| std   |   0.0951607 |      0.081974 |   0.214382 |     0.108428 |   0.169708  |        0.137543 |   0.232929 |     0.167253 |   0.168734  |   0.126015 |   0.135718  |   0.138281 |
| min   |   0.392857  |      0        |   0.014371 |     0        |   0         |        0        |   0        |     0        |   0         |   0        |  -0.173205  |   0        |
| 25%   |   0.528673  |      0.106411 |   0.188093 |     0.121386 |   0.0739583 |        0.160202 |   0.070472 |     0.146677 |   0.0623576 |   0.120308 |   0.0137264 |   0.112984 |
| 50%   |   0.580164  |      0.163942 |   0.31239  |     0.179998 |   0.173463  |        0.252701 |   0.338557 |     0.375577 |   0.17942   |   0.194891 |   0.0628137 |   0.196434 |
| 75%   |   0.620898  |      0.232212 |   0.499886 |     0.262319 |   0.316633  |        0.356051 |   0.510174 |     0.437197 |   0.306623  |   0.303148 |   0.140553  |   0.323678 |
| max   |   0.946429  |      0.391015 |   0.964286 |     0.472954 |   0.875     |        0.49793  |   0.892857 |     0.5      |   0.880952  |   0.49793  |   0.857143  |   0.642824 |
<br>

## Delta

|       |     roc_auc |   std_roc_auc |      pr_auc |   std_pr_auc |   precision |   std_precision |      recall |   std_recall |          f1 |      std_f1 |         mcc |     std_mcc |
|:------|------------:|--------------:|------------:|-------------:|------------:|----------------:|------------:|-------------:|------------:|------------:|------------:|------------:|
| count | 104         |   104         | 104         |  104         | 104         |     104         | 104         |  104         | 104         | 104         | 104         | 104         |
| mean  |   0.5617    |     0.149992  |   0.315072  |    0.169037  |   0.17919   |       0.235197  |   0.221786  |    0.249167  |   0.156884  |   0.185232  |   0.0775304 |   0.197348  |
| std   |   0.0929972 |     0.079487  |   0.209679  |    0.10309   |   0.161212  |       0.15331   |   0.221248  |    0.166619  |   0.156533  |   0.133637  |   0.128956  |   0.13594   |
| min   |   0.207692  |     0         |   0.0142328 |    0         |   0         |       0         |   0         |    0         |   0         |   0         |  -0.246324  |   0         |
| 25%   |   0.506178  |     0.0898039 |   0.164406  |    0.0983368 |   0.0467084 |       0.0974736 |   0.0296717 |    0.0869605 |   0.0370366 |   0.0811493 |   0         |   0.0992101 |
| 50%   |   0.544354  |     0.134629  |   0.295572  |    0.152197  |   0.135621  |       0.284232  |   0.174679  |    0.258026  |   0.111028  |   0.172441  |   0.0531619 |   0.18637   |
| 75%   |   0.585041  |     0.208573  |   0.43466   |    0.239549  |   0.274337  |       0.350847  |   0.328729  |    0.38521   |   0.209648  |   0.278322  |   0.111307  |   0.280681  |
| max   |   0.892857  |     0.340048  |   0.909091  |    0.450071  |   0.607143  |       0.49793   |   0.868421  |    0.5       |   0.660652  |   0.49793   |   0.571429  |   0.562429  |
<br>


<br>

****
## Differences among metric sets and statitical tests

**Difference table info:**
* Values below the diagonal are difference between the mean of the models featuring the metrics in the row and the models featuring the metrics in the column. A negative value means that the models featuring the metrics in the row performed worse than those featuring the metrics in the column.

**Statistical test table info:**
* Values above the diagonal are the Choen's *d* effect size.
* Values below the diagonal are the p-values for the pairwise Wilcoxon's rank test.
* The shown p-values are not corrected for the number of comparisons. To do so, multiply each value by the number of comparisons, that is: *p-value * 21*.

### PRAUC

**Differences:**

|    | metrics       | ico     | ico-delta   | ico-process   | total   | process_delta   | process   | delta   |
|---:|:--------------|:--------|:------------|:--------------|:--------|:----------------|:----------|:--------|
|  0 | ico           | -       | -           | -             | -       | -               | -         | -       |
|  1 | ico_delta     | -0.0061 | -           | -             | -       | -               | -         | -       |
|  2 | ico_process   | -0.0166 | -0.0105     | -             | -       | -               | -         | -       |
|  3 | total         | -0.0214 | -0.0153     | -0.0048       | -       | -               | -         | -       |
|  4 | process_delta | -0.5482 | -0.5421     | -0.5316       | -0.5268 | -               | -         | -       |
|  5 | process       | -0.5526 | -0.5465     | -0.536        | -0.5312 | -0.0044         | -         | -       |
|  6 | delta         | -0.5811 | -0.575      | -0.5645       | -0.5597 | -0.0329         | -0.0285   | -       |
<br>


**Statistical test:**

|    | metrics       | ico      | ico-delta   | ico-process   | total    | process_delta   | process   | delta   |
|---:|:--------------|:---------|:------------|:--------------|:---------|:----------------|:----------|:--------|
|  0 | ico           | -        | 0.0422      | 0.1131        | 0.1429   | 3.0114          | 3.1072    | 3.2414  |
|  1 | ico_delta     | 6.70e-03 | -           | 0.0701        | 0.1002   | 2.9432          | 3.0354    | 3.1688  |
|  2 | ico_process   | 2.01e-05 | 1.54e-04    | -             | 0.0311   | 2.8655          | 2.9547    | 3.088   |
|  3 | total         | 6.14e-04 | 3.26e-03    | 2.07e-01      | -        | 2.8006          | 2.8868    | 3.0188  |
|  4 | process_delta | 8.53e-19 | 8.53e-19    | 8.53e-19      | 1.82e-18 | -               | 0.0209    | 0.1552  |
|  5 | process       | 8.53e-19 | 8.78e-19    | 8.78e-19      | 1.88e-18 | 1.53e-01        | -         | 0.1368  |
|  6 | delta         | 1.28e-18 | 1.40e-18    | 1.52e-18      | 3.20e-18 | 1.64e-12        | 2.69e-07  | -       |
<br>


### MCC


**Differences:**

|    | metrics       | ico     | ico-delta   | ico-process   | total   | process_delta   | process   | delta   |
|---:|:--------------|:--------|:------------|:--------------|:--------|:----------------|:----------|:--------|
|  0 | ico           | -       | -           | -             | -       | -               | -         | -       |
|  1 | ico_delta     | -0.0251 | -           | -             | -       | -               | -         | -       |
|  2 | ico_process   | -0.0343 | -0.0092     | -             | -       | -               | -         | -       |
|  3 | total         | -0.063  | -0.0379     | -0.0287       | -       | -               | -         | -       |
|  4 | process_delta | -0.713  | -0.6879     | -0.6788       | -0.6501 | -               | -         | -       |
|  5 | process       | -0.7203 | -0.6953     | -0.6861       | -0.6574 | -0.0073         | -         | -       |
|  6 | delta         | -0.7265 | -0.7015     | -0.6923       | -0.6636 | -0.0135         | -0.0062   | -       |
<br>


**Statistical test:**

|    | metrics       | ico      | ico-delta   | ico-process   | total    | process_delta   | process   | delta   |
|---:|:--------------|:---------|:------------|:--------------|:---------|:----------------|:----------|:--------|
|  0 | ico           | -        | 0.1331      | 0.1887        | 0.3215   | 4.4743          | 4.6186    | 4.6415  |
|  1 | ico_delta     | 6.48e-08 | -           | 0.0483        | 0.1859   | 4.0729          | 4.1957    | 4.2196  |
|  2 | ico_process   | 3.50e-09 | 3.16e-02    | -             | 0.1454   | 4.2104          | 4.3463    | 4.3701  |
|  3 | total         | 5.46e-08 | 4.30e-05    | 6.08e-04      | -        | 3.6741          | 3.7814    | 3.8058  |
|  4 | process_delta | 8.53e-19 | 8.78e-19    | 8.53e-19      | 1.99e-18 | -               | 0.0555    | 0.102   |
|  5 | process       | 8.53e-19 | 8.78e-19    | 8.53e-19      | 1.99e-18 | 2.17e-01        | -         | 0.0484  |
|  6 | delta         | 8.53e-19 | 8.78e-19    | 8.53e-19      | 2.05e-18 | 6.04e-02        | 3.44e-01  | -       |
<br>


### ROCAUC


**Differences:**

|    | metrics       | ico     | ico-delta   | ico-process   | total   | process_delta   | process   | delta   |
|---:|:--------------|:--------|:------------|:--------------|:--------|:----------------|:----------|:--------|
|  0 | ico           | -       | -           | -             | -       | -               | -         | -       |
|  1 | ico_delta     | -0.0037 | -           | -             | -       | -               | -         | -       |
|  2 | ico_process   | -0.0074 | -0.0037     | -             | -       | -               | -         | -       |
|  3 | total         | -0.0086 | -0.0048     | -0.0012       | -       | -               | -         | -       |
|  4 | process_delta | -0.3709 | -0.3672     | -0.3635       | -0.3624 | -               | -         | -       |
|  5 | process       | -0.3715 | -0.3678     | -0.3641       | -0.363  | -0.0006         | -         | -       |
|  6 | delta         | -0.3997 | -0.396      | -0.3923       | -0.3911 | -0.0287         | -0.0281   | -       |
<br>


**Statistical test:**

|    | metrics       | ico      | ico-delta   | ico-process   | total    | process_delta   | process   | delta   |
|---:|:--------------|:---------|:------------|:--------------|:---------|:----------------|:----------|:--------|
|  0 | ico           | -        | 0.0692      | 0.1354        | 0.1556   | 4.869           | 5.3839    | 5.3407  |
|  1 | ico_delta     | 2.29e-02 | -           | 0.0636        | 0.083    | 4.6763          | 5.138     | 5.1277  |
|  2 | ico_process   | 1.86e-05 | 6.10e-05    | -             | 0.0195   | 4.5927          | 5.0383    | 5.0384  |
|  3 | total         | 7.00e-04 | 2.35e-03    | 2.72e-01      | -        | 4.5553          | 4.9971    | 4.9985  |
|  4 | process_delta | 8.53e-19 | 8.78e-19    | 8.78e-19      | 1.88e-18 | -               | 0.0067    | 0.3055  |
|  5 | process       | 8.53e-19 | 9.04e-19    | 9.04e-19      | 1.93e-18 | 8.73e-01        | -         | 0.3185  |
|  6 | delta         | 8.53e-19 | 9.04e-19    | 9.04e-19      | 1.93e-18 | 3.49e-08        | 1.33e-06  | -       |
<br>


### PRECISION


**Differences:**

|    | metrics       | ico     | ico-delta   | ico-process   | total   | process_delta   | process   | delta   |
|---:|:--------------|:--------|:------------|:--------------|:--------|:----------------|:----------|:--------|
|  0 | ico           | -       | -           | -             | -       | -               | -         | -       |
|  1 | ico_delta     | -0.025  | -           | -             | -       | -               | -         | -       |
|  2 | ico_process   | -0.0202 | 0.0048      | -             | -       | -               | -         | -       |
|  3 | total         | -0.0489 | -0.0238     | -0.0286       | -       | -               | -         | -       |
|  4 | process_delta | -0.6094 | -0.5844     | -0.5892       | -0.5605 | -               | -         | -       |
|  5 | process       | -0.6124 | -0.5874     | -0.5922       | -0.5635 | -0.003          | -         | -       |
|  6 | delta         | -0.6416 | -0.6165     | -0.6213       | -0.5927 | -0.0322         | -0.0291   | -       |
<br>


**Statistical test:**

|    | metrics       | ico      | ico-delta   | ico-process   | total    | process_delta   | process   | delta   |
|---:|:--------------|:---------|:------------|:--------------|:---------|:----------------|:----------|:--------|
|  0 | ico           | -        | 0.1317      | 0.1141        | 0.2526   | 3.4987          | 3.589     | 3.7717  |
|  1 | ico_delta     | 1.16e-05 | -           | -0.0254       | 0.1166   | 3.14            | 3.2133    | 3.3821  |
|  2 | ico_process   | 9.07e-05 | 8.99e-01    | -             | 0.1489   | 3.407           | 3.4965    | 3.6804  |
|  3 | total         | 9.45e-06 | 2.67e-02    | 3.01e-03      | -        | 2.9579          | 3.0262    | 3.1912  |
|  4 | process_delta | 8.53e-19 | 1.25e-18    | 8.53e-19      | 2.66e-18 | -               | 0.0181    | 0.1942  |
|  5 | process       | 8.53e-19 | 1.25e-18    | 8.53e-19      | 2.67e-18 | 4.38e-01        | -         | 0.1802  |
|  6 | delta         | 8.53e-19 | 1.25e-18    | 8.53e-19      | 2.83e-18 | 3.81e-03        | 1.46e-02  | -       |
<br>


### RECALL


**Differences:**

|    | metrics       | ico     | ico-delta   | ico-process   | total   | process_delta   | process   | delta   |
|---:|:--------------|:--------|:------------|:--------------|:--------|:----------------|:----------|:--------|
|  0 | ico           | -       | -           | -             | -       | -               | -         | -       |
|  1 | ico_delta     | -0.0084 | -           | -             | -       | -               | -         | -       |
|  2 | ico_process   | -0.0289 | -0.0205     | -             | -       | -               | -         | -       |
|  3 | total         | -0.0464 | -0.038      | -0.0175       | -       | -               | -         | -       |
|  4 | process_delta | -0.5628 | -0.5544     | -0.5339       | -0.5164 | -               | -         | -       |
|  5 | process       | -0.5569 | -0.5485     | -0.5281       | -0.5105 | 0.0059          | -         | -       |
|  6 | delta         | -0.6609 | -0.6525     | -0.632        | -0.6145 | -0.0981         | -0.104    | -       |
<br>


**Statistical test:**

|    | metrics       | ico      | ico-delta   | ico-process   | total    | process_delta   | process   | delta   |
|---:|:--------------|:---------|:------------|:--------------|:---------|:----------------|:----------|:--------|
|  0 | ico           | -        | 0.0624      | 0.2097        | 0.3119   | 2.9632          | 2.8401    | 3.6151  |
|  1 | ico_delta     | 9.29e-05 | -           | 0.1485        | 0.2551   | 2.9155          | 2.7941    | 3.5645  |
|  2 | ico_process   | 2.08e-08 | 3.43e-05    | -             | 0.1151   | 2.7708          | 2.6565    | 3.4036  |
|  3 | total         | 1.74e-06 | 8.65e-05    | 1.10e-02      | -        | 2.5667          | 2.4653    | 3.1605  |
|  4 | process_delta | 1.25e-18 | 1.82e-18    | 1.25e-18      | 5.59e-18 | -               | -0.0248   | 0.4318  |
|  5 | process       | 7.43e-18 | 1.99e-18    | 1.58e-18      | 1.18e-17 | 9.84e-01        | -         | 0.4475  |
|  6 | delta         | 8.53e-19 | 1.25e-18    | 8.52e-19      | 3.19e-18 | 9.35e-05        | 7.20e-05  | -       |
<br>


### F1


**Differences:**

|    | metrics       | ico     | ico-delta   | ico-process   | total   | process_delta   | process   | delta   |
|---:|:--------------|:--------|:------------|:--------------|:--------|:----------------|:----------|:--------|
|  0 | ico           | -       | -           | -             | -       | -               | -         | -       |
|  1 | ico_delta     | -0.0236 | -           | -             | -       | -               | -         | -       |
|  2 | ico_process   | -0.0335 | -0.0099     | -             | -       | -               | -         | -       |
|  3 | total         | -0.0586 | -0.035      | -0.0251       | -       | -               | -         | -       |
|  4 | process_delta | -0.625  | -0.6014     | -0.5916       | -0.5664 | -               | -         | -       |
|  5 | process       | -0.627  | -0.6034     | -0.5935       | -0.5684 | -0.002          | -         | -       |
|  6 | delta         | -0.6685 | -0.6449     | -0.6351       | -0.6099 | -0.0435         | -0.0415   | -       |
<br>


**Statistical test:**

|    | metrics       | ico      | ico-delta   | ico-process   | total    | process_delta   | process   | delta   |
|---:|:--------------|:---------|:------------|:--------------|:---------|:----------------|:----------|:--------|
|  0 | ico           | -        | 0.1321      | 0.1941        | 0.317    | 3.6964          | 3.7257    | 4.0985  |
|  1 | ico_delta     | 1.59e-08 | -           | 0.0545        | 0.1812   | 3.3758          | 3.4013    | 3.7387  |
|  2 | ico_process   | 3.86e-10 | 1.41e-02    | -             | 0.134    | 3.4384          | 3.4657    | 3.8216  |
|  3 | total         | 6.50e-08 | 1.52e-04    | 8.52e-04      | -        | 3.0706          | 3.0937    | 3.4083  |
|  4 | process_delta | 8.53e-19 | 1.25e-18    | 8.53e-19      | 2.92e-18 | -               | 0.0117    | 0.2673  |
|  5 | process       | 8.53e-19 | 1.25e-18    | 8.53e-19      | 3.10e-18 | 6.78e-01        | -         | 0.2565  |
|  6 | delta         | 8.53e-19 | 1.25e-18    | 8.53e-19      | 2.92e-18 | 3.47e-04        | 3.20e-04  | -       |
<br>

