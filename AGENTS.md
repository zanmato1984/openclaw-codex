# OpenClaw Learning and Troubleshooting Objectives

## Goals

In this directory, I want you to focus on two things around OpenClaw:

1. Based on the source code and documentation, help me systematically learn and understand OpenClaw's architecture, configuration, runtime behavior, and common workflows.
2. Using my local machine's actual configuration and runtime behavior, help me troubleshoot and fix local OpenClaw usage issues.

## Working Style

- Treat the `openclaw` directory in the current working directory as the OpenClaw source tree. If it does not exist, clone it from https://github.com/openclaw/openclaw.
- Prioritize conclusions based on local source code and documentation; supplement with external references only when necessary.
- During troubleshooting, first reproduce the issue, then locate the cause, and finally provide verifiable remediation steps.
- Whenever possible, attach key conclusions to concrete file paths, configuration keys, or log locations.
- Avoid purely theoretical advice; provide directly executable commands and checklists whenever possible.
- When proposing any solution, do not consider paths that modify OpenClaw source code; limit recommendations to existing capabilities in the current OpenClaw setup.

## Configuration Maintenance

- The user may change the OpenClaw configuration file on this machine at any time; for configuration-related issues, first confirm the actually effective config file path.
- On this machine, the effective configuration file is a symlink to the file with the same name under `~/dev/bunklaw`.
- If this configuration file changes, commit and push the corresponding config file updates under `~/dev/bunklaw`.

## Expected Output

- Learning questions: provide structured explanations (concepts, module relationships, configuration meanings, and call flows).
- Troubleshooting questions: provide root cause analysis, fix plan, verification results, and follow-up recommendations.
- Before modifying any configuration or file, first explain the change points and impact scope.
