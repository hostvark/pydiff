# Pydiff

Pydiff is a CLI-tool designed to calculate the difference between two JSON or YAML files. Supports output in JSON format as well as in a flat format in a form of a readable text.
---
### Quick start
```bash
# 1. Clone a repository and enter your new directory
git clone https://github.com/hostvark/pydiff.git
cd pydiff

# 2. Install UV package and project manager.
curl -LsSf https://astral.sh/uv/install.sh | sh

# 3. Install the project
make package-install
```

### Usage

Simply write "pydiff" and then specify the paths to two files (whether JSON or YAML) to see the difference between them.

Use "-f plain" to show the output in a form of a readable text and "-f json" to go back to standard JSON output.

```bash
pydiff -f plain data/file1.json data/file2.yml
# -- or --
pydiff -f json data/file1.json data/file2.yml

```
