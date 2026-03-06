# Contributing to Minecraft Legacy Project Index

Thanks for helping keep the project list up to date!

## Adding a project via Pull Request

1. **Fork** this repository.
2. Open `projects.json` in any text editor.
3. Add your entry to the `repos` array:

```json
{
  "name": "YourName / YourProject",
  "url": "https://github.com/YourName/YourProject",
  "priority": 5
}
```

4. **Priority** - use the next number after the last entry. Maintainers may adjust it.
5. Make sure your JSON is valid - no trailing commas, all strings in double quotes.
6. Commit with a message like: `Add YourProject to project list`
7. Open a Pull Request and fill out the template.

## Requesting a project (no code needed)

Go to **Issues → New Issue → Project Request** and fill in the form. A maintainer will handle the rest.

## Guidelines

- One project per PR.
- Project must be related to Minecraft Legacy / Console Edition.
- No duplicate URLs.
- Keep `projects.json` clean and formatted.

## JSON validation

Before submitting, paste your edited `projects.json` into [jsonlint.com](https://jsonlint.com) to check for errors.

## Questions?

Open an issue or reach out to the maintainers.
