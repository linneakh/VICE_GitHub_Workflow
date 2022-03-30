# VICE GitHub Workflows

This is repository for Linnea. 

Launch VICE app with shared data input here:

<a href="https://de.cyverse.org/apps/de/48b6e7ae-8b64-11ec-92dc-008cfa5ae621/launch?saved-launch-id=09d152f8-fc93-4620-affe-6c301fa0b204"><img src="https://de.cyverse.org/Powered-By-CyVerse-blue.svg"></a>

This will launch VICE RStudio with `storms_by_year/` data input shared by CyVerse user `culshawmaurer`.

## Finding Input Data

The storms data shared by CyVerse user `culshawmaurer` can be found inside the container, at `/data/input/storms_by_year/`.

## Cloning a GitHub Repo

Go to the `Terminal` pane of RStudio, and clone this repo like so:

```
git clone https://github.com/MCMaurer/VICE_GitHub_Workflow.git
```

Next, set up your `git` configuration:

```
git config --global user.name "Your Name"
git config --global user.email "youremail@domain.com
```

Finally, set up GitHub authentication by running `gh auth login`. This will walk you through the process of authenticating with GitHub.

Once the repo has been cloned, you can open the RStudio Project file to open the project.

**Note**: you can also list, clone, or fork repos with `gh`. However, sometimes the authorization doesn't carry over once you open an RStudio Project. If you are ever prompted for your GitHub username or password, just redo the authentication process with `gh auth login`.

## Reading the Shared Data

Open the `read_data_from_input.R` script, which has code to read data attached via the VICE Quick Launch.
