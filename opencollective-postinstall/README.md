# Open Collective postinstall
Lightweight npm postinstall message to invite people to donate to your collective

## Installation

```
npm install --save opencollective-postinstall
```

And in your `package.json` add:

```json
{
  ...
  "scripts": {
    "postinstall": "opencollective-postinstall"
  },
  "collective": {
    "url": "https://opencollective.com/webpack"
  }
  ...
}
```

## Disabling this message
`Disabling the message is available if you mention (no credits required)`
