# Smart Note App

This is a simple note-taking app that uses Retrieval Augmented Generation (RAG) to enhance the note-taking experience. The app allows users to upload notes, search for specific information within their notes, and summarize their notes using AI.

## Getting Started

### Prerequisites

- Python 3.x
- An OpenAI API key (for GPT-4o-mini)
- A Pinecone API key and environment

### Installation

1. Clone the repository:
git clone https://github.com/garv-seth/appliedai.git


2. Install the required dependencies:
pip install -r requirements.txt


3. Create a `.env` file in the root directory of the project and add your OpenAI API key and Pinecone API key and environment:
OPENAI_API_KEY=your-openai-api-key
PINECONE_API_KEY=your-pinecone-api-key
PINECONE_ENVIRONMENT=your-pinecone-environment


### Usage

1. Start the Flask server:
flask run


2. Open your web browser and navigate to `http://localhost:5000`.

3. Upload your notes using the "Upload Notes" page.

4. Search for specific information within your notes using the search bar on the "Search Notes" page.

5. Summarize your notes using the "Summarize Notes" page.

## Event

This project was created for an Applied AI event hosted by Garv, Parsa, Paulo, and Sush. 
The event focused on Retrieval Augmented Generation (RAG) and its applications in note-taking apps. 
Attendees were guided through the process of building a simple note-taking app that uses RAG to enhance the note-taking experience. 
The code for this project is available on GitHub, and attendees were encouraged to modify and extend it to suit their own needs.
