# Arctic Avatar
![Arctic Avatar](arctic_avatar.png)

## Description
Arctic Avatar is an interactive application built with Streamlit that allows users to interact with **Snowflake Arctic** through text or voice. The application features an animated avatar that responds to user inputs, providing a more engaging and visually appealing experience.

## Features
- **Text and Voice Input**: Users can input their queries via text or voice recording.
- **Animated Avatar**: The animated avatar responds to user inputs, synchronizing its movements with the generated text.
- **Replicate Integration**: Utilizes the Replicate service to generate language model responses.

## Installation

1. Clone this repository:
    ```sh
    git clone https://github.com/your-username/arctic-avatar.git
    cd arctic-avatar
    ```

2. Create a virtual environment and install the dependencies:
    ```sh
    python3 -m venv env
    source env/bin/activate
    pip install -r requirements.txt
    ```

3. Configure Replicate credentials:
    - Create a `secrets.toml` file in the `.streamlit` directory with your Replicate API token:
      ```toml
      [secrets]
      REPLICATE_API_TOKEN = "your_replicate_token"
      ```

## Usage

1. Run the Streamlit application:
    ```sh
    streamlit run app.py
    ```

2. Open your web browser and navigate to `http://localhost:8501` to interact with the application.

## Project Structure

```plaintext
.
├── .streamlit
│   └── secrets.toml
├── app.py
├── requirements.txt
├── arctic_avatar.png
└── README.md

