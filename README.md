16010122146 Sarthak Pokale Batch-C1

This project demonstrates how to automate API testing using Postman Collections with GitHub Actions. The collection file, API Testing.postman_collection.json, is executed in the CI pipeline whenever changes are pushed to the main branch or a pull request is opened. The automation uses Newman, the Postman CLI tool, to run the tests and display results directly in the GitHub Actions logs.

Developers can also run the same tests locally for consistency. By installing Newman, the collection can be executed with newman run "API Testing.postman_collection.json". This ensures that test results remain the same across local and pipeline environments.

The workflow setup helps validate APIs continuously and can be extended further by adding environment files, generating detailed HTML reports, or integrating into a complete CI/CD pipeline.
