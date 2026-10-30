# Heokjin Developer Support

Public developer support hub for Japan Story and future apps.

- Support email: [heokjin@gmail.com](mailto:heokjin@gmail.com)
- Hub: https://heokjin.github.io/developer-support/
- Japan Story support: https://heokjin.github.io/developer-support/japan-story/
- Japan Story privacy policy: https://heokjin.github.io/policy/japan-story/

## Directory structure

Each app has its own directory containing an `index.html` file:

```text
/
├── index.html                 # App support hub
└── japan-story/
    └── index.html             # Japan Story support page
```

To add another app, create a new directory such as `my-app/` and place its support page at `my-app/index.html`. The app-specific Google Play website URL is then:

```text
https://heokjin.github.io/developer-support/my-app/
```

The site is a static HTML page and is deployed from the `main` branch root.
