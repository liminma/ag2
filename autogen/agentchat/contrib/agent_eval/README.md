Agents for running the [AgentEval](https://docs.ag2.ai/latest/docs/blog/2023/11/20/AgentEval/) pipeline.

AgentEval is a process for evaluating a LLM-based system's performance on a given task.

When given a task to evaluate and a few example runs, the critic and subcritic agents create evaluation criteria for evaluating a system's solution. Once the criteria have been created, the quantifier agent can evaluate subsequent task solutions based on the generated criteria.

See our [blog post](https://docs.ag2.ai/blog/2024-06-21-AgentEval) for usage examples and general explanations.
