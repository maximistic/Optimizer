# Scope and Functional Requirements

The goal of this project is to create a lightweight text optimization tool for English language improvement that provides core functionalities similar to popular platforms like Grammarly, with significant differences to prioritize simplicity, speed, and accessibility for users. The website will help users improve English proficiency by offering the following core functions:
    - Plagiarism Detection: Basic plagiarism checks to ensure content originality.
    - Text Rephrasing: Transformation from informal to formal language, supporting different levels of rephrasing.
    - Grammar Correction: Correcting common grammar errors and typos.
    -  User-Focused Learning: Tips and explanations for grammar errors or rephrasing choices, beneficial for language learners.

    - *Input* :: A sentence or passage in casual or incorrect English
    - *Output* :: A polished, correct, and grammatically optimized version of the input
    - *Requirements* ::
        - **Real Time Optimization** 
        - **Responsive User Design**
        - **Scalability**
    - Some other Functionalities (For reference):
        - Text Rephrasing
        - Grammar Correction
        - Summarization
        - Plagiarism detection
        - Question Answering (Not necessarily)
        - Translation (Out of scope for now)

# Models and other Specifications
    - T5 (Text-To-Text Transfer Transformer) Base is versatile and is relatively lightweight compared to large language models (LLMs), which was designed to approach NLP tasks as text-to-text problems. 
    - https://huggingface.co/google-t5/t5-base