# End-to-End Text Summarizer Project 📃

This project aims to develop an end-to-end solution for text summarization, enabling the generation of concise summaries from textual data. The project leverages AWS services and follows a structured workflow to ensure efficient summarization of information.

## Workflows 🔄

The following workflows are involved in the text summarizer project:

1. 📝 Update `config.yaml`: Modify the configuration file (`config.yaml`) to customize settings based on specific project requirements.
2. 📝 Update `params.yaml`: Adjust the parameters file (`params.yaml`) to configure specific summarization parameters according to your needs.
3. 📝 Update entity: Modify the entity file to include relevant entities for the summarization process.
4. 📝 Update the configuration manager in `src/config`: Make necessary updates to the configuration manager in the source code (`src/config`) to ensure proper integration of project components.
5. 📝 Update the components: Update individual components of the text summarizer, such as data preprocessing, feature extraction, and summarization algorithms, as required.
6. 📝 Update the pipeline: Enhance the pipeline that orchestrates the flow of data through the summarization process.
7. 📝 Update `main.py`: Modify the main script file (`main.py`) to incorporate any changes or improvements to the overall functionality of the text summarizer.
8. 📝 Update `app.py`: Make necessary updates to the app script file (`app.py`), which is responsible for running the text summarizer as a web application.

## How to Run ▶️

Follow the steps below to run the project:

##Step 1: Clone the Repository 📥

Clone the project repository using the following command:

```bash
git clone https://github.com/somanathkshirsagar/End_to_end_Text-Summarizer-Project-With-AWS-Services.git
cd End_to_end_Text-Summarizer-Project-With-AWS-Services

##Step 2: Create Conda Environment 🐍

After opening the repository, create a Conda environment using the provided command:
conda create -n summary python=3.8 -y
conda activate summary

##Step 3: Install Requirements 📦

Install the required dependencies by running the following command:
pip install -r requirements.txt

##Step 4: Run the Project 🚀

Finally, execute the following command to start the text summarizer:
python app.py

##Step 5: Access the Application 🌐

Open your web browser and enter the localhost and port to access the running application.

Author 🧑‍💻

Somnath Kshirasagar
Data Scientist
Email: somanathtk198@gmail.com

AWS CI/CD Deployment with GitHub Actions ☁️🔧

This project includes AWS CI/CD deployment using GitHub Actions. The deployment process involves the following steps:

🔑 Login to AWS Console.
🧑‍💼 Create IAM User for Deployment:
✅ EC2 access: It is a virtual machine.
✅ ECR: Elastic Container Registry to save your Docker image in AWS.
Deployment Description 🚀

The deployment process can be summarized as follows:

🐳 Build a Docker image of the source code.
📤 Push your Docker image to ECR.
🚀 Launch your EC2 instance.
📥 Pull your image from ECR on


