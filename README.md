# FME Lab website

Bilingual website for the Functional Macroecology Lab / 功能宏生态学实验室.

## Structure

- `en/`: English pages
- `zh/`: Chinese pages
- `_layouts/default.html`: shared layout and navigation
- `_includes/lang-switch.html`: language switcher
- `assets/css/style.css`: site styling

Each English and Chinese page pair uses the same `ref` value in its front matter. This allows the language switcher to locate the corresponding translation automatically.

