# Getting Started

Welcome to your new project.

It contains these folders and files, following our recommended project layout:

File or Folder | Purpose
---------|----------
`app/` | content for UI frontends goes here
`db/` | your domain models and data go here
`srv/` | your service models and code go here
`package.json` | project metadata and configuration
`readme.md` | this getting started guide


## Next Steps

- Open a new terminal and run `cds watch` 
- (in VS Code simply choose _**Terminal** > Run Task > cds watch_)
- Start adding content, for example, a [db/schema.cds](db/schema.cds).


## Learn More

Learn more at https://cap.cloud.sap/docs/get-started/.


## dev phase to create the currect flow 2
npm install -g mbt
npm install --global @sap/cds-dk
mkdir capApp
cd capApp
cds init
cds add mta
mtb build

git init
git remote add origin https://github.com/papaik/capApp.git
git branch -M main
git push -u origin main