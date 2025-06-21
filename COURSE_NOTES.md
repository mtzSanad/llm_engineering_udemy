## Week 1

- There is a guide in week 1 that move you throught Python basics. It is called ["Intermediate Python"](./week1/Intermediate%20Python.ipynb)
- If you stuck with any code you can use chatGPT to explain it to you.

### Creating a virtual environment

```bash
python -m venv llms
```

- `source llms/Scripts/activate` in git bash to activate the virtual environment on Windows.

```bash
pyhon -m pip install --upgrade pip
pip install -r requirements.txt
```

- Make sure you install MS Visual C++ Build Tools if you are on Windows. You can find it [here](https://visualstudio.microsoft.com/visual-cpp-build-tools/).
- Go to the root folder of this repository and run `jupyter lab` to start Jupyter Lab.

## Week 2

- Check [Week 1 Day 2 Exercises](./week2/Week%201%20Day%202%20Exercises.ipynb) for exercises.
- To make sure ollama is running you can visit [http://localhost:11434](http://localhost:11434) in your browser. You must first install ollama and this is may not be needed to run `ollama serve` in your terminal.