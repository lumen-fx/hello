# hello

The smallest runnable Lumen app.

Concepts demonstrated:

- **`src/main.lmn`** - every app is one `<root>` element; a `<label>` fills
  it. An app keeps its code in `src/` and its `lumen.toml` at the root.
- **`<script src="main.cdl" />`** - attaches a candela script; `on_start()`
  runs once when the app loads. `import "lumen.cdl";` pulls in the whole
  Lumen surface, and `main()` stays empty because a Lumen app works through
  its lifecycle handlers.
- **`lumen.toml`** - window title + logical size.

Run it:

```sh
lumenc run .
```
