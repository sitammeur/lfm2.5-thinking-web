# LFM-2.5 Thinker 🤖

This is a simple web app that demonstrates how to use the [LFM2.5-1.2B-Thinking](https://huggingface.co/LiquidAI/LFM2.5-1.2B-Thinking-ONNX) model by LiquidAI in the browser using [Transformers.js](https://huggingface.co/docs/transformers.js) and ONNX Runtime Web. The application allows users to chat with the LFM2.5-1.2B-Thinking model, a 1.2 billion parameter reasoning LLM, and receive real-time responses — all running locally in the browser via WebGPU.

## Project Structure

The project is structured as follows:

- `public/`: Static assets like images, icons, and fonts.

- `src/`: Core source code for the application.
  - `components/`: Reusable React components for the application.
    - `icons/`: Icon components for the application.
      - `ArrowRightIcon.jsx`: Arrow right icon component.
      - `BotIcon.jsx`: Bot icon component.
      - `BrainIcon.jsx`: Brain icon component for the thinking indicator.
      - `StopIcon.jsx`: Stop icon component.
      - `UserIcon.jsx`: User icon component.

    - `Chat.jsx`: Chat component for displaying chat messages.
    - `Progress.jsx`: Progress component for displaying progress bar.

  - `styles/`: CSS files for styling the application.
    - `index.css`: Global CSS styles for the application.
    - `Chat.css`: CSS styles for the chat interface.

  - `worker.js`: Web Worker for running the LFM model using Transformers.js.
  - `App.jsx`: Main React component for the application.
  - `main.jsx`: Entry point for the application.

- `.gitignore`: Specifies which files and directories should be ignored by Git.
- `LICENSE`: Project licensing information.
- `README.md`: Project documentation and setup instructions.
- `index.html`: Main HTML file for the application.
- `package.json`: Project dependencies and script configuration.
- `eslint.config.js`: ESLint configuration file.
- `postcss.config.js`: PostCSS configuration file.
- `tailwind.config.js`: Tailwind CSS configuration file.
- `vite.config.js`: Vite configuration file for the project.

## Technologies Used

- **HTML**: Standard markup language for creating web pages.
- **Tailwind CSS**: Utility-first CSS framework for styling web applications.
- **JavaScript**: High-level programming language for building web applications.
- **React**: JavaScript library for building user interfaces.
- **Transformers.js**: JavaScript library for running Hugging Face models in the browser.
- **Marked**: Markdown parser for rendering model responses.
- **DOMPurify**: DOM-only XSS sanitizer for secure HTML rendering.
- **Better React MathJax**: React component for rendering MathJax in the browser.

## Getting Started

To get started with this project, follow the steps below:

1. Clone the repository: `git clone https://github.com/sitammeur/lfm2.5-thinking-web.git`
2. Change the directory: `cd lfm2.5-thinking-web`
3. Install the required dependencies: `npm install`
4. Run the application: `npm run dev`

Open your local host to view the web application in your browser at `http://localhost:5173/`.

## Results

The application allows users to chat with LFM2.5-1.2B-Thinking, a large language model by LiquidAI optimized for reasoning, that operates within web browsers via 🤗 Transformers.js and ONNX Runtime Web.

To see results, please refer to the live version of the application [here](https://huggingface.co/spaces/sitammeur/LFM2.5-Thinking-WebGPU), which is deployed on Hugging Face Spaces.

## Contributing

Contributions are welcome! If you would like to contribute to this project, please raise an issue to discuss the changes you would like to make. Once the changes are approved, you can create a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact

If you have any questions or suggestions regarding the project, feel free to reach out to me on my GitHub profile.

Happy coding! 🚀
