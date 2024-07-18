# Drag-and-Drop 3D Viewer

This project is a React application that allows users to drag and drop GLB files to visualize them using `react-three-fiber`.

## Features

- Drag and drop interface for uploading GLB files
- Visualization of GLB files using `react-three-fiber`
- Automatic loading of GLB and texture files

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/geyang/drag-and-drop-3D-viewer.git
    cd drag-and-drop-3D-viewer
    ```

2. Install the dependencies:

    ```bash
    npm install
    ```

3. Run the development server:

    ```bash
    npm start
    ```

## Usage

- Open your browser and navigate to `http://localhost:3000`.
- Drag and drop a GLB file into the designated area to visualize it.

## About This Project

This project was developed with the assistance of ChatGPT, a large language model created by OpenAI. ChatGPT is trained on a diverse range of internet text but does not know specifics about which documents were part of its training set. It generates human-like text based on the input it receives, providing assistance in generating code, solving errors, and explaining concepts.

### How It Works

1. **Initial Setup**:
    - Set up a new React project using `create-react-app`.
    - Install necessary dependencies like `three`, `@react-three/fiber`, and `@react-three/drei`.

2. **File Drag-and-Drop Functionality**:
    - Implement a custom React hook, `useFileDrop`, to handle drag-and-drop events.
    - Create a `FileDropZone` component to provide the drag-and-drop interface.

3. **3D Visualization**:
    - Use `react-three-fiber` to render the 3D scene.
    - Implement a `GLBViewer` component to load and display GLB files.

4. **Integrating Everything**:
    - Combine all components and hooks to create a seamless user experience for dragging, dropping, and viewing 3D models.

### ChatGPT's Role

ChatGPT assisted in the development process by:
- Providing code snippets and explanations.
- Debugging errors and suggesting improvements.
- Guiding through the integration of various libraries and tools.

### About ChatGPT

ChatGPT is powered by the GPT-4 architecture, a state-of-the-art language model designed by OpenAI. It is trained using reinforcement learning from human feedback, among other techniques, to generate text that is coherent, contextually relevant, and grammatically correct.

For more information about ChatGPT, visit the [OpenAI website](https://openai.com).

## License

This project is licensed under the MIT License.

