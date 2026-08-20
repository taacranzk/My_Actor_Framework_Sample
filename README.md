# My_Actor_Framework_Sample

こちらの記事で作成したLabVIEW Actor Frameworkのサンプルです。

https://stacksequencenotpass.net/actor-framework/

作成したLabVIEWバージョン：LabVIEW 2026 Q3

実行に必要な設定
* DAQ実機かシミュレーションデバイスの設定
* 使用するDAQに合わせてDAQ Channel Setting.csvを編集する。

実行方法
* Actor Framework Sample.lvprojを開き、Launcher.viを開く
* Launcher.viを実行する。

アプリケーションの構造
- Launcher
    - Supervisor Actor
    - UI Actor
    - DAQ AI Actor
    - DAQ DI Actor
