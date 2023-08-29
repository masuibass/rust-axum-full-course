## Start Dev Server
```
cargo watch -q -c -w src/ -x run
```

## Start Test
```
cargo watch -q -c -w tests/ -x "test -q quick_dev -- --nocapture"
```