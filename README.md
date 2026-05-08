# Github Actions Learning Lab

This repository serves as a personal laboratory for learning GitHub Actions

## Documentation
- **Objective**: Learn how to automate shel command execution using GitHub-hosted runners.
- **Runner Enviroment**: `ubuntu-latest` (a clean, temporary virtual machine provided by Github).

## Key Concepts Learned
1. **Jobs**: The `build` job is the building block of the workflow.
2. **Runners**: `runs-on` defines the OS enviroment.
3. **Steps**: Each `run` command executes a separate shell process.
    -Note: Each step runs in a fresh, empty directory by default.

## Troubleshooting / Notes
- To trigger this workflow, simply `git push` your changes to the `main` branch.
- View logs in the "Actions" tab of this repository.

## Future References
- [Github Actions Documentation](https://docs.github.com/en/actions)