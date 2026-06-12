# Taki App Assets

Public image/assets hosting for Taki apps.

Use this repo only for public images used in Firebase In-App Messaging, banners, popups, and app marketing.

## Folder Structure

```text
inapp/        Firebase In-App Messaging images
banners/      App banners and promo images
icons/        Public icons/logos only
```

## Firebase Image URL Format

After uploading an image, use this raw URL format:

```text
https://raw.githubusercontent.com/takiff507/taki-app-assets/main/inapp/your-image.webp
```

Example:

```text
https://raw.githubusercontent.com/takiff507/taki-app-assets/main/inapp/banner.webp
```

## Safe Rules

- Upload only public images.
- Do not upload `.env`, API keys, keystore files, passwords, or app source code.
- Keep banner images compressed, ideally WebP/JPG around 200–300 KB.
- Do not rename or move an image after using its URL in Firebase, otherwise the image link will break.
