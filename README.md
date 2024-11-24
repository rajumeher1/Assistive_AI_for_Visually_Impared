                                Assistive AI for Visually Impaired

Project Overview

This project provides an AI-powered assistive tool designed to help visually impaired individuals interact with and understand their surroundings. By leveraging the Google Gemini API, the application can offer real-time scene understanding, text-to-speech conversion, and object detection, allowing users to navigate and comprehend their environment more effectively.

The project uses Streamlit for creating an interactive web application and integrates Google Generative AI (Gemini) for scene description and text generation. Additionally, Google Text-to-Speech (gTTS) is utilized to convert text into speech for better accessibility.


Key Features:

1. Real-Time Scene Understanding: The application generates textual descriptions of uploaded images, enabling users to understand the context of their surroundings.
2. Text-to-Speech Conversion: The app extracts text from images and reads it aloud, making written content more accessible to visually impaired users.
3. Object and Obstacle Detection: Identifies objects and obstacles within images for safer navigation (future improvements 4. planned for real-time obstacle detection).
4. Personalized Assistance for Daily Tasks: Recognizes items, provides task-specific guidance, and offers contextual information from uploaded images.

            --------------------------------------------------------------------------------------------


Table of Contents
    1.  Technologies Used
    2.  How to Use
    3.  API Setup
    4.  Features and Functionality
    5.  Known Issues

            --------------------------------------------------------------------------------------------
        
1. Technologies Used

    *   Google Gemini API: A powerful generative AI model by Google for scene understanding and text generation.
    *   Streamlit: A Python library used for creating the interactive web interface.
    *   Google Text-to-Speech (gTTS): A Python library that converts text to speech for better accessibility.
    *   Pillow (PIL): Python Imaging Library for handling image uploads and manipulation.

2.  How to Use

    *   Upload an Image: Click the "Upload an Image" button on the Streamlit interface and select an image file from your local system.
    *   Process the Image: Click the "Process the Image" button to process the uploaded image.
    *   The app will analyze the image and provide a description of the scene.
    *   If the image contains text, the app will extract it and convert it to speech.
    *   Text-to-Speech: The extracted text will be read aloud for better accessibility.
    *   Real-Time Scene Understanding: The application will generate a textual description of the uploaded image to help the user understand the scene.

3.  API Setup

Google Gemini API Key:

    *   To access the Google Gemini API, you'll need to place your API key inside the keys/ folder in the project directory. The key should be named gemini.txt.

    *   Make sure to follow the steps to obtain a Gemini API key from Google and configure it properly for your environment.

4.  Features and Functionality

Real-Time Scene Understanding
    *   The app uses the Google Gemini API to generate a detailed, one-line description of the uploaded image. This helps visually impaired individuals understand the context of the image in terms of objects, people, and other elements.

Text-to-Speech Conversion
    *   Text in the image is converted into speech using Google's Text-to-Speech (gTTS) API. This functionality enables users to hear the content of images containing written text, such as signs, labels, or any other visible text.

Object and Obstacle Detection
    *   Although the current version focuses primarily on scene description and text-to-speech, future improvements will include real-time object and obstacle detection for safer navigation, helping visually impaired individuals avoid obstacles while moving in their environment.

Personalized Assistance for Daily Tasks
    *   For future versions, the app aims to provide personalized assistance for specific tasks like identifying grocery items, reading labels, or even recognizing facial expressions.

5. Known Issues

    *   Real-Time Obstacle Detection: The current version lacks real-time obstacle detection for safe navigation, but this feature is under development.

    *   Text Extraction Accuracy: The accuracy of text extraction (OCR) may vary depending on the clarity of the text and the image quality. Enhancements to improve accuracy are planned for future releases.

    *   Scene Description Limitations: The scene understanding is limited to simple one-line descriptions. More detailed analysis and context are planned for future improvements.

            --------------------------------------------------------------------------------------------

Contributing

If you’d like to contribute to the project, feel free to fork the repository, submit issues, and create pull requests. Please ensure that your contributions align with the project goals and follow the general coding guidelines in the repository.

            --------------------------------------------------------------------------------------------

Conclusion

This project aims to create a user-friendly assistive AI tool that can help visually impaired individuals interact with and understand their environment more effectively. By providing real-time scene understanding, text-to-speech conversion, and object detection, the tool empowers users with more autonomy in their daily lives.

Your feedback and suggestions for improvement are always welcome!