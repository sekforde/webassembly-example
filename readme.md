# Global Requirements

```
npm i -g ts-node
npm i -g typescript
```

To compile the fib wasm file

```
asc fib/fib.ts -o fib.wasm
```

To test the wasm module inside typescript

```
ts-node run.ts
```