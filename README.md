# Shopify Vue Storefront

Shopify 2.0 Vue Performance Testing
Comparisons between Liquid 2.0 and VueStorefront

[Documentation via AureateLabs](https://docs.vuestorefront.io/v2/) // Repo WIP as of Feb 11 2022

# Table of Contents

1. [Installation](#installation)
1. [Performance](#performance)
1. [Limitations](#limitations)

# Installation

Repository

```
nvm use 16
npx @vue-storefront/cli init
cd <your_project_name>
yarn install
yarn dev
```

Don't have yarn yet? (npm users I see u)

```
npm install --global yarn
yarn --version
```

Yarn giving you problems? (It gave me problems on Windows)
[Terminal > New Terminal > Select Default Shell Option > Command Prompt](https://stackoverflow.com/questions/56199111/visual-studio-code-cmd-error-cannot-be-loaded-because-running-scripts-is-disabl/67420296#67420296)

VSCode Extensions

```
Vetur
```

# Performance

```
547 MB Memory Usage
1.08 GB RSS
```

# Limitations

1. Changing the color scheme

[2020 Source](https://forum.vuestorefront.io/t/css-guide-attempting-to-change-color-scheme/1146/2)

1. Where is the VUE APP stored?

Since it's not a theme, there has to be allocation for
