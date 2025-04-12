# Document Analysing Agent

This project implements a document-analyzing agent named Alfred, inspired by Batman's butler. Alfred can extract text from images, perform calculations, and respond to user queries using a state-based graph system.

## Features

- **Text Extraction**: Extract text from image files using a multimodal model.
- **Computation Tools**: Perform basic calculations like division.
- **State Management**: Uses a state graph to manage control flow and decision-making.
- **Interactive Responses**: Provides intelligent responses based on user inputs and tools.


## Usage

1. Install the required dependencies.
2. Run the `main.py` script to initialize and execute the agent.
3. Provide an image file or query to interact with Alfred.

## Logic Diagram

The logic diagram below illustrates the flow of the state graph used in this project:


## Example

```python
# Example usage
messages = [HumanMessage(content="Extract text from the provided image.")]
react_graph.invoke({"messages": messages, "input_file": "example_image.png"})
```

## Dependencies
- `langchain_openai`
- `langchain_core`
- `IPython`