# Arragon Affiliates site

### Technologies used:

- [Decap CMS](https://decapcms.org/)
- [Eleventy](https://www.11ty.dev/)
- [Alpine.js](https://github.com/alpinejs/alpine)
- [Tailwind CSS](https://tailwindcss.com/)

### Setup blog reference:

https://blog.surjithctly.in/neat-stack-create-a-static-website-with-netlify-cms-eleventy-alpinejs-and-tailwindcss


### 1\. Install dependencies

```
npm install
```

### 2\. Build the project to generate the first CSS:

This step is only required the very first time.

```
npm run build
```

### 3\. Run Eleventy

```
npm run start
```

### 4\. Deploy

Pushing to main triggers deploy to Netlify. Changes made to Markdown content in production CMS on `/admin` path, will then need to be pulled into `main` branch

### Run local CMS proxy (not required for startup)

```
npx netlify-cms-proxy-server
```

This would make local proxy CMS available at `/admin`

## Author

David White ([@webdigga](https://github.com/webdigga/))
