# promptevolution
![Prompt Evolution](promptevolution.png)

# Evolving Project Management Prompts for AI Projects

This project demonstrates Prompt Evolution (Fernando et al., 2023) by generating project management prompts tailored to AI projects. The goal here is to evolve prompts that will assist with planning, tracking, and executing AI projects effectively using my ongoing project project-manager.ai to showcase how prompt evolution can be applied to a business problem.

## Overview

Prompt Evolution uses an iterative process to evolve better prompts for a domain, in this case project management of AI initiatives. As described in "Promptbreeder: Self-Referential Self-Improvement via Prompt Evolution" (Fernando et al., 2023), it leverages a language model to generate variations of prompts, evaluates their utility, and selects the most useful prompts to propagate to the next generation.

I show how to evolve prompts that will assist with planning, tracking, and executing AI projects effectively. 

## Prompts

The prompts provided will serve as the initial population. They include project management advice for different AI project types:

- AI Assistant
- Proof of Concept (POC)
- Model Development
- Platform as a Service (PAAS)

For example, the prompt for a POC provides guidance on:

- Defining goals and constraints
- Data preparation 
- Model selection and training
- Evaluation metrics
- Documentation and stakeholder communication

## Evolution 

The prompts will be iteratively evolved to improve their utility using:

- Mutation functions like rephrasing or elaboration
- Fitness evaluation on project management scenarios
- Selection and recombination of fitter prompts

This will yield prompts tuned for managing AI projects, like:

*"For an AI assistant, ensure frequent communication with end users during development. Collect feedback early and often to validate capabilities and usability."*

## Results

Evolved prompts will provide useful project management advice tailored to different AI initiatives like:

- Release planning for iterative development 
- Reporting timelines and milestones to stakeholders
- Budgeting for data acquisition and infrastructure
- Assessing technical debt and documentation needs

## References

Fernando, C., Banarse, D., Michalewski, H., Osindero, S., & Rocktäschel, T. (2023). Promptbreeder: Self-Referential Self-Improvement via Prompt Evolution. arXiv preprint arXiv:2309.16797.

### License
promptevolution is released under the MIT License.