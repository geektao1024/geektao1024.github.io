# geektao1024.github.io

The GitHub Pages repository for **GeekTao Studio**.

Primary site:

- [GeekTao Studio homepage](https://geektao1024.github.io/)

## Studio Network

The following external links use descriptive, concise anchor text so visitors and search engines can understand each destination before clicking.

- [ClaudeCode101: Chinese Claude Code tutorials and workflows](https://claudecode101.com/)  
  Focused on Claude Code tutorials, practical workflows, and AI-assisted development guidance. `claudecode101.com`  
  Primary audience: Chinese-speaking developers learning Claude Code.  
  Best entry intent: tutorials, workflows, setup guidance, and hands-on usage.

- [DeepSeek Hubs: topical discovery platform for DeepSeek content](https://deepseekhubs.com/)  
  Built for DeepSeek-related discovery, topic organization, and future product expansion. `deepseekhubs.com`  
  Primary audience: users exploring DeepSeek tools, resources, and adjacent topics.  
  Best entry intent: discovery, topic overviews, and curated DeepSeek-focused content.

- [Learn Cursor: onboarding guides and workflow training for Cursor users](https://learn-cursor.com/)  
  Covers setup, core features, use cases, and workflow improvements for Cursor. `learn-cursor.com`  
  Primary audience: users adopting Cursor for AI coding.  
  Best entry intent: onboarding, feature education, and workflow optimization.

- [Musikalis: AI music creation and soundtrack generation](https://musikalis.com/)  
  An AI music product site for songwriting, soundtrack workflows, and creative audio production. `musikalis.com`  
  Primary audience: creators, musicians, and teams producing AI-assisted music.  
  Best entry intent: music generation, soundtrack creation, and creative production workflows.

- [Suno AI Musical: Suno-based music creation workflows and use cases](https://sunoaimusical.com/)  
  Focused on Suno-driven music creation, production workflows, and AI music use cases. `sunoaimusical.com`  
  Primary audience: users evaluating or actively using Suno for music generation.  
  Best entry intent: Suno workflows, music prompts, and production-oriented use cases.

## Repository Structure

- `index.html`: GeekTao Studio homepage
- `styles.css`: shared site styles
- `404.html`: custom 404 page
- `tools/starter/index.html`: starter lab page for new static tools
- `.nojekyll`: disables default Jekyll processing on GitHub Pages

## Adding a New Tool

1. Create a new folder under `tools/`, for example `tools/json-viewer/`
2. Add the tool page and its static assets to that folder
3. Add a relevant internal link from `index.html`
4. Push to `main`

## GitHub Pages Settings

Confirm the following in the repository settings:

1. `Settings`
2. `Pages`
3. `Build and deployment`
4. `Source`: `Deploy from a branch`
5. `Branch`: `main`
6. Folder: `/ (root)`

## Site Role

This site serves as the main entry point for GeekTao Studio and is used to present:

- the studio brand
- the portfolio of live projects
- future lightweight tools and experiments
- a stable homepage for ongoing expansion
