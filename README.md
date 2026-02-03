# CMPE351-Group4-Project
Answering research questions on the flight-delay-dataset-20182022 dataset.

## Setup

1. Clone the repo and install the dependencies.

```bash
pip install -e .
```

or 

```bash
uv sync
```

2. Next, the dataset should be downloaded as a zip from kaggle and extracted into the data directory.

[DATASET LINK](https://www.kaggle.com/datasets/robikscube/flight-delay-dataset-20182022/data)

*Plaintext: https://www.kaggle.com/datasets/robikscube/flight-delay-dataset-20182022/data*

The folder should have the following structure:

```
data
└── flight-delay-dataset-20182022
    ├── Airlines.csv
    ├── Combined_Flights_2018.csv
    ├── Combined_Flights_2018.parquet
    ├── Combined_Flights_2019.csv
    ├── Combined_Flights_2019.parquet
    ├── Combined_Flights_2020.csv
    ├── Combined_Flights_2020.parquet
    ├── Combined_Flights_2021.csv
    ├── Combined_Flights_2021.parquet
    ├── Combined_Flights_2022.csv
    ├── Combined_Flights_2022.parquet
    ├── raw
    │   ├── Flights_2018_10.csv
    │   ├── Flights_2018_11.csv
    │   ├── Flights_2018_12.csv
    │   ├── Flights_2018_1.csv
    │   ├── Flights_2018_2.csv
    │   ├── Flights_2018_3.csv
    │   ├── Flights_2018_4.csv
    │   ├── Flights_2018_5.csv
    │   ├── Flights_2018_6.csv
    │   ├── Flights_2018_7.csv
    │   ├── Flights_2018_8.csv
    │   ├── Flights_2018_9.csv
    │   ├── Flights_2019_10.csv
    │   ├── Flights_2019_11.csv
    │   ├── Flights_2019_12.csv
    │   ├── Flights_2019_1.csv
    │   ├── Flights_2019_2.csv
    │   ├── Flights_2019_3.csv
    │   ├── Flights_2019_4.csv
    │   ├── Flights_2019_5.csv
    │   ├── Flights_2019_6.csv
    │   ├── Flights_2019_7.csv
    │   ├── Flights_2019_8.csv
    │   ├── Flights_2019_9.csv
    │   ├── Flights_2020_10.csv
    │   ├── Flights_2020_11.csv
    │   ├── Flights_2020_12.csv
    │   ├── Flights_2020_1.csv
    │   ├── Flights_2020_2.csv
    │   ├── Flights_2020_3.csv
    │   ├── Flights_2020_4.csv
    │   ├── Flights_2020_5.csv
    │   ├── Flights_2020_6.csv
    │   ├── Flights_2020_7.csv
    │   ├── Flights_2020_8.csv
    │   ├── Flights_2020_9.csv
    │   ├── Flights_2021_10.csv
    │   ├── Flights_2021_11.csv
    │   ├── Flights_2021_12.csv
    │   ├── Flights_2021_1.csv
    │   ├── Flights_2021_2.csv
    │   ├── Flights_2021_3.csv
    │   ├── Flights_2021_4.csv
    │   ├── Flights_2021_5.csv
    │   ├── Flights_2021_6.csv
    │   ├── Flights_2021_7.csv
    │   ├── Flights_2021_8.csv
    │   ├── Flights_2021_9.csv
    │   ├── Flights_2022_1.csv
    │   ├── Flights_2022_2.csv
    │   ├── Flights_2022_3.csv
    │   ├── Flights_2022_4.csv
    │   ├── Flights_2022_5.csv
    │   ├── Flights_2022_6.csv
    │   └── Flights_2022_7.csv
    ├── readme.html
    └── readme.md

3 directories, 68 files
```
