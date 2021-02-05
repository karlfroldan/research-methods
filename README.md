# AdNU DCS Senior Project Documentation Template

Adopted from Virginia Polytechnic Institute, this LaTeX document is used by the Ateneo de Naga University Department of Computer Science (DCS) as template for the Senior Thesis/Capstone Project documentation.

### Instructions for mga tamad according to one prof
1. Before making changes, create a new branch (branching from `master`) using Github. Name your branch.
2. In the terminal, assuming you're in the directory of the project, type in `git fetch`
3. Then `git checkout NEW-BRANCH-NAME`, then `git pull origin NEW-BRANCH-NAME`
4. You can make your changes. To commit, type
    1. `git add .`
    2. `git commit -m 'fucking commit'`
    3. `git push origin NEW-BRANCH-NAME`
5. Go back to the github website repository and make a pull request. Feel free to merge yourself if there are no
merge conflicts.

Note: Branches are for preventing merge conflicts if two or more people are working on a project.

### Instructions for building
* `make` - Builds the PDF file
* `make clean` - Cleans all unecessary files
