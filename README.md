<div align="center">
<img width="1200" height="475" alt="GHBanner" src="https://github.com/user-attachments/assets/0aa67016-6eaf-458a-adb2-6e31a0763ed6" />
</div>

# SkillVouch - Full Stack Application

## Project Structure

```
SkillVouch/
├── Frontend/          # React/Vite frontend application
│   ├── components/    # React components
│   ├── services/      # Frontend services
│   ├── public/        # Static assets
│   └── package.json   # Frontend dependencies
├── Backend/           # Node.js/Express backend API
│   ├── ai/           # AI-related modules
│   ├── routes/       # API routes
│   ├── services/     # Backend services
│   ├── sql/          # Database schemas
│   └── package.json  # Backend dependencies
└── package.json      # Root package.json with scripts
```

## Setup Instructions

**Prerequisites:** Node.js

1. Install all dependencies:
   ```bash
   npm run install:all
   ```

2. Start development servers:
   ```bash
   npm run dev
   ```

3. Or start individually:
   ```bash
   # Frontend only
   npm run dev:frontend
   
   # Backend only
   npm run dev:backend
   ```

4. Build for production:
   ```bash
   npm run build:frontend
   ```

## Environment Variables

Copy `.env.example` to both `Frontend/.env` and `Backend/.env` and configure accordingly.

View your app in AI Studio: https://ai.studio/apps/drive/1E_eHHCq-abAdilb_hp_uh1l8SvYMX1ON
