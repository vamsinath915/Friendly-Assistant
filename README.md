# Friendly-Assistant

1. create a folder

2.set up a virtual environment
     
	 python -m venv .venv
     
        .\.venv\Scripts\activate

3. Install required packages

   pip install google-adk
   pip install deprecated pydantic httpx requests rich

4.create file

	adk create myagent

5.  CREATE API KEY FROM Google AI Studio

6.myAgent created
	- .env
	- __init__.py
	- agent.py

7.Finally Run the parent folder
	
	adk run myagent
