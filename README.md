# create-svelte

Everything you need to build a Svelte project, powered by [`create-svelte`](https://github.com/sveltejs/kit/tree/master/packages/create-svelte).

## Creating a project

If you're seeing this, you've probably already done this step. Congrats!

```bash
# create a new project in the current directory
npm create svelte@latest

# create a new project in my-app
npm create svelte@latest my-app
```

## Developing

Once you've created a project and installed dependencies with `npm install` (or `pnpm install` or `yarn`), start a development server:

```bash
npm run dev

# or start the server and open the app in a new browser tab
npm run dev -- --open
```

## Building

To create a production version of your app:

```bash
npm run build
```

You can preview the production build with `npm run preview`.

> To deploy your app, you may need to install an [adapter](https://kit.svelte.dev/docs/adapters) for your target environment.

# architecture elements

@see
[microCMS + SvelteKitでブログサイト作ってみた from YouTube](https://www.youtube.com/watch?v=MQCupW94wxk)

[microcms](https://microcms.io/)
[Tailwind-blog-template](https://github.com/davidgrzyb/tailwind-blog-template)
node v18.12.1

.env
```
MICROCMS_SERVICE_DOMAIN=your_microcms_domain
MICROCMS_API_KEY=your_microcms_api_key
```