# Codespaces .NET Core Starter #

This project is a .NET Core starter for developers to use in Codespaces that includes basic system tools and extensions for .NET Core app development.


## What's Included ##

This is an unopinionated, basic environment that should be ready to expand upon to build a day-to-day development envrionment. It comes with the following software choices:


### System Tools ###

* [curl/curl](https://github.com/curl/curl): the command line tool for transferring data over a metric boatload of protocols.
* git: the Git SCM tool.
* [gnupg2](https://gnupg.org/): a complete and free implementatiuon of the OpenPGP standard.
* [stedolan/jq](https://github.com/stedolan/jq): a command line JSON parser.
* [sudo](https://www.sudo.ws/): the superuser authority delegation tool.
* [zsh](https://www.zsh.org/): interactive terminal (alternative to `bash`).
* [ohmyzsh/ohmyzsh](https://github.com/ohmyzsh/ohmyzsh): a delightful community driven framework for managing zsh config.
* [.NET Core SDK 3.1 LTS](https://dotnet.microsoft.com/download/dotnet-core/3.1?WT.mc_id=dotnet-0000-juyoo): a free, cross-platform and open source developer platform for building all types of apps.
* [Azure Functions Core Tools v3](https://docs.microsoft.com/azure/azure-functions/functions-run-local?tabs=linux,csharp,bash&WT.mc_id=dotnet-0000-juyoo): lets you develop and test your functions on your local computer from the command prompt or terminal.
* [Docker CE](https://docs.docker.com/engine/install/ubuntu/): runs Docker CLI inside Codespaces.
* [PowerShell 7](https://docs.microsoft.com/powershell/scripting/how-to-use-docs?view=powershell-7&WT.mc_id=dotnet-0000-juyoo): a cross-platform task automation and configuration management framework, consisting of a command-line shell and scripting language.

> **NOTE**: Docker daemon can't be running inside Codespaces. Instead, set `DOCKER_HOST` to access to a remote docker daemon.


### VS Code Extensions ###

The following extensions are installed for .NET Core development.

* [Azure Tools](https://marketplace.visualstudio.com/items?itemName=ms-vscode.vscode-node-azure-pack&WT.mc_id=dotnet-0000-juyoo): Get web site hosting, SQL and MongoDB data, Docker Containers, Serverless Functions and more, all on Azure, all from VS Code, in this one extension from Microsoft.
* [C#](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.csharp&WT.mc_id=dotnet-0000-juyoo): Included for C# development.
* [C# Extensions](https://marketplace.visualstudio.com/items?itemName=kreativ-software.csharpextensions&WT.mc_id=dotnet-0000-juyoo): Included to speed up development workflows.
* [C# Sort Usings](https://marketplace.visualstudio.com/items?itemName=jongrant.csharpsortusings&WT.mc_id=dotnet-0000-juyoo): Included for document formatting.
* [C# XML Documentation Comments](https://marketplace.visualstudio.com/items?itemName=k--kato.docomment&WT.mc_id=dotnet-0000-juyoo): Included for XML style C# code documentation.
* [Docs Authoring Pack](https://marketplace.visualstudio.com/items?itemName=docsmsft.docs-authoring-pack&WT.mc_id=dotnet-0000-juyoo): Collection of extensions to assist with content development for [docs.microsoft.com](https://docs.microsoft.com/?WT.mc_id=dotnet-0000-juyoo).
* [EditorConfig](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig&WT.mc_id=dotnet-0000-juyoo): Included for .NET Core code formatting found in `.editorconfig`.
* [Git Graph](https://marketplace.visualstudio.com/items?itemName=mhutchie.git-graph&WT.mc_id=dotnet-0000-juyoo): View a Git Graph of your repository, and perform Git actions from the graph.
* [Git History](https://marketplace.visualstudio.com/items?itemName=donjayamanne.githistory&WT.mc_id=dotnet-0000-juyoo): View git log, file history, compare branches or commits
* [GitHub Pull Requests and Issues](https://marketplace.visualstudio.com/items?itemName=github.vscode-pull-request-github&WT.mc_id=dotnet-0000-juyoo): Integration with GitHub's Pull Requests and Issues features that significantly enhance the experience of working in a repo hosted on GitHub.
* [GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens&WT.mc_id=dotnet-0000-juyoo): An extension that significantly enhances the experience using Git in a development environment.
* [IntelliCode](https://marketplace.visualstudio.com/items?itemName=visualstudioexptteam.vscodeintellicode&WT.mc_id=dotnet-0000-juyoo): AI-assisted development for multiple languages including JavaScript and TypeScript.
* [Live Share](https://marketplace.visualstudio.com/items?itemName=ms-vsliveshare.vsliveshare&WT.mc_id=dotnet-0000-juyoo): collaborative, multi-user remote editing from directly within the editor.
* [Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one&WT.mc_id=dotnet-0000-juyoo): All you need to write README.md in Markdown.
* [PowerShell](https://marketplace.visualstudio.com/items?itemName=ms-vscode.PowerShell&WT.mc_id=dotnet-0000-juyoo): This extension provides rich PowerShell language support.

The following extensions are intentionally disabled until they support remote server.

* ~~[Bracket Pair Colorizer 2](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer-2&WT.mc_id=dotnet-0000-juyoo): An extension colors matching brackets appropriately to enhance code readability.~~
* ~~[vscode-icons](https://marketplace.visualstudio.com/items?itemName=vscode-icons-team.vscode-icons&WT.mc_id=dotnet-0000-juyoo): An enhancement to the editor UI that gives more visual indicators in the explorer.~~


### Dotfiles ###

Dotfiles are meant to be personalised configuration. But the following dotfiles are largely common for .NET Core application development.

* [.gitignore](https://gitignore.io): Sourced from [gitignore.io](https://gitignore.io) configured for `VisualStudio`.
* [.editorconfig](https://editorconfig.org/): Sourced from [@RehanSaeedUK](https://twitter.com/RehanSaeedUK)'s [.editorconfig](https://github.com/RehanSaeed/EditorConfig/blob/master/.editorconfig)


### Operating System ###

* [Ubuntu 18.04](https://releases.ubuntu.com/18.04.4/): The 18.04 LTS version of Ubuntu.


## Usage ##

### In VS Codespaces ###

#### Initial Creation ####

For usage in VS Codespaces, you're going to want to head over to [online.visualstudio.com](https://online.visualstudio.com/?WT.mc_id=dotnet-0000-juyoo) and sign up for VS Codespaces (that process is outside the scope of these instructions). Once you've got an account and are signed in to [online.visualstudio.com](https://online.visualstudio.com/?WT.mc_id=dotnet-0000-juyoo), you're going to take the following steps:

* Ensure you're on the `/environments` page at [online.visualstudio.com/environments](https://online.visualstudio.com/environments)
* In the top right corner, there'll be a "Create environment" button. Click this button, which will open up a panel from the right side of the screen. Fill in the details of this panel:
  * **Environment Name:** This will be the visible name of your environment within Codespaces. The value here doesn't particularly matter * I'm going to use `tinycloud`.
  * **Git Repository:** This is going to be either the URL you'd `git clone` the repo from or the GitHub `<org OR user>/<repo>` shorthand. For this repo, the easier value would be `codespaces-examples/base`.
  * **Instance Type:** For this, you're going to choose your plan * in my case, I'm just going to go with the `Standard (Linux)` plan. For most use cases of this starter, `Basic (Linux)` should suffice. You can also change your plan at any time, as your workload demands.
  * **Suspend idle environment after:** This is the period of time you want your environment to automatically suspend after you've stopped actively using it. I generally chose 5 minutes and have not had any problems to date.
  * **Dotfiles (optional):** These are entirely optional, and are available for advanced users.
    * **Dotfiles Repository:** Using the `git clone` URL or the GitHub `<org OR user>/<repo>` syntax, you can define the repo to pull your dotfiles from. For examples, see [jessfraz/dotfiles](https://github.com/jessfraz/dotfiles) or [fnichol/dotfiles](https://github.com/fnichol/dotfiles).
    * **Dotfiles Install Command:** The name of the file or the command to run to install your dotfiles.
    * **Dotfiles Target Path:** The path where your dotfiles should be installed.
  * Once you've filled out all of those (and resolved any errors in the form validation, if any occurred), you'll be able to click "Create" at the bottom of the panel and your environment will start creating.


#### Connecting to your Environment ####

Once you've completed the Creation steps, your environment will be usable from Codespaces until you delete it. You can access it by going to [online.visualstudio.com](https://online.visualstudio.com/?WT.mc_id=dotnet-0000-juyoo) and selecting the vertical ellipsis menu to connect to it from the browser or launch it in VS Code / VS Code Insiders.

When inside of the environment you can change envrionments themselves from the command pallete with the `Codespaces: Connect`.

> **Note:** See the [VS Online in the Browser](https://docs.microsoft.com/visualstudio/online/quickstarts/browser?WT.mc_id=dotnet-0000-juyoo) quickstart for more information.

Additionally, if you've installed the [Visual Studio Codespaces](https://marketplace.visualstudio.com/items?itemName=ms-vsonline.vsonline&WT.mc_id=dotnet-0000-juyoo) extension in VS Code locally, you'll be able to directly connect from VS Code itself.

> **Note:** See the [VS Online in VS Code](https://docs.microsoft.com/visualstudio/online/quickstarts/vscode?WT.mc_id=dotnet-0000-juyoo) quickstart for more information.


#### Working ####

Now that you're set up and connected, you should be able to work within your Codespaces environment.


## Contributing ##

Contributions are welcome. Please refrain from opinionated additions like linters. However, adding package managers and other DX improvements that are additive like `yarn` or `EditorConfig` are welcome. Contributors must follow the [Code of Conduct](./CODE_OF_CONDUCT.md).
