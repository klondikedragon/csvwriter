# csvwriter fork

Base: d-markey/csvwriter `03a32ab` (published as [csvwriter 1.3.0](https://pub.dev/packages/csvwriter/versions/1.3.0); the pub archive differs only in CRLF line endings).
Patch: select the unchanged browser sink with `dart.library.js_interop`, so the package compiles under dart2wasm.
Revisit when upstream supports Wasm.
