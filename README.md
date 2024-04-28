# Git Assignment - sabarevasan

    > a. What is an _issue_?
    An issue on github, is a potential problem causing piece of code or a team member's suggestion to make an update. This could be to resolve an issue, meet best practise, or requesting further clarification. An issue on github keeps track of the begining, staus and the resolution of an item of concern while enabling effective team collaboration.
    
    > b. What is a _pull request_?
    Further to effective team collaboration, a pull request allows the team members to review another members work and make suggestions to improve or appreciate the job well done. Github provides ways to gate the code merge process by making pull requests as a rule prior to merging the updated code to a prodcution version of a project, thus ensuring atleast one working branch for the project. Tagging reviewrs to a pull request, notifies them of a pending task. Once the required number of reviewrs approve the pull request, the updated code is ready for merge.

    > c. How do I open up a _pull request_?
    Once all the necessary work is complete on a feature branch of the project codebase (post staging, commit, and push to origin), and before merging these updates to the source branch or main/master branch it is required to "compare and creaate a new pull request". PR details are updated as per the practise and reviewers are selected.
    
    > d. Give me a step by step guide on how to add someone to your repository.
    As the owner of a repository, we are given the option to add collabotrators to the repository. The proposed collaborators must have a github account. Collaborator github accout name is used to send them an invite to start contributing to the repository. They have the choice to decline. The repository privileges must be set by the owner while sending out the invite.

    > e. What is the difference between `git` and `GitHub`?
    GIT is the process or philosophy for version control, that is very effective for projects with multiple contributors spread across the globe. GIT is robust, as it keeps track of file changes only rather than keeping multiple copies of the same source code. Github is the cloud based version control service, with additional services for code management for entreprise scale projects.

    > f. What does `git diff` do?
    git diff highlights the differences between to code branches or files, making it easy to identify what was removed or included to a previous version of the code.

    > g. What is the `main` branch?
    `main` branch is the default github branch that gets checked out while cloning a repository, and it has been a practise to keep the main branch as the current working codebase or production grade code. If a certain application requires restoring the main branch is used as the one place of truth/backup, making it vital to the working and continuity of a project.

    > h. Besides our initial commit if it is a new repository, should we directly push our changes directly into the `main` branch?
    It is best to push code to main branch as feature batches, by using feature branch to develop, test, and complete a specific feature, and delete the feature branch once it is merged to main branch. Establishing this as a practice in a new repository will enable a culture of maintaining clean code in main branch.
