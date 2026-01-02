# Dosa Shop
## plain Dosa
* dosa batter
* lite oil added
# Karam dosa
* Dosa batter added
* Karam added
* oil added
# onion dosa
* Dosa batter added for onion
* OIL added
# Potato dosa
* Dosa batter added
* OIL added
########################################################
# Switch to main branch
git checkout main

# Update local main branch
git pull origin main

# Create a new feature branch for Onion Dosa
git checkout -b onion-dosa

# Stage changes, commit, and push to remote
git add .
git commit -m "Add Onion Dosa feature"
git push origin onion-dosa

# Then create a Pull Request (PR) on GitHub
# After review and approval, merge the PR into main
# Switch back to main branch
git checkout main

# Pull the latest changes from GitHub (including the merged PR)
git pull origin main
