# vibes-plusplus

## Evaluation framework for AI Dev Tools

### What developers want from AI Dev Tools

- **Accurate**: Generate correct code.
- **Fast**: Get the job done quickly.
- **Easy to use**: Easy to use and understand.
- **Steerable**: Customize the output to the user's needs and preferences.
- **Testable**: Generate testable code so that I know it will work for my environment.


### How to evaluate AI Dev Tools

- **Accuracy**: HumanEval for the model and SWE bench for the agents
- **Speed**: Measure the time it takes to complete a task.
- **Ease of use**: Measure the ease of use of the tool.
- **Steerability**: Measure the ability to customize the output to the user's needs and preferences.
- **Testability**: Measure the ability to generate testable code.

#### What impacts accuracy?

- **Model**: The LLM being used to generate the code.
- **Context**: The context being used to generate the code. Is the retrieval of context from other files working?
- **Prompt**: The prompt being used to generate the code. Are the prompts making sure production level high quality code is generated?

#### What impacts speed?

- **Model**: The LLM being used to generate the code.
- **Caching**: Whether the tool is using caching to speed up the generation process.

#### What impacts ease of use?

- **UI/UX**: The UI/UX of the tool.
- **Documentation**: The documentation of the tool.

#### What impacts steerability?

- **Prompt**: The prompt being used to generate the code.
- **Custom rules**: The custom rules being used to generate the code.

#### What impacts testability?

- **Test framework**: The test framework being used to run the generated code.
- **Test cases**: The test cases being used to test the generated code.
