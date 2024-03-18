
## multi-repo

### demo-a
```shell
cd demo-a
npm install
npm run dev
```

### demo-b
```shell
cd demo-b
npm install
npm run dev
```

## mono-repo
```shell
npm install
npm run dev -w demo-a
npm run dev -w demo-b
```