Notes:
===
Been spending a lot of time learning about JS rendered front end development and SSR (Server Side Rendering), hydration and partial hydration of Client Side data, asyncronous data fetching, etc. I know that Svelte was developed by the Vercel team with these things in mind, and it's build on my favorite tool: Vite. So I know I have to mess with it - forked this repo to get familiar with it when I have spare time. I thought their GraphQL queries for pulling Shopify product data were especially elegant, and it looks like Svelte might be borrowing some of Vue's more focused scoped coding practices. I'm still liking SolidJS more for server-side projects, but Svelte definitely looks good.

---
...

# SvelteKit Commerce

<img width="843" alt="sveltekit-commerce" src="https://user-images.githubusercontent.com/9113740/176811983-2bc99cac-e994-4c65-b8b2-5e2f845b3b8e.png">

SvelteKit Commerce is an open-source, customizable ecommerce template built with SvelteKit, Tailwind CSS, and Shopify.

## Deploy Your Own

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?demo-title=SvelteKit%20Commerce&demo-description=An%20all-in-one%20starter%20kit%20for%20high-performance%20e-commerce%20sites%20built%20with%20SvelteKit.&demo-url=https%3A%2F%2Fsveltekit-commerce.vercel.app&demo-image=%2F%2Fimages.ctfassets.net%2Fe5382hct74si%2F3XUMB0FmezRUsbDFLZzqw9%2Fef0f3ad80a5e2e02dca2e2f94a3f174f%2FCleanShot_2022-07-29_at_17.13.28_2x.png&project-name=SvelteKit%20Commerce&repository-name=sveltekit-commerce&repository-url=https%3A%2F%2Fgithub.com%2Fvercel%2Fsveltekit-commerce)

This template includes read-only Shopify credentials by default, but you can add the following environment variables to make it your own:

- `VITE_SHOPIFY_API_ENDPOINT`
- `VITE_SHOPIFY_STOREFRONT_API_TOKEN`

## Running Locally

- `pnpm install`: Install dependencies
- `pnpm dev`: Start development server
- `pnpm build`: Create a production build of the app
- `pnpm preview`: Preview the production build
