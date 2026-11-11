# Password Tools

A lightweight Streamlit application for exploring password strength and generating password candidates. It brings a password strength checker and three generation modes together in a simple interface.

> **Try it online:** [passwordtool.streamlit.app](https://passwordtool.streamlit.app/)

## Features

- **Password strength checker** — evaluates a password against eight checks, including length, character variety, username reuse, and a small list of common passwords. It also provides suggestions for failed checks.
- **Random password generator** — create passwords from letters, with optional numbers and symbols.
- **Memorable password generator** — combine words with a chosen separator and optional capitalization.
- **PIN generator** — generate a numeric code of a configurable length.
- **Streamlit interface** — use the tools in your browser, either through the hosted app or a local installation.

## Screenshots

| Password generator | Strength checker |
| --- | --- |
| ![Password generator](src/images/generator.png) | ![Password strength checker](src/images/score.png) |

## Run locally

### Requirements

- Python 3.10 or later
- `pip`

### Setup

Clone the repository and install its dependencies:

```bash
git clone https://github.com/mohammadhossein-hamed/password_tools.git
cd password_tools
python -m pip install -r requirements.txt
```

Start the app from the `src` directory:

```bash
cd src
streamlit run "🏠️_Home.py"
```

Streamlit will print a local URL in the terminal. Open it in your browser to use the app.

## Use responsibly

The strength checker provides a basic, rule-based estimate; it is not a security audit and does not guarantee that a password is safe. Avoid entering passwords you use for real accounts. For important accounts, use a trusted password manager and a unique password for each service.

## Contributing

Contributions and suggestions are welcome. Open an issue to report a problem or propose an improvement, or submit a pull request.

## License

This project is distributed under the MIT License. See [LICENSE](LICENSE) for details.
