# Hugo source code for the ResearchSchool website

## Deployment
1. Make the site pretty and work locally.
    ```
    hugo server
    # or:
    hugo server -t <THEME>
    ```
2. Delete the public folder.
    ```
    rm -rf public
    ```
3. Make a "public" submodule.
    ```
    git submodule add -b master git@github.com:researchschool/researchschool.github.io.git public
    ```
4. Build the website with the `deploy.sh` script.
    ```
    ./deploy.sh <MESSAGE>
    ```
