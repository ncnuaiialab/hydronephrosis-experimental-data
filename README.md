# Hydronephrosis Experimental Data

The `data/` directory structured as follows:

```
data
├── 1
|    ├── abnormal
|     |    ├──{file_a}.jpg
|     |    ├──{file_a}_M.jpg
|     |     .........
|    └── normal
|         ├──{file_b}.jpg
|         ├──{file_b}_M.jpg
|          .........
├── 2
...
└── 10
```
folder 1 to folder 10 store corresponding fold data,
fold data were separate into abnormal and normal folder,
paired image and hydronephrosis mask have same prefix of file name.

![example img](data\5\abnormal\_dicoms_abnormal_20201027_S0000002_US000001_000.jpg)
![example mask](data\5\abnormal\_dicoms_abnormal_20201027_S0000002_US000001_000_M.jpg)

### Statistics

| Fold         | Dicoms  | Total frames | Abnormal Frames | Normal Frames |
| :----:             | :----:    |:----:   |:----:   |:----:   |
| 1          |94  |   415 | 243 | 172
| 2          |95  |   560 | 336 | 224
| 3          |95  |   579 |380 |199
| 4          |94  |   442|383 |59
| 5          |95  |   514 |316 |198
| 6          |95  |   502 |432 |70
| 7          |94  |   427 |377 |50
| 8          |95  |   263 |201 |62
| 9          |95  |   795 |478 |317
| 10        |95  |   593 |316 |277


