Feature branches
================

To start working on anything, you first create a `feature branch`. These branches can either be a `feature`, a `fix`, or a `chore`.

```sh
# Create a branch locally
git branch feature/improve_rating_system

# Work, work...
git commit -m "Show stars for user ratings"
git commit -m "Allow users to click on stars"

# Push your branch as often as possible
git push --set-upstream origin feature/improve_rating_system
```

All work start as a feature branch. Nobody should directly push commits to the main branches (*master* and *develop*). Working this way brings us a lot of benefits:

- Your work can easily be reviewed later through [pull requests](pull_requests.md).
- It can be reverted later on as one branch, if need be.