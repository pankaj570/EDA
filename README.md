# EDA
EDA INTEGRAION USING LLM FRAMEWORK USING
- OLLAMA || - MISTRAL AI || - GRADIO UI

Understanding meaning of each column:Data Dictionary: Variable Description
- Survived - Survived (1) or died (0)
- Pclass - Passenger’s class (1 = 1st, 2 = 2nd, 3 = 3rd)
- Name - Passenger’s name
- Sex - Passenger’s sex
- Age - Passenger’s age
- SibSp - Number of siblings/spouses aboard
- Parch - Number of parents/children aboard (Some children travelled only with a nanny, therefore parch=0 for them.)
- Ticket - Ticket number
- Fare - Fare
- Cabin - Cabin
- Embarked - Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

The Process to set up the project in local machine
OLLMA Set up:
  1. Download from https://ollama.com/download/windows
  2. Install from download folder
  3. After installed successfully, open command prompt and type command "ollama" press Enter key you will see below option means OLLMMA working fine
      Available Commands:
          - serve       Start ollama </br>
          - create      Create a model from a Modelfile </br>
          - show        Show information for a model </br>
          - run         Run a model </br>
          - stop        Stop a running model </br>
          - pull        Pull a model from a registry </br>
          - push        Push a model to a registry </br>
          - list        List models </br>
          - ps          List running models </br>
          - cp          Copy a model </br>
          - rm          Remove a model </br>
          - help        Help about any command </br>

MISTRAL AI Model Set Up:
1. Type "ollama list" in command prompt and see the if any model alredy pull if not the use to pull the model as " ollama pull mistral"
2. After pulling MISTRAL model you run as "ollama run mistral"
3. You will below screen
![image](https://github.com/user-attachments/assets/0291c3ee-9acc-4642-b4a9-1faac8afc06f)
4. you and ask any question as prompt input, model will give response on command prompt

GRADIO UI Integration with OLLAMA
1. Open code in VS Code and run as "python aap.py"
2. It will run as local server on URL : http://127.0.0.1:7860/
3. Upload csv file and see the Data Analysis by model and produce the visual data in nice graph





          
