## Prompt 
How do I create a new Github repository from my terminal?

## ChatGPT Response
You can create a new GitHub repository from your terminal by following these steps:

Open your terminal and navigate to the directory where you want to create the new repository.
Create a new directory for your repository with the following command:

```mkdir <repository-name>```

Replace <repository-name> with the name you want to give your new repository.

Change into the new directory with the following command:

```cd <repository-name>```

Again, replace <repository-name> with the name of your new repository.

Initialize the repository with the following command:

```git init```

Create a new repository on GitHub.com. You can do this by logging in to your GitHub account, clicking the "+" icon in the top right corner of the page, and selecting "New repository". Follow the prompts to create a new repository with the same name as the directory you just created.

Copy the URL of your new repository.

Add the remote repository to your local repository with the following command:

```git remote add origin <repository-url>```

Replace <repository-url> with the URL you just copied.

Add your files to the local repository with the following command:

```git add .```

This will add all files in the current directory to the repository.

Commit your changes with the following command:

```git commit -m "Initial commit"```

Replace "Initial commit" with a message that describes the changes you made.

Push your changes to the remote repository with the following command:

```git push -u origin master```

That's it! Your new GitHub repository should now be created and initialized with your local files.