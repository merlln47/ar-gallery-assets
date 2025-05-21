# AR Gallery Assets

This repository contains assets and configuration files for the AR Gallery application.

## Structure

- `config/`  
  Contains configuration files, such as `artwork_config.json`, which defines available artworks, settings, and API endpoints for the app.

- `images/`  
  Intended for static images or sample artwork. (User-generated images are uploaded at runtime and not stored here.)

- `thumbnails/`  
  Intended for thumbnail versions of images for faster loading and previews.

- `videos/`  
  Intended for static video assets or placeholders. (User-generated videos are uploaded at runtime and not stored here.)

## Usage

- The app loads its configuration from `config/artwork_config.json` using the raw GitHub URL.
- Images and thumbnails can be referenced in the config file using their raw GitHub URLs.
- User-generated content (photos, videos) is managed by the app and backend, not stored in this repository.

## Notes

- This repository is public and intended for non-sensitive, non-personal assets only.
- Folders may contain a `.gitkeep` file to ensure they exist in the repository, even if empty.

---

*Created for Merlin's Mansion* 
