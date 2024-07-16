# Codeplace-dotnet-boilerplate

1. Fork this repo.
2. Go to https://github.com/codespaces
3. Click on "New Codespace" button.
4. Click the "Select repository" button and find your fork of this repo.
5. With default values selected, click "Create codespace".
6. Once VSCode starts, go to the VSCode "terminal" tab, run the command `dotnet new console --framework net6.0 --use-program-main` to create a new console project.
7. Update path to your app's output binary in .vscode/launch.json.
7. Set a breakpoint in Program.cs and start the debugger in VScode.
8. Win.

The Codespace VM is based on [this custom docker container](https://github.com/shukriadams/dotnet6buildcontainer). Substitute your own of you want a different setup.
