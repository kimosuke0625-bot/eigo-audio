# eigo-audio

「英語マスター 2年計画」（https://kimosuke0625-bot.github.io/eigo-app/）で使う英語の音声ファイル置き場です。
アプリの更新のたびに大きな音声を送り直さないよう、音声だけをこのリポジトリに分けています。

## 中身
- `heads/`：NGSL の見出し語（単語1つ）の音声（mp3・モノラル48kbps）
- `ex/`：復習カードの例文の音声（mp3・モノラル32kbps）
- `facts/`：雑学（やさしい版・標準版）の音声（32kbps）
- `quotes/`：名言の英語の原文の音声（32kbps）
- `index.json`：作成済みの音声の一覧（アプリが読む）

## 作り方とライセンス
- 音声合成：Kokoro-82M（Apache-2.0、https://huggingface.co/hexgrad/Kokoro-82M）。6種類の声（アメリカ英語・イギリス英語、男性・女性）を文ごとに使い分けています。
- 読み上げた英文の出典：NGSL 1.2（CC BY-SA 4.0）、Tatoeba（CC BY 2.0 FR）、このアプリで作成した例文・雑学（CC BY-SA 4.0）、名言（短い引用）。
- 音声ファイルは、元の英文のライセンスにならい CC BY-SA 4.0 で公開します（Tatoeba の文の音声は CC BY 2.0 FR の表示に従います）。
