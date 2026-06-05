# Crime Script Extractor

Next.js + TypeScript app for rule-based crime-script extraction from Korean judgment text.

The app is configured to run without an OpenAI API key. When no key is present, AI extraction is skipped and rule-based extraction remains available.

## Run Locally

```bash
npm install
npm run dev
```

Open:

```txt
http://localhost:3000
```

## Environment

No environment variables are required for rule-based mode.

Optional:

```env
OPENAI_API_KEY=
OPENAI_MODEL=gpt-4.1-mini
```

Do not commit `.env.local` or any real API key. The repository `.gitignore` excludes local environment files.

## Deploy

See [DEPLOYMENT.md](./DEPLOYMENT.md).
