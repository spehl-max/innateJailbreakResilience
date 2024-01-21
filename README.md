# Innate Jailbreak Resilience

## Introduction
Innate Jailbreak Resilience is a project exploring methods to prevent jailbreaking in large language models (LLMs). Jailbreaking occurs when a user crafts prompts that elicit restricted information from an LLM, such as instructions for treating a disease. This project examines a novel approach by tweaking the user's prompt to "wake up" the LLM from a jailbreaking attempt using a totem of three random nouns.

## Methodology

### Prompt Engineering
I modified a jailbreak prompt to make GPT-4 output restricted information. By injecting a totem of three random nouns into the user's prompt and adding specific instructions, I assessed the LLM's ability to adhere to its programmed policies.

### Experiment
The experiment involved changing the position of the totem within the prompt and observing the LLM's response. The goal was to determine the effectiveness of the totem in preventing the LLM from breaking its restrictions.

## Results
The study found that the placement of the totem noticeably impacts the LLM's response. Placing the totem towards the end of the prompt was more effective in preventing jailbreak scenarios.

## Discussion and Conclusion
Though the sample size was small, the findings suggest that using random nouns as a totem could be a viable method to enhance LLM resilience against jailbreaking. The project is documented in a [Google Colab](https://colab.research.google.com/github/spehl-max/innateJailbreakResilience/blob/main/Innate_Jailbreak_Resilience.ipynb) for further exploration and contributions.

*Note: The research and findings are based on a limited sample and should be further investigated.*
