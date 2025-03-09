# Code_tech-2.1

Name : Rajlaxmi jena

Domain:Data Science

Id: CT08TDM

Project: Data pipe line development

Data Pipeline Development with Airflow involves creating automated workflows to extract, transform, and load (ETL) data using Apache Airflow.

Key Components: DAG (Directed Acyclic Graph): Defines the pipeline structure and dependencies between tasks. Operators: Define individual tasks (e.g., PythonOperator, BashOperator, etc.). Tasks: Units of work that execute specific operations (e.g., data extraction, transformation). Scheduler: Triggers the DAG to run at specified intervals. Executor: Executes tasks (e.g., LocalExecutor, CeleryExecutor). Hooks: Connect to external systems (e.g., databases, APIs). Workflow Example: Extract: Pull data from a database or API using a PythonOperator. Transform: Clean and format data using a Python script. Load: Store the processed data into a database or data warehouse. Benefits: ✅ Automates complex workflows ✅ Handles task dependencies and retries ✅ Provides monitoring and logging through a web UI
