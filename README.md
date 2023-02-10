# 生成手順

## 1. submodule を clone する。

```
git submodule update --init --recursive
```

## 2. 依存関係のinstall

```
npm run gen
```

## 3. コンパイル

```
npm run tsc
```