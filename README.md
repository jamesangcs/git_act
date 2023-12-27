# git_act

# reference : https://www.youtube.com/watch?v=govmXpDGLpo
# git tag v1.0

# git tag -a v1.1 -m "tag for v1.1"
# git tag -l "v1.*"

# git push --set-upstream origin test

# pushing tag to remote
# git push origin v1.0
# git push --tags

# to delete tag locally
# git tag --delete v1.0

# deleting tag remotely
# git push origin -d v1.0

# we cannot checkout tags in git

# create tag for past commits
# git tag v0.3 7b0ce5a

Git Tag:

A tag in Git is a reference to a specific commit in the repository.
Tags are often used to mark specific points in the commit history, such as releases or important milestones.
Tags are lightweight and do not move as new commits are added; they simply point to a specific commit.
Example:

bash
Copy code
git tag v1.0.0  # Creates a tag named v1.0.0 at the current commit
GitHub Release:

A GitHub release is a higher-level concept that includes a Git tag but goes beyond it.
When you create a release on GitHub, it typically involves creating a Git tag to mark a specific commit and adding additional information such as release notes, a title, and attached files (like pre-built binaries).
GitHub releases provide a user-friendly way to package and distribute software versions, making it easy for users to download and use specific releases of a project.
To create a GitHub release, you often create a Git tag first and then use that tag when creating the release on the GitHub platform.

Example (assuming you've already created a tag locally):

bash
Copy code
git push origin v1.0.0  # Pushes the tag to the remote repository
Then, on GitHub, you go to the "Releases" tab and create a release, associating it with the tag you just pushed.

In summary, while a Git tag is a specific marker for a commit in the version history, a GitHub release is a broader concept that encompasses a Git tag along with additional information and assets to make it easier for users to consume and understand specific versions of a project.

###
# good video on git release
# https://www.youtube.com/watch?v=Ob9llA_QhQY

# Tagging basics
# https://git-scm.com/book/en/v2/Git-Basics-Tagging