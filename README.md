# Alexa Custom Skills with AWS Lambda.
<img src="https://m.media-amazon.com/images/G/01/mobile-apps/dex/alexa/alexa-skills-kit/tutorials/quiz-game/header._TTH_.png" />

---

## Introduction

This repository provides a guide on developing custom skills for Alexa using AWS Lambda. It aims to help you understand the process of creating intents to communicate effectively with Alexa, offering insights into configurations and setup to seamlessly integrate your code.

## Getting Started

To get started with Alexa custom skills development and AWS Lambda integration, follow these steps:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/math-ferreira/alexa-custom-skills-awslambda.git
   cd alexa-custom-skills-awslambda
   ```

2. **Install Dependencies:**
   Ensure that you have the necessary dependencies installed. Refer to the documentation for details.

3. **Configuration:**
   Modify the configuration files to suit your requirements. This may include authentication credentials, skill settings, and other environment-specific configurations.

4. **Developing Intents:**
   Explore the `intents` directory to understand how to structure and create intents for your Alexa skill. Follow best practices and customize according to your use case.

## Deployment

Deploying your Alexa custom skill involves setting up AWS Lambda and configuring your Alexa Developer Console. Follow these general steps:

1. **AWS Lambda Setup:**
   - Create a new Lambda function.
   - Upload your code or link to your repository.
   - Configure the necessary environment variables.

2. **Alexa Developer Console:**
   - Create a new Alexa skill on the [Alexa Developer Console](https://developer.amazon.com/alexa/console/ask).
   - Configure your skill settings, including the endpoint URL pointing to your AWS Lambda function.

3. **Testing:**
   Test your skill using the Alexa Simulator or a physical Alexa-enabled device. Ensure that the intents are correctly recognized and handled.

## License

This project is licensed under the [MIT License](LICENSE).
