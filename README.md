# Sandbox #
This is the Sandbox for learning how to use git.

Don't be :worried: - You won't :boom: anything when you :game_die: with this repository.

:smile: the experience and be :sparkles:!

Steffen

## Get the sandbox locally
Get a local clone of this repository by
```bash
git clone ssh://git@github.com/staerz/sandbox.git
```

## Learning Git ##
For learning git, see the [Official Git Tutorial](https://git-scm.com/docs/gittutorial) or just search the web for others.

Feel also free to study the following tutorials:
- [LASP Git tutorial](https://staerz.web.cern.ch/slides/LASP_Git_Tutorial.pdf)
- [LASP Rebase tutorial](https://staerz.web.cern.ch/slides/LASP_Git_Rebase.pdf)

but keep in mind that they are tailored for [the LASP firmware project](https://gitlab.cern.ch/atlas-lar-be-firmware/LASP/LASP) and hence not everything explained there might apply for your project.

A big recommendation is the [Git Cheat Sheet](https://staerz.web.cern.ch/slides/GitCheatSheet.txt), even if you know git already very well.
Make sure to always have a copy of it right next to you :wink:.

Feel free to <a href="mailto:steffen.staerz<ät>cern.ch?subject=GitCheatSheet">:e-mail: me</a> to add further commands to it if you miss anything or find any funny typo: Sorry, I'm :de: :rofl:.

In the end, it comes with practice.
This repository shall [help you to get some](#learning-by-doing-with-git).

## Directory structure and file content
This repository comes with the following :memo: (by default before changes) and :open_file_folder: :
- `BrothersGrimm.txt`: A :memo: plenty of :fire: to fix for you :eyes: to work on for testing git commands
- `WordExceptions.txt`: A list of :confused: words for aspell contained in the `BrothersGrimm.txt`
- [`.gitlab/CODEOWNERS`](https://gitlab.cern.ch/help/user/project/code_owners): The :memo: setting the owners of different :memo: and :open_file_folder: in this repository
- `mountain`: a test :open_file_folder: with a :memo: to claim ownership to demonstrate principle of code owners

## Get inspiration ##
### Learning by doing with git ###
To test git, simply play with the repository (based on the [**Git Cheat Sheet**](https://staerz.web.cern.ch/slides/GitCheatSheet.txt)):

First of all: create a dedicated branch (try not to mess on master, you won't be able to push anyway, possibly), then:
- create new :memo:
- modify existing :memo:
- try to merge with other branches etc.
- revert some commits
- ...

Give it a try by fixing some :fire: in the **BrothersGrimm.txt**!
You can do this directly in the [web interface](./BrothersGrimm.txt), but you should also give the terminal a try :sunglasses:

### Issue tracker ###
GitHub has an integrated issue tracker.

This repository requires 1 approver per merge request (as might be the default for some projects).

For learning the feature and in :zap: to good practice, this repository has "Enable self approval of merge requests" active, so you can approve your own merge requests.

Merging to master is still restricted to the maintainers of this repository.
You can though merge to any other branch.
