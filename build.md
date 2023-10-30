



```
docker build --build-arg TARGET=mipsel-unknown-linux-musl --build-arg RUST_MUSL_MAKE_CONFIG=config.mak --build-arg TOOLCHAIN=1.73.0-x86_64-unknown-linux-gnu -t tmp:mipsel-musl .
```