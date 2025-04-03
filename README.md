---
page_type: sample
languages:
- javascript
- nodejs
name: "JavaScript end-to-end Express.js server"
description: "This project is used instead of the previous express-generator."
products:
- azure
- vs-code
---
[![Build Status](https://dev.azure.com/LLCStudio/%E7%BF%BB%E8%AF%91%E9%AD%94%E6%B3%95%E9%97%AE%E9%A2%98/_apis/build/status%2Fllcstudio.js-e2e-express-server?branchName=main)](https://dev.azure.com/LLCStudio/%E7%BF%BB%E8%AF%91%E9%AD%94%E6%B3%95%E9%97%AE%E9%A2%98/_build/latest?definitionId=9&branchName=main)


# JavaScript end-to-end client file upload to Azure Storage Blobs

This is a basic Express.js server used for JS Dev Experience documentation, in place of the previously used express generator. 

1. Clone repo.

1. Install dependencies: 

    ```bash
    npm install
    ```

1. Configure environment variable name for port in `./src/index.js`.

    * Azure App Service on Linux: process.env.WEB_PORT
    * Azure App Service on Windows native: process.env.PORT

1. Start project: 

    ```bash
    npm start
    ```

## Contributions

* Legal files: If your PR removes the legal files, you PR will be closed. 
* Azure Pipelines: Azure pipeline example files should be put in the `azure-pipelines` directory. The file name should indicate the type of pipeline. That should be the only file in your PR or it will be closed. 


## Resources 

* [Dev Containers](docs/devcontainer.md)
* [Sample: App Service full stack with Authentication](https://github.com/azure-samples/js-e2e-web-app-easy-auth-app-to-app)
* [Samples: Azure TypeScript end to end](https://github.com/azure-samples/azure-typescript-e2e-apps)
