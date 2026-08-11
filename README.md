# Demo Brain

A live collaborative HTML page. One repo, many terminals.

Live site: https://sahilmodi1965.github.io/demo-brain/

## Your job

Find the block in `index.html` with your GitHub username in the START/END comment markers.
Edit **only** what is between those two markers. That block is yours — text, styles,
images, whatever you want. Everything outside your markers belongs to someone else.

## How to contribute (from your terminal)

Clone the repo:

    git clone https://github.com/sahilmodi1965/demo-brain.git
    cd demo-brain

Make a branch named after yourself:

    git checkout -b yourusername

Open `index.html`, find your block, edit it. Then:

    git add index.html
    git commit -m "yourusername: claimed my card"
    git push -u origin yourusername

Then open a Pull Request on GitHub. Sahil merges, the site updates.

## Rules

1. Edit only inside your own START/END markers.
2. One branch per person, named after your username.
3. Small commits, clear messages.
4. If you break the page, that's fine — we fix it live.

## Stuck?

`git status` tells you where you are. Ask in the session.
