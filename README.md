# HTML to ADF Converter

A lightweight npm package that simplifies the process of converting HTML strings from your editor into Atlassian Document Format (ADF). Ideal for users working with Jira REST API for posting, putting comments, or updating fields that require ADF formatting.

## Features

- **Effortless Conversion:** Easily transform HTML code into ADF format with a single function call.
- **Jira Integration:** Streamline your Jira workflow by ensuring your content is in the required ADF structure.
- **Developer-Friendly:** Simple to use, allowing developers to focus on their work without worrying about ADF formatting intricacies.

## Installation

```bash
npm install html-to-adf-converter
```

## Usage
```bash
const { convertToADF } = require('html-to-adf-converter');

const htmlString = '<p>Your HTML content here</p>';
const adfResult = convertToADF(htmlString);

console.log(adfResult);
```

## Contributing


Found a bug or have a feature request? [Open an issue](https://github.com/package-provider/html-to-adf-converter/issues/1) or submit a pull request. Contributions are welcome and appreciated!

## 🌐 Connect with Me

Let's stay connected! Feel free to reach out, ask questions, or just say hello. You can find me on:

- [Email](providerpackage@gmail.com)

Looking forward to connecting with you! 🚀



