You can submit a new workflow, or an update to an existing one, in three different ways:

- Submitting a pull request
- Creating an issue on GitHub

If your workflow makes use of an API, make sure that you use Import Questions and remove your API keys before submitting. It should not violate an API developer's terms of service as it would result in consequences for the user of the workflow.

## Submitting a pull request

If you're familiar with Git, you can create a pull request containing the workflow you wish to add. When creating a pull request, make sure that the following steps are taken:

- Create a new directory for your workflow
- The **.wflow** workflow file is placed in this directory
- A README.md is created and added to this directory

### Format for README

The README for a workflow uses the following structure:

    # Workflow Title

    Submitted by: [@your_github_username](https://github.com/your_github_username)

    A brief description of the workflow (and any instructions, if necessary).

To export a workflow, open the Share Sheet and select **Share as File**.

### Updating a workflow

When submitting an update to an existing workflow:

- Overwrite the existing **.wflow** file
- Update the README.md (if required)

## Creating an issue on Github

The easiest way to submit a workflow is to create a new issue on GitHub. A GitHub account is required. Follow the issue template and provide:

- Workflow name
- A description
- Link to the workflow at **workflow.is**
