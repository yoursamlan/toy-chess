Build and Run

```
python script.py init --clang # Add "--b Debug" for debug build
python script.py run
```

Test

```
python script.py run --e main_test -- -s
```

Benchmark

```
python script.py run --e main_bench -- -s
```

For training neural network, see `src/nn/README.md`.

For deploying lichess bot, see `misc/bot/README.md`.
