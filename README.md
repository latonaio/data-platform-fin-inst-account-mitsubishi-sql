# data-platform-fin-inst-account-mitsubishi-sql 

data-platform-fin-inst-account-mitsubishi-sql は、データ連携基盤において、三菱UFJ銀行の口座データを維持管理するSQLテーブルを作成するためのレポジトリです。  

## 前提条件  
data-platform-fin-inst-account-mitsubishi-sql は、データ連携にあたり、API を利用し、本レポジトリ の sql 設定ファイルの内容は、下記 URL の API 仕様を前提としています。  
https://api.XXXXXXXX.com/api/OP_API_XXXXXXX_XXX/overview   

## sqlの設定ファイル

data-platform-fin-inst-account-mitsubishi-sql には、sqlの設定ファイルとして、以下のファイルが含まれています。

* data-platform-fin-inst-account-mitsubishi-sql-account-info-data.sql（データ連携基盤 口座 三菱UFJ銀行 - 口座情報データ）

## MySQLのセットアップ / Kubernetesの設定 / SQLテーブルの作成方法
MySQLのセットアップ / Kubernetesの設定 / 具体的なSQLテーブルの作成方法、については、[mysql-kube](https://github.com/latonaio/mysql-kube)を参照ください。  
