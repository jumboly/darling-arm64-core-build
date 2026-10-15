# darling-arm64-core-build

Builds the `core` component of [VibeDarling](https://github.com/VibeDarling/darling) on an arm64
Linux runner (Debian 13 container) and publishes the `DESTDIR` install tree as an artifact.

Used by the "MacでHello Worldする" demo, which runs the resulting Darling on top of
[NABI](https://github.com/mslxnu/native_abi) on Apple Silicon macOS.
