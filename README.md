

---

# WhatsApp Chat Analyzer

## Overview
The WhatsApp Chat Analyzer is a Python-based tool that helps you gain insights from your WhatsApp chat history. By leveraging pandas for data analysis, this tool can generate various statistics and visualizations about your chat patterns, such as the most active participants, daily activity, and word frequency.

## Features
- **Message Count:** Analyze the number of messages sent by each participant.
- **Activity Patterns:** Visualize daily and hourly message trends.
- **Word Frequency:** Identify the most commonly used words in the chat.
- **Message Length:** Calculate the average length of messages for each participant.
- **Response Time:** Analyze the average response time between participants.

## Requirements
- Python
- pandas
- matplotlib
- seaborn
- streamlit
- emoji

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/whatsapp-chat-analyzer.git
   cd whatsapp-chat-analyzer
   ```

2. Install the required dependencies:
   ```sh
   pip install -r requirement.txt
   ```

## Usage
1. Export your WhatsApp chat history from the WhatsApp app:
   - Open the chat you want to analyze.
   - Tap on the three dots in the top right corner.
   - Select "More" > "Export chat".
   - Choose to export without media.
   - Save the exported file to your local system.
/
2. Run the analyzer:
   ```sh
   streamlit run app.py
   ```
3. Upload the .txt file of chat in the sidebar of web app.
   
4. The tool will generate various statistics and visualizations based on the chat data.


## Contributing
Contributions are welcome! Please feel free to submit a pull request or open an issue if you have any suggestions or improvements.

## Contact
For any questions or feedback, please contact Pranav Mittal at pranavmittal@gmail.com.

# Link : https://whatsapp-chat-analyzer-qted.onrender.com
