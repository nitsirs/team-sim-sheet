# Executive Decision Portal

A voting application for team decision-making scenarios.

## Deploy to Vercel

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone)

### Quick Deploy Steps:

1. **Install Vercel CLI** (optional):
   ```bash
   npm i -g vercel
   ```

2. **Deploy**:
   ```bash
   vercel
   ```

3. **Or use the Vercel Dashboard**:
   - Go to [vercel.com](https://vercel.com)
   - Click "New Project"
   - Import this Git repository
   - Click "Deploy"

That's it! Your app will be live on Vercel.

## Features

- Team-based voting system
- Multiple scenario support
- Vote locking mechanism (prevents duplicate votes)
- Google Forms integration for data collection
- Fully responsive design
- Modern gradient UI with animations

## Local Testing

Simply open `index.html` in your browser. No build process required.

## Configuration

Google Form settings are in `index.html` (lines 126-129). Update these if you create a new form:
- `formURL`: Your Google Form response URL
- `entryTeam`: Team field entry ID
- `entryScen`: Scenario field entry ID  
- `entryVote`: Vote field entry ID
