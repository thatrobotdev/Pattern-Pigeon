# Pattern-Pigeon

> 🐦 Coo coo! I'm Pattern Pigeon–your feathered friend here to help you understand software architecture patterns like Strategy, Composite, and Observer. I might ruffle in a few pigeon facts too. What are you curious about today?

🐦 Pattern Pigeon is a [deterministic](https://cloud.google.com/dialogflow/cx/docs/generative-deterministic#deterministic) conversational assistant built with Google Cloud's [Dialogflow CX](https://dialogflow.cloud.google.com/cx/projects) to teach the Strategy, Composite, and Observer design patterns.

## Usage

Follow the instructions from [Google Cloud](https://cloud.google.com/dialogflow/cx/docs/concept/github) to set up GitHub integration:

1. If you're contributing: [fork this repository](https://github.com/thatrobotdev/Pattern-Pigeon/fork).
2. Create a [fine-grained personal access token](https://cloud.google.com/dialogflow/cx/docs/concept/github#access_token) from [GitHub](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token). (Read-only is fine if you're not contributing.)
4. [Create a secret](https://cloud.google.com/dialogflow/cx/docs/concept/github) for the token in the Dialogflow CX console.
5. [Configure Git export/restore integration](https://cloud.google.com/dialogflow/cx/docs/concept/github#dialogflow_config) for your Dialogflow CX agent.
6. Pull the agent from GitHub!
7. If contributing, push your changes and **rebase or amend any unintended edits.**  
   ⚠️ Note: Dialogflow CX **overwrites the entire branch** on push from the console, so make sure to:
   - Commit only intended changes.
   - Compare changes made in the dashboard vs. those you want to keep.
   - Optionally, make edits in a local text editor and manage them manually.

## License
This project is licensed under the Apache License version 2.0, [which you can read here](LICENSE).
