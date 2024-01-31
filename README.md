<div id="top"></div>

<!-- ## 使用技術 -->
<!-- シールド一覧 -->
<!-- https://t8csp.csb.app/ -->
<p style="display: inline">
  <img src="https://img.shields.io/badge/-Power%20Automate%20Desktop-5391FE.svg?logo=Power%20Automate&style=popout"
</p>


# Power Automate Desktopを使ってGoogle連絡帳へインポートする


# 概要

会社の電話帳を追加していく処理をPower Automate Desktop（以降はPADと表記）で
自動化するサンプルです

# 前提

インポートするCSVは作成済みであること。

PAD内のGoogleアカウント、CSVファイルのパスを変更すること。

# 導入方法

source.zipを解凍して全文をコピーする。

新規のフローを作成し、コピーしたソースをフローに貼り付ける（Ctrl＋V）。

# 使い方

自動起動するには、有償版で利用するか、PowerShell で起動させてタスクスケジューラ登録すること。


# 注意点

インポートできる正しいCSVで実行してください。インポート時のエラー処理は未対応です。

# ライセンス
 [MIT license](https://en.wikipedia.org/wiki/MIT_License).
