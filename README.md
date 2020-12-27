### Members

Arthur Brito de Araujo Costa



#Git Workflow

To follow this workflow you have to have git installed.

The workflow start with cloning the repository

`git clone https://github.com/jcu-cms-bachelors/Assignment-2.git`

This will make a copy of the repository into your own profile.

To startup creating a branch for the feature you are developing run

`git checkout -b "feature/name-of-the-feature"`

Add the changes into the stage
`git add .`

Create a commit
`git commit -m "Your message"`

Once you done with the feature you can publish it

`git push origin HEAD`*

*You might need to login or adjust your ssh keys to push to production.

A link will be generated that can help you to create a **Pull Request**
Example: https://github.com/jcu-cms-bachelors/Assignment-2/pull/new/feature/read-me

Following the link steps you can create a **Pull Request**.
Pull Requests needs to be reviewed by the peers to be merged into **Staging** environment.

[A staging environment is the last step before something goes into production and is visible on the live site. ](https://umbraco.com/about-us/umbraco-dictionary/staging-environment/#:~:text=A%20staging%20environment%20is%20the,they%20hit%20the%20live%20website. "A staging environment is the last step before something goes into production and is visible on the live site. ")

After the things are push into staging and tested we can then push to the production which is the **main** branch.


