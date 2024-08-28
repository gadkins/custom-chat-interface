# Custom Chat Interface (Claude, GPT-4, or Gemini)

![Custom Chat Interface](/public/assets/screenshot.png)

## Prerequisites
- Git
- Docker

## Installation Steps
Follow these steps to set up LibreChat with the default configuration:

### Clone the Repository
```
git clone https://github.com/danny-avila/LibreChat.git
```

### Navigate to the LibreChat Directory
```
cd LibreChat
```

### Create a .env File from .env.example
```
cp .env.example .env
```

### Start LibreChat
```
docker compose up -d
```

### Access LibreChat
Visit `http://localhost:3080/` in your browser.
