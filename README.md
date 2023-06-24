# AI Avatar
A web-based application that uses a custom-trained Stable Diffusion model to generate an AI avatar of me based on your prompt. This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app). It is deployed with Railway at [sarahdahippo-ai-avatar.up.railway.app](sarahdahippo-ai-avatar.up.railway.app).

## What's Next
- Provide a few buttons representing preset prompts that auto populate the prompt input field
- Break down the broader prompt input into smaller fields (e.g., artist, medium, vibe, descriptors) to give users ideas on how to write good prompts
- Let other people generate their own avatars by uploading their images so we can process them, tune a Stable Diffusion model with GPUs, and use predefined prompts to generate images

## Tech Stacks, Tools, & Concepts
- Dreamstudio
- Google Colab
- Jupyter notebooks
- HuggingFace
- Text-to-image models like Stable Diffusion and Dall-e
- Next.js

## Development
1. `git clone` the repository and change directory into it: `cd ai-avatar`
2. Install the modules `npm i`
3. Run `npm run dev` (or `yarn dev`) to launch the development server in your web browser
4. Open [http://localhost:3000](http://localhost:3000) with your browser to see the result
5. You can edit the page and watch it auto-update by modifying `pages/index.js`
6. [API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello) -- This endpoint can be edited in `pages/api/hello.js`
7. The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

### Learn More about Next.js
- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial
- The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js. Check out [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
