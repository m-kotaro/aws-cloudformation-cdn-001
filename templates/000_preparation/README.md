# templates/000_preparation

## 概要

CloudFormationを実行する前の事前準備

## 構築するもの

下記リソースを構築してからアーキテクチャを構築する。

 - Route53にてドメインを取得
 - ドメインに対してパブリックACM（証明書）を取得する
 - パブリックACMをRoute53に登録して承認する
