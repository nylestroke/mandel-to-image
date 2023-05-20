## Run needs 4 console args:
- final image name with extension, e.g (mandel.png)
- image size in pixels separated with 'x' char, e.g (4000x3000)
- set of complex numbers for upper left corner separated with comma ',', e.g (-1.20,0.35)
- set of complex numbers for lower right corner separated with comma ',', e.g(-1,0.20)

## Example usage:

```rust
cargo run -- mandel.png 4000x3000 -1.20,0.35 -1,0.20
```

and result:
![mandel.png](mandel.png)
