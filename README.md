# plain.nvim

A minimal Neovim colorscheme that intentionally removes syntax highlighting.

`plain.nvim` is based on the idea that code should be read as text, not colors.  

## Philosophy

- Minimal visual distraction

## Features

- Fully monochrome design
- Optional `dim_comments` mode
- Selectable `fg` color variant (`default`, `nerdy`, `sunny`)

## Installation (Lazy.nvim)

```lua
{
  "pngnwthbrd/plain.nvim",
  priority = 1000,
  config = function()
    require("plain").setup({
      dim_comments = false,
      fg = "default", -- "default" | "nerdy" | "sunny"
    })

    vim.cmd.colorscheme("plain")
  end,
}
```
## Variants (with dimmed comments)
### default
<img width="681" height="816" alt="image" src="https://github.com/user-attachments/assets/4b1e9d51-0a97-4899-849a-412280b1d49e" />

### nerdy
<img width="791" height="818" alt="image" src="https://github.com/user-attachments/assets/d54865c4-615b-4698-ba01-3f0a8b180abb" />

### sunny
<img width="753" height="859" alt="image" src="https://github.com/user-attachments/assets/3b9ec2ad-4550-45ec-aebe-04f443728c98" />
