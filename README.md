# AI-Powered-Service-Pitch-Email-Generator
Given a Job posting link this AI powered app will go and fetch the skills from it and find out the related portfolio from the database and then draft a mail for the client. The mail will also have portfolio links in it.

# How to run?
### STEPS:

Clone the repository

```bash
git clone https://github.com/rahulgayke/AI-Powered-Service-Pitch-Email-Generator.git
```
### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n pitchmailer python=3.10 -y
```

```bash
conda activate pitchmailer
```


### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```


### Create a `.env` file in the root directory and add your Huggingface API credentials as follows:

```ini
HUGGINGFACE_API_TOKEN = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
```