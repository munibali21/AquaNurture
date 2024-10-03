# AquaNurture 
Aquanurture is an AI-powered application designed to monitor the health of aquarium fish and assist in tank management. The system utilizes YOLOv8 for real-time fish disease detection and classification, helping aquarium owners identify diseases and take early corrective actions. A camera scans the fish in the tank, and the AI model determines whether the fish is healthy or suffering from a specific disease. The application also features a chatbot that provides fish care tips and answers frequently asked questions.

Key features include:
- **Real-time Fish Disease Detection**: Detects fish types and identifies potential diseases.
- **Tank Temperature Monitoring**: Alerts users when the temperature is outside optimal conditions and offers suggestions for correction.
- **Chatbot for Fish Care**: Offers instant guidance on fish care and aquarium maintenance.
- **Multiple Tank Management**: Supports adding and managing multiple tanks, each with its unique ID and details.
  
The application is built using **Python Kivy** for the interface, **YOLOv8** for the detection model, and **MongoDB** for the database to store user and tank information.
