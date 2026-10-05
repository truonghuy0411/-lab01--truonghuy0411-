# Study Assistant — starter

A starter repository for the CSC10014 Smart Virtual Assistant project.

## Setup

Prerequisites: Python 3.10+, Git.

&#x20;git clone git@github.com:<you>/lab01-starter.git

&#x20;cd lab01-starter

&#x20;python -m venv .venv

&#x20;source .venv/bin/activate # Windows: .venv\\Scripts\\Activate.ps1

&#x20;pip install -r requirements.txt

&#x20;pip install -e .

## Run

python -m assistant "where is the library?"

&#x20;# -> Library: room B.201, open Mon-Sat 07:00-20:00.Test



## Project structure

\## Test

&#x20;pytest -q # -> 4 passed

\## Troubleshooting

\- "No module named assistant" -> you forgot `pip install -e .` or the venv is not active.

\- PowerShell blocks Activate.ps1 -> Set-ExecutionPolicy -Scope CurrentUser RemoteSigned

