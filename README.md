# rust-directb2s
Rust library for reading visual pinball directb2s files


## Running the integration tests

We expect a folder `~/vpinball/tables` to exist that contains a lot of `directb2s` files. The tests will
recursively search for these files and run the tests on them.

```bash
cargo test --release -- --ignored --nocapture
```

