# AI Calculator Notes

A smart calculator application that combines traditional calculation capabilities with AI-powered features for note-taking and mathematical assistance.

## Features

- Basic calculator operations
- AI-powered mathematical assistance using Google's Generative AI
- Note-taking capabilities
- Modern and intuitive user interface
- Real-time calculations
- History tracking

## Tech Stack

### Frontend
- React.js with TypeScript
- Vite for build tooling
- Tailwind CSS for styling
- Modern UI components
- Responsive design

### Backend
- Python 3.x
- FastAPI framework
- Google Generative AI integration
- Pydantic for data validation
- Uvicorn ASGI server

## Project Structure

```
AI-Calculator-Notes/
├── AI-Calculator-Frontend/     # React frontend application
│   ├── src/
│   │   ├── components/        # Reusable UI components
│   │   ├── screens/          # Page components
│   │   ├── lib/             # Utility functions
│   │   └── assets/          # Static assets
│   └── public/              # Public static files
│
└── AI-Calculator-Backend/     # FastAPI backend application
    ├── apps/                # Application modules
    ├── main.py             # Application entry point
    ├── schema.py           # Data models
    └── constants.py        # Configuration constants
```

## Getting Started

### Prerequisites
- Node.js (v14 or higher) for frontend
- Python 3.x for backend
- npm or yarn
- Git
- Google Cloud API key for AI features

### Installation

1. Clone the repository
```bash
git clone https://github.com/yourusername/AI-Calculator-Notes.git
cd AI-Calculator-Notes
```

2. Install Frontend Dependencies
```bash
cd AI-Calculator-Frontend
npm install
```

3. Install Backend Dependencies
```bash
cd ../AI-Calculator-Backend
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
pip install -r requirements.txt
```

4. Environment Setup
- Create a `.env` file in the backend directory with your Google Cloud API key:
```
GOOGLE_API_KEY=your_api_key_here
```

5. Start the Development Servers

Frontend:
```bash
cd AI-Calculator-Frontend
npm start
```

Backend:
```bash
cd AI-Calculator-Backend
source venv/bin/activate  # On Windows use: venv\Scripts\activate
uvicorn main:app --reload
```

The application will be available at:
- Frontend: http://localhost:5173
- Backend API: http://localhost:8000

## Screenshots

[Add your application screenshots here]

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
