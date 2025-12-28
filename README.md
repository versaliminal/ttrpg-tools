# ttrpg-tools
Tools for building / running Table-Top Roleplaying Games (TTRPGs)

# Setup
## Python environment
To create a valid python environment run the follwoing:
1. `python3 -m venv .venv`
2. `source .venv/bin/activate`
3. `pip install -r scripts/requirements.txt`

# Creating a new project
1. Create your templates under content/templates/{project-name}
2. Create your source tables under content/tables/{project-name} (you may skip this if you want to refresh from gsheets)
3. Update the projects.yaml file to include your project resources

# Rendering your project
Run the render script (add `--refresh` to refresh sources)
`scripts/render.py content {project-name}`
Rendered templates will be found under content/rendered