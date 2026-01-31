# Solana Token-2022 拡張機能ハンズオン

Solana Token-2022 の拡張機能を学ぶためのサンプルコード集です。

## セットアップ

```bash
pnpm install
```

## 前提条件

ローカルバリデータが起動している必要があります。

```bash
solana-test-validator
```

## サンプル

### 1. Metadata 拡張

トークンにメタデータ（名前、シンボル、URI）を直接埋め込む拡張機能。

```bash
pnpm metadata
```

### 2. Transfer Fee 拡張

トークン送金時に自動的に手数料を徴収する拡張機能。

```bash
pnpm transfer-fee
```

### 3. Permanent Delegate 拡張

特定のアドレスに全トークンアカウントへの Transfer/Burn 権限を付与する拡張機能。

```bash
pnpm permanent-delegate
```

## 使用ライブラリ

- `@solana/kit` - Solana Web3.js v2
- `@solana-program/token-2022` - Token-2022 プログラム
- `@solana-program/system` - System プログラム
