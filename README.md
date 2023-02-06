## What is it? 

This is a boilerplate project with Next.js v10 and Tailwind v2. 

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Coding Style

We use ESLint and Prettier to ensure the coding style is always the same.

### Configure eslint

To make ESLint errors visible in VSCode, you need to install the [ESLint plugin](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint).

I also recommend you tell VSCode to auto-fix ESLint errors on Save. To do so, create a `.vscode/settings.json` file with the following content:

```json
{
	"editor.codeActionsOnSave": {
		"source.fixAll.eslint": true
	}
}
```

### Configure Prettier

Now let's configure VSCode to actually format our code on save according to our prettier configuration file. To do so, install VSCode's [prettier plugin](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode).

Then, you can tell VSCode to format the code on Save by editing our `.vscode/settings.json` file:

```json
{
	"editor.codeActionsOnSave": {
		"source.fixAll.eslint": true
	},
	"editor.formatOnSave": true,
	"editor.defaultFormatter": "esbenp.prettier-vscode"
}
```
## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/import?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.

