 Nursura Chat Assistant

Nursura is a responsive web-based chat assistant tailored to provide empathetic and practical support for teenage girls. This project uses TailwindCSS for styling and integrates with the Ollama API for generating responses from an AI model.

---

## Features

- **Responsive Design:** Optimized for various screen sizes using TailwindCSS.
- **Chat Interface:** Allows users to send and receive messages in a user-friendly format.
- **AI-Powered Responses:** Provides concise, empathetic, and practical advice using the Mistral model through the Ollama API.

---

## Prerequisites

1. **Node.js:** Ensure you have Node.js installed on your machine.
2. **Ollama API:** Install and set up the Ollama API locally. It must be accessible at `http://localhost:11434`.
3. **Web Browser:** A modern browser like Chrome, Firefox, or Edge.

---

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/Nursura.git
   cd Nursura
   ```

2. Start the Ollama API server:
   Follow the Ollama API documentation to ensure the server is running on `http://localhost:11434`.

3. Open the project:
   - Simply open the `index.html` file in your browser.

---

## Usage

1. Open the chat interface in your browser.
2. Type a message in the input field.
3. Press "Enter" or click the "Send" button to submit the message.
4. Receive an AI-generated response in real time.

---

## File Structure

```plaintext
Nursura/
├── index.html      # Main HTML file
├── README.md       # Project documentation
├── tailwind.min.css # TailwindCSS stylesheet (via CDN)
└── script.js       # Main JavaScript logic (embedded in index.html)
```

---

## Technologies Used

- **HTML5:** Structuring the chat interface.
- **CSS3 (TailwindCSS):** Styling the application for responsive and modern design.
- **JavaScript:** Handling user interactions and integrating with the Ollama API.
- **Ollama API:** Generating AI responses using the Mistral model.

---

## API Endpoint

- **Base URL:** `http://localhost:11434`
- **Endpoint:** `/api/generate`
- **Request Body:**
  ```json
  {
      "model": "mistral",
      "prompt": "Your prompt here",
      "stream": false
  }
  ```

---

## Customization

1. **Change Assistant's Tone:** Update the `prompt` in the `sendMessage()` function in `index.html` to fit different personas or use cases.
2. **Styling Adjustments:** Modify the TailwindCSS classes in the `index.html` file or use a custom stylesheet.

---

## Troubleshooting

- Ensure the Ollama API server is running locally and accessible at the specified base URL.
- Check your browser's console for any error messages.
- Verify your internet connection if TailwindCSS doesn't load correctly (via CDN).

---

## Contributing

1. Fork the repository.
2. Create your feature branch:
   ```bash
   git checkout -b feature/YourFeature
   ```
3. Commit your changes:
   ```bash
   git commit -m 'Add YourFeature'
   ```
4. Push to the branch:
   ```bash
   git push origin feature/YourFeature
   ```
5. Open a pull request.

---

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

## Acknowledgements

- [TailwindCSS](https://tailwindcss.com/)
- [Ollama API](https://ollama.com/)
