**Learning git version control**

# Create new project with git repository
> new project > create git repo > create

# Add a file to git
> src > new file > add file to git

// When modifying this file, the IDE automatically  
// indexes any changes.  
// This file is now tracked by git and added to the  
// local Changes tab in the Commit window.

# Commit changes
> commit window > select files > click commit

# Share project on GitHub 
> git > GitHub > share project on GitHub  
> fill necessary fields > share

// Share means publishing to a remote repo.  
// When you publish, commits are pushed and shown on GitHub.

# Create a new branch
> main/master > create branch from main > create

// Checkout branch switches to new branch right away.  
// Commit changes before switching to another branch.

# Make and view changes and Push
> log > git > undo commit
> git > push (specific to branch you have open)

// Make new file and add to version control when asked.  
// Blue means modified, green means newly added.  
// Double-click a file on the commit window to compare changes directly.  
// Undo commit, if not pushed.  
// Revert commit, if pushed.

# Merge branches and resolve conflicts
> from master > new_feature branch > merge "new_feature" into "main"

// Since changes were made in both branches, Conflicts dialog appears.  
// Options: accept yours/theirs or merge to solve conflicts manually.  
// Three panels show up: main / result / new_feature.  
// Result is a fully-functional editor.  
// Arrows accept changes into result, click apply.

# View history
> main branch > right-click a file > git > show history  
> right-click code fragment > git > history for selection
