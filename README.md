# ClickTag Implementation

This just give a quick implementation, but can be extend to support all provider like districtm and DV360

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Things to look for](#things)

## Installation

If you want run the live test you will need to have node install or just read the code and comments

On windows, mac and linux
Official nodejs website 
[www.nodejs.com](https://nodejs.org/en/download/)

You can also on mac use brew
 
```bash
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
brew install node
node -v
```

## Usage

Once the package install run the following command
```bash
npm i
npm run start

```

This will start a node server you can go on http://localhost:3000 or the port reported in the terminal.
click on the banner it should redirect you on a google search for districtm.net website.

Again this is just a overview not a full implementation.

## Things

First if you look at the `index` file you will see that we applied a parameters to the banner url.
This again can be spec by you, for example, DV360 will modify the clickTag for clicktag and vice-versa.
I invite you to use another label or key like `ex: sofiaClick= redirect URL`.

You should also have a fallback if the provider does not have a redirect so you only use the url declare in your platform.





