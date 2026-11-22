# Why this exists

The binaries provided by the [upstream bruno repository](https://github.com/usebruno/bruno/releases) or the [official website](https://www.usebruno.com/downloads) are not built directly from the published source code. The Open Source Edition includes changes that impose restrictions (e.g. number of OpenAPI syncs per month) and adds upgrade banners.

# What does this repo do

The GitHub Action workflow in this repo builds binaries directly from the published source code with no functional changes, and uploads them to a GitHub release.
