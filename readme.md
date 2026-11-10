# README

TRPGセッション際のココフォリアをOBSで録画するにあたり、見た目をCSSでカスタムします。

- [chat/ccfolayer-chat-001.css](chat/ccfolayer-chat-001.css): チャット欄（ルームの URL に使う）
- [status/ccfolayer-status-001.css](status/ccfolayer-status-001.css): キャラクターのステータス（キャラクターの表示用 URL に使う）

どちらも外から別の CSS を読み込まない1ファイルです。ココフォリアの更新で壊れにくいよう、
ココフォリアが自動で付けるクラス名（`css-xxxx` など）や「何番目の箱か」には頼らず、
MUI の部品名と要素どうしの位置関係で狙っています。

## 参考にさせていただきました
- [OBSでココフォリアを表示させる時のカスタムCSSについて | U7D05 BAR](https://ydk.vc/obs-ccfolia-css/)
- [you-custom-css｜Made by 葉桜ヨウ](https://scrapbox.io/you-custom-css/)
- [ghgantz/customCss](https://github.com/ghgantz/customCss): chat の元にしていた CSS（2026-11 に自前で書き直し）
- [yudukiak/ccfoliaCSS](https://github.com/yudukiak/ccfoliaCSS): status で読み込んでいた CSS（2026-11 に自前で書き直し）

## Docs

- [OBSでココフォリアを録画するときのカスタムCSS](https://note.com/kaige_h/m/me2ed31ea492f)
