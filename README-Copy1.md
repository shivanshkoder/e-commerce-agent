# Install uv

curl -LsSf <https://astral.sh/uv/install.sh> | sh

or

pip3 install uv

## check path
python3
>>> import shutil

>>> print(shutil.which("uv"))

## create project

uv init ecomm-prod-assistant

### imp cmd
uv pip list

uv python list - show all python version for venv

uv python install cpython-3.11.14-linux-x86_64-gnu

### create virtual venv
uv pip list

uv venv venv --python cpython-3.11.14-linux-x86_64-gnu

### install trquirements.txt
uv pip install -r requirements.txt