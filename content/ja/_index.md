---
title: Bocchi
type: docs
---

# Bocchi

BocchiはAndroid端末をOpenPGP Cardとして動作させるアプリケーションです。


## できること

Bocchiは、OpenPGP Card対応ソフトウェアと組み合わせることで、次のことができます。

 - 電子署名（Signature）
 - データの復号化（Decryption）
 - 認証（Authentication）
 - 端末のセキュリティハードウェア内での鍵の生成とデバイス認証による利用
 - アプリでの鍵の生成とデバイス認証による利用

{{< hint info >}}
**OpenPGP Cardとは**  

OpenPGP Cardは、スマートカードなどのハードウェア内で生成した暗号鍵の機能を、外部のソフトウェアに提供できる[規格](https://www.gnupg.org/ftp/specs/OpenPGP-smart-card-application-3.4.1.pdf)です。

一般的に、ハードウェア内で生成した鍵は取り出すことができない仕組みになっていて、不正アクセス時の鍵の漏洩リスクを低減できます。
{{< /hint >}}


## 必要なもの

Bocchiの利用には、次のものが必要です。

 - PC
 - NFCカードリーダー（USBでPCと接続）
 - [GnuPG](https://www.gnupg.org/)などOpenPGP Card対応ソフトウェア


## ダウンロード

Google Playでダウンロードできます。

https://play.google.com/store/apps/details?id=dev.keiji.bocchi.app

オープンベータ版では開発中のバージョンを試すことができます。

https://play.google.com/apps/testing/dev.keiji.bocchi.app

{{< figure src="images/4175a15414d2d3120581ec478777db263e06dc1fc397e211a61bc65747a41c59.png" >}}

対応OS: Android 11.0（API Level 30）以上

## アプリ・ドキュメントのフィードバック

 - bocchi_feedback [at] keiji.dev
 - [https://github.com/keiji/bocchi-docs](https://github.com/keiji/bocchi-docs)