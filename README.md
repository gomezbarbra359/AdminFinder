# AdminFinder

AdminFinder is a simple tool designed to locate admin login pages on websites. By utilizing a wordlist, this tool attempts to find various paths where the admin login page might be located.

## Features

- Easy and fast to use  
- Supports both default and custom wordlists  
- Displays results with color‑coded status codes  
- Neon effect display for tool information

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Amirprx3/AdminFinder.git
   cd AdminFinder
   ```

2. Install dependencies:

   Ensure you have Python installed. Then run:

   ```bash
   pip install -r requirements.txt
   ```

## Usage

AdminFinder can be used with both default and custom wordlists.

### Using Default Wordlist

```bash
./adminfinder -u <target_url> -d
```

### Using Custom Wordlist

```bash
./adminfinder -u <target_url> -w <path_to_wordlist>
```

### Example

```bash
./adminfinder -u http://example.com -d
./adminfinder -u http://example.com -w custom_wordlist.txt
```

---

## Options

- `-h`, `--help`: Show help  
- `-u`, `--url`: Target URL (required)  
- `-d`, `--default`: Use default wordlist  
- `-w`, `--wordlist`: Path to custom wordlist

---

## Output

The output displays the status of each attempted path with color‑coded status codes:

- **Green [200]:** Found a page  
- **Red [404]:** Could not find the page  
- **Yellow [500]:** Server error

---

## Example Output

*(Example output would normally appear here)*

## Author

[Amirprx3](https://github.com/Amirprx3)

## License

MIT license
