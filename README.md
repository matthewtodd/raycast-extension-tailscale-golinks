# Golinks

This is a [Raycast extension](https://developers.raycast.com/) for
fuzzy-searching over the links in a private [Tailscale golink
server](https://github.com/tailscale/golink).

I use it all the time at work: it's great for discovering what we've got and
for not having to remember specific spellings or punctuation.

## Install

If you don't use [Raycast](https://www.raycast.com/), you can install it at
that download link or `brew install raycast.`

Then:

```
git clone https://github.com/matthewtodd/raycast-extension-tailscale-golinks.git && cd raycast-extension-tailscale-golinks
which npm || brew install node
npm install && npm run dev
```

Type "go" in the Raycast window and follow your nose.

At this point, the extension is installed and you can ctrl-c to kill the watcher process in the terminal.
