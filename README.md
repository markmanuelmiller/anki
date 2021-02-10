# Anki Decks for Software Engineering

## Getting Started

1. Download Anki [here](https://apps.ankiweb.net/) - it's free!
2. Install the "CrowdAnki" add-on [here](https://ankiweb.net/shared/info/1788670778). For information on installing add-ons, checkout [this](https://englishfirstaid.net/2016/07/31/installing-anki-add-ons/#:~:text=In%20the%20main%20Anki%20window,the%20box%20and%20click%20OK.) guide.

3. Restart Anki - **this step is important** - you must restart Anki for the add-ons to take effect.

4. Clone this repository to your local machine.

5. Using Anki, click "File" > "CrowdAnki: Import from disk" option and select a folder in this repo. **Important**: each folder in this repo represents a deck in Anki, so you'll need to perform this action for each deck you wish to import.

## Methodology

When to create a new deck?

For Anki and its algorithm to work the best, we want to limit the number of decks we create. But at the same time, we don't want to put specific technologies like Kafka or JavaScript, into a general software engineering deck, so we've created standalone decks for those.

When contributing, please try to place general software engineering questions in the "Software Engineering" deck. If you have tech specific cards, feel free to create a new deck!

### Examples

- **Security/authentication** cards would go in the **Software Engineering** deck
- **Promises in JavaScript** cards would go in the **JavaScript** deck
- **CAP Theorum** cards would go in the **Software Engineering** deck
- **React's virtual DOM** cards would go in a new **React** deck.

## Contributing

If you're interested in contributing (and you should! the power is in community contribution) there are a few things to keep in mind.

1. Try to minimize the context required for a certain card. Make sure the card's question/front/text makes sense to someone seeing it for the first time.
1. Refrain from copy/pasting large chunks of text into one card. Follow the KISS principle with cards.

### Process

1. Within the cloned repo, create a new branch (example branch names: "new-deck-react" or "updating-deck-javascript").
1. Using Anki, click the gear icon next to the deck you wish to update and click the "Export" button.
1. Select "CrowdAnki JSON representation" as the export format.
1. Click export and select the location of the repo.
1. Create a pull request with the updated files.
