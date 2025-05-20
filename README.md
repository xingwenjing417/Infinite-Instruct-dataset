# Infinite-Instruct Dataset

Welcome to the Infinite-Instruct Dataset! This is a high-quality question-answer pair synthesis framework designed to enhance the code generation capabilities of large language models (LLMs).

## Dataset Overview

Infinite-Instruct is an automated framework focused on improving the internal logic of synthesized problems and the quality of synthesized code. This dataset contains high-quality programming instruction data generated through two complementary construction mechanisms:

1. **Reverse Construction** - Transforms code snippets into diverse programming problems
2. **Backfeeding Construction** - Reconstructs programming problems through knowledge graphs to enhance internal logic

## Dataset Content

This repository contains two versions of the dataset:

- **Unfiltered Version** - Original synthesized question-answer pairs
- **Filtered Version** - High-quality question-answer pairs filtered through a static analysis pipeline

### Data Format

Each sample contains the following fields:

```json
{
  "prompt": "Question text",
  "response": "Answer/code solution",
  "type": "Question type"
}
```
