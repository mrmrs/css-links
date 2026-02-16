# css-links

Functional CSS for links

## Filesize

| File | Size |
|------|------|
| `dist/links.css` | 281 bytes |
| `dist/links.min.css` | 213 bytes (103 Gzipped) |

## Install

```sh
npm install css-links
```

## Usage

### Import

```css
@import "css-links";
```

### CDN

```html
<link rel="stylesheet" href="https://unpkg.com/css-links/dist/links.min.css">
```

### Direct

```html
<link rel="stylesheet" href="path/to/css-links/dist/links.min.css">
```

## Classes

| Class   | Value                    |
|---------|--------------------------|
| `.link` | `text-decoration: none;` |
| `.link-s` | `text-decoration: none;` |
| `.link-m` | `text-decoration: none;` |
| `.link-l` | `text-decoration: none;` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.link-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/links.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/links.css` — formatted
- `dist/links.min.css` — minified

## License

MIT
