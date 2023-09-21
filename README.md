# Welcome to our lab 👋

You can open the Jupyter Notebooks in Colab (on this [site](https://kirenz.github.io/lab-template/slide.html)) or in GitHub Codespaces (see instructions below).

## Create Codespace


[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/kirenz/lab-template?quickstart=1)


- Simply choose the *default* settings and create the Codespace.

- After the container is created, you will see the following text in the terminal (wait until the installation process is done):

```bash
	"postCreateCommand": "pip3 install --user -r requirements.txt"
```


## Configure your Codespace

After your Codepsace is ready, you may want to: 

- Click on *activate* if you see the pop-up *Thanks for installing vscode-icons* (in the lower right right corner of your screen)

- If needed, provide **API-keys** (e.g. OpenAi or Hugging Face) in the file `.env-template`. Then save your changes and rename the file to `.env`

- Open *Extensions*, select *Atom One Dark Theme* and click twice on *Set Color Theme* to change the user interface

- Open *Explorer* and open the folder 📂 *code*. Now you can select a Jupyter Notebook

- Click on the *Kernel* picker, choose *Python environments* and select the latest Python version

- Note that the changes you make during the container session are not saved (this is only done with *commits* to the GitHub repo)

- When you are done, you can click on the connection icon `><` in the lower left corner of the VS Code user interface and select *Stop Codespace* from the menu.

- Visit the [GitHub Codespaces overview](https://github.com/codespaces) and make sure that you don't have active Codespaces