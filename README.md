![ATS_Resume_Tracker](https://socialify.git.ci/p2kalita/ATS_Resume_Tracker/image?language=1&name=1&owner=1&pattern=Circuit%20Board&stargazers=1&theme=Light)
# How to run?
### STEPS:

Clone the repository

```bash
Project repo: https://github.com/p2kalita/ATS_Resume_Tracker/
```

### STEP 01- Create a conda environment after opening the repository

```bash
conda create -p venv python=3.10 -y
```

```bash
conda activate venv/
```

### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```


### Create a `.env` file in the root directory and add your GOOGLE API credentials as follows:

```ini
GOOGLE_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
```




# Finally run the following command
```
streamlit run app.py
```

Now,

```
open up localhost:
```


![alt text](https://github.com/p2kalita/ATS_Resume_Tracker/blob/main/Capture.JPG)



### Techstack Used:

- Python
- LangChain
- Gemini
- Streamlit


