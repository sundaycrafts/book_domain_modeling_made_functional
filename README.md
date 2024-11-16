## Jupyter notebook with F# Setup

1. Setup F# from [official website](https://fsharp.org/) with [.NET SDK v8](https://dotnet.microsoft.com/en-us/download/dotnet/8.0)
2. Setup Jupyter Notebook (or Jupyter Lab) from [official website](https://jupyter.org/)
3. Install Jupyter interactor ([details](https://github.com/dotnet/interactive/blob/main/docs/NotebookswithJupyter.md))

```bash
dotnet tool install -g Microsoft.dotnet-interactive
dotnet interactive jupyter install

# launch jupyter notebook (assuming you are in the project root and having a path to jupyter cli)
jupyter-lab
```
