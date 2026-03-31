# NewLine Joiner

A simple, client-side tool to convert multiline text into a single line with custom separator and quotes. Inspired by [Comma Quote](http://commaquote.azurewebsites.net/).

## Features

- **Line Joining**: Convert multiline text into a single line instantly
- **Custom Separator**: Choose any separator character (default: comma)
- **Quote Options**: Wrap each line with single quotes, double quotes, or no quotes
- **100% Client-side**: All processing happens in your browser — no data is sent to any server
- **Dark/Light Theme**: Toggle between dark and light modes with system preference detection
- **Local Storage**: Your input, separator, and quote preferences are automatically saved
- **Copy to Clipboard**: One-click copy functionality for easy use
- **Responsive Design**: Works seamlessly on desktop and mobile devices

## How to Use

1. Enter or paste your multiline text in the **Input** field
2. Set your desired **Separator** (e.g., `,`, `;`, `|`, etc.)
3. Choose a **Quote** option:
   - No quotes
   - Single quotes (`'`)
   - Double quotes (`"`)
4. The **Output** field will automatically update with the joined text
5. Click **Copy** to copy the result to your clipboard

## Example

**Input:**
```
Line 1
Line 2
Line 3
```

**Separator:** `,`

**Quotes:** `"`

**Output:**
```
"Line 1","Line 2","Line 3"
```

## Built With

- [Spectre CSS](https://picturepan2.github.io/spectre/) — Lightweight CSS framework

## Icons Used

- [Merge Icon](https://www.iconfinder.com/icons/1055025/merge_arrow_on_ramp_icon)

## License

MIT License

## Contributing

Contributions are welcome! Feel free to submit a Pull Request.

## Demo

[https://herusdianto.github.io/newline-joiner/](https://herusdianto.github.io/newline-joiner/)