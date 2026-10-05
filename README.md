# E-commerce: Practical Work

All the practical work of the E-commerce module: web services and web application development, from describing and consuming services to building a Flask application and a GraphQL API.

## Repository structure

```
.
├── Application Flask/   # Web application built with Flask
├── Calculatrice/        # Calculator web service
├── Service Etudiant/    # Student management web service
├── TP WADL/             # Lab on WADL (Web Application Description Language)
├── TPGRAPHQL/           # Lab on GraphQL
└── README.md
```

## Contents

| Folder | Description |
|--------|-------------|
| `Application Flask` | A web application developed with the Python Flask framework |
| `Calculatrice` | A calculator exposed as a web service |
| `Service Etudiant` | A web service to manage student data |
| `TP WADL` | Describing REST web services with WADL |
| `TPGRAPHQL` | Querying and serving data with GraphQL |

## Getting started

```bash
git clone https://github.com/sarahmoussaoui/E-commerce-Practical-Work.git
cd E-commerce-Practical-Work
```

Each folder is an independent project. Folder names contain spaces, so wrap them in quotes on the command line:

```bash
cd "Application Flask"
```

### Python projects (Flask, GraphQL)

```bash
python -m venv venv
source venv/bin/activate        # Windows: venv\Scripts\activate
pip install flask
flask run
```

The Flask server starts on http://127.0.0.1:5000 by default. For the GraphQL lab, also install the GraphQL library used in the code (for example `graphene` or `ariadne`) with `pip install`, then start the server as described in the lab's files.

### Web services

Open the `Calculatrice` and `Service Etudiant` folders in your IDE, deploy or run the service as in the lab, and call its endpoints with a browser, Postman or `curl`.

## Notes

This repository gathers the labs of one module, so each folder has its own dependencies and can be run on its own.
