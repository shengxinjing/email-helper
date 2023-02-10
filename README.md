# [EmailHelper](https://email-helper.vercel.app/)

This project generates emails for you using AI.

[![](./public/screenshot3.png)](https://email-helper.vercel.app/)

## Support
`English`, `Simplified Chinese`, `Traditional Chinese`, `Japanese`, `Italian`, `German`, `Spanish`,`French`,`Dutch` ,`Korean`,`Khmer`, `Hindi`

PR welcome

## How it works

Inspired by [TwtterBio](https://github.com/Nutlope/twitterbio) and [Danny Richman](https://twitter.com/DannyRichman/status/1598254671591723008?ref_src=twsrc%5Etfw%7Ctwcamp%5Etweetembed%7Ctwterm%5E1598254671591723008%7Ctwgr%5Eb7deab6eb03d86a1b9ac13f7e38cdeab57a40cbb%7Ctwcon%5Es1_&ref_url=https%3A%2F%2Fwww.buzzfeednews.com%2Farticle%2Ftomwarren%2Fai-app-dyslexic-email-writer-help)

Powerd by [OpenAI](https://openai.com/), [Next.js](https://nextjs.org/), [Vercel](https://vercel.com/) and [Tailwind CSS](https://tailwindcss.com/).

This project uses the [OpenAI GPT-3 API](https://openai.com/api/) (specifically, text-davinci-003) and [Vercel Edge functions](https://vercel.com/features/edge-functions) with streaming. It constructs a prompt based on the form and user input, sends it to the GPT-3 API via a Vercel Edge function, then streams the response back to the application.

Video and blog post coming soon on how to build apps with OpenAI and Vercel Edge functions!

## Running Locally

After cloning the repo, go to [OpenAI](https://beta.openai.com/account/api-keys) to make an account and put your API key in a file called `.env`.

Then, run the application in the command line and it will be available at `http://localhost:3000`.

```bash
npm run dev
```

## One-Click Deploy

Deploy the example using [Vercel](https://vercel.com?utm_source=github&utm_medium=readme&utm_campaign=vercel-examples):

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/shengxinjing/email-helper&env=OPENAI_API_KEY&project-name=email-helper&repo-name=EmailHelper)

<!-- https://www.seotraininglondon.org/gpt3-business-email-generator/ -->
