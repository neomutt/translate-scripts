# Translation Helper Scripts

<a href="https://github.com/neomutt/neomutt/actions/workflows/translate.yml"><img align="right" src="https://github.com/neomutt/neomutt/actions/workflows/translate.yml/badge.svg?branch=translate&event=push"></a>

These scripts automate the process of updating the [Translation Leaderboard](https://neomutt.org/translate).

They take the `.po` files in the [NeoMutt repo](https://github.com/neomutt/neomutt),
check them for any syntax errors, generate a webpage, then upload the webpage to
the [website repo](https://github.com/neomutt/neomutt.github.io).

## Scripts

| Script                                     | Description                                        |
| :----------------------------------------- | :------------------------------------------------- |
| [deploy.sh](deploy.sh)                     | Deploy the updated webpage                         |
| [generate-webpage.sh](generate-webpage.sh) | Generate the Leaderboard webpage                   |
| [stats.sh](stats.sh)                       | Validate translations and print some stats         |

## Screenshot

The result looks a bit like this:

![leaderboard](leaderboard.png)
