* airflow/ → orchestrer les jobs ETL (extraction CSV, chargement dans PostgreSQL, déclenchement dbt).
* dbt/ → transformations SQL, modèle décisionnel.
* data/ → stocker les fichiers bruts que tu reçois (import test).
* warehouse/ → scripts initiaux pour la BDD PostgreSQL (si tu veux structurer ton DWH).
* reports/ → modèles de dashboard (Metabase, PowerBI, Tableau).
* docker/ → pour contenir docker-compose.yml et configurer tous tes services.
* notebooks/ → tester des requêtes, du ML léger (PoC rapide).
* docs/ → garder les ateliers métiers, KPIs, specs techniques.

│── airflow/      # DAGs, configs Airflow
│── data/         # Données sources (CSV, JSON, logs, tests…)
│── dbt/          # Modèles dbt, seeds, tests
│── docker/       # Dockerfiles, docker-compose.yml
│── docs/         # Documentation projet (technique + fonctionnelle)
│── notebooks/    # Jupyter notebooks pour exploration
│── reports/      # Dashboards exportés, PDFs, PPTs
│── warehouse/    # Schéma cible (Snowflake, Postgres, etc.)
│── README.md     # Explications globales
│── .gitignore    # Pour ignorer fichiers inutiles dans Git


