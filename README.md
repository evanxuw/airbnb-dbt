# airbnb-dbt

# Airbnb Data Pipeline Project with DBT

Welcome to my DBT project, where I showcase my skills in developing data pipelines using DBT (Data Build Tool) with Airbnb data sets. This project demonstrates various DBT concepts and techniques, including modeling, materialization, sources, seeds, snapshots, and more. The data is stored in Snowflake and visualized using Preset.

## Table of Contents

- [Introduction](#introduction)
- [Project Structure](#project-structure)
- [Concepts and Techniques](#concepts-and-techniques)
- [Data](#data)
- [Visualization](#visualization)
- [Setup](#setup)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This project is designed to highlight my expertise in DBT by creating robust data pipelines with Airbnb data sets. The project covers a wide range of DBT functionalities and best practices, aimed at transforming and managing data efficiently.

## Project Structure


## Concepts and Techniques

The following DBT concepts and techniques are utilized in this project:

- **Models**: Define and structure data transformations.
- **Materialization**: Manage how data is stored (e.g., table, view, ephemeral).
- **Sources**: Define and manage raw data sources.
- **Seeds**: Load CSV data into the database.
- **Snapshots**: Capture and track historical data changes.
- **Packages**: Reuse and share DBT code.
- **Hooks**: Custom SQL executed at various points in the DBT run lifecycle.
- **Exposures**: Define and document important datasets.
- **Analyses**: Perform ad-hoc analyses.
- **DBT Tests**: Ensure data quality and consistency.
- **DBT Documentation**: Auto-generate project documentation.
- **Jinja**: Templating language for SQL generation.
- **Macros**: Reusable SQL snippets.
- **Great Expectations (dbt-expectations)**: Data validation and testing.
- **Debugging Tests**: Identify and fix issues in the data pipeline.
- **Orchestration**: Manage and automate the execution of DBT models.
- **Complex SQL Queries**: Perform advanced data transformations and analysis.

## Data

The data used in this project is sourced from Airbnb and is stored in Snowflake. It includes information on listings, reviews, and host details.

## Visualization

The transformed data is visualized using Preset, providing insightful dashboards and reports.

## Setup

To set up the project locally, follow these steps:

1. Clone the repository:
  
   git clone https://github.com/your-username/airbnb-dbt-project.git

2. Navigate to the project directory:
   cd airbnb-dbt-project

3. Install the required packages:
   dbt deps
   
5. Configure your database connection in the 'profiles.yml' file.


## Contributing  
Many thanks to Zoltan C. Toth's bootcamp on complete dbt from zero to hero!
