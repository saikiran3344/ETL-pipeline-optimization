# ETL-pipeline-optimization with Apache Spark


This project demonstrates an optimized ETL pipeline designed to preprocess data for machine learning models, reducing preprocessing time by using Apache Spark for parallel processing.

## How to Run
1. Ensure Spark is installed and accessible.
2. Update the input data file path (`s3://path_to_data.csv`) and output path (`s3://path_to_output/`).
3. Run the script:
   ```bash
   spark-submit etl_pipeline.py
