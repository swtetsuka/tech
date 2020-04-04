# EBS ボリュームサイズの変更

## 例
インスタンスの非ルートデバイスの EBS ボリュームサイズを 1GiB から 10GiB に拡張します。

## 手順
1. 「EC2 ダッシュボード > インスタンス > インスタンス」を開きます
2. インスタンス一覧から対象インスタンスを選択します
3. 「説明」タブ中の「ブロックデバイス」のうち、非ルートデバイスを開きます
4. EBS ID を開きます
5. 対象ボリュームを選択します
6. 「アクション」をクリックします
7. 「ボリュームの変更」を開きます
8. 現在の「サイズ」が正しいことを確認します
10. 「サイズ」を変更します
11. 「変更」をクリックします
12. 「はい」をクリックします
13. 「閉じる」をクリックします
14. 「サイズ」が変更されていない場合は更新ボタンをクリックします
15. 「サイズ」が正しく変更されたことを確認します

## スクリーンショット

1.
![elb-modify-volume](img/screenshot-2020-04-04-18.19.00-1.png)
2.
![elb-modify-volume](img/screenshot-2020-04-04-18.19.20-1.png)
3.
![elb-modify-volume](img/screenshot-2020-04-04-18.19.52-1.png)
4.
![elb-modify-volume](img/screenshot-2020-04-04-18.19.56-1.png)
5.
![elb-modify-volume](img/screenshot-2020-04-04-18.20.03-1.png)
6.
![elb-modify-volume](img/screenshot-2020-04-04-18.20.03-2.png)
7.
![elb-modify-volume](img/screenshot-2020-04-04-18.20.14-1.png)
8.
![elb-modify-volume](img/screenshot-2020-04-04-18.20.22-1.png)
9.
![elb-modify-volume](img/screenshot-2020-04-04-18.20.27-1.png)
10.
![elb-modify-volume](img/screenshot-2020-04-04-18.20.27-2.png)
11.
![elb-modify-volume](img/screenshot-2020-04-04-18.20.30-1.png)
12.
![elb-modify-volume](img/screenshot-2020-04-04-18.20.34-1.png)
13.
![elb-modify-volume](img/screenshot-2020-04-04-18.20.38-1.png)
14.
![elb-modify-volume](img/screenshot_2020-04-04_19.45.41-1.png)

## 参考
https://docs.aws.amazon.com/ja_jp/AWSEC2/latest/UserGuide/ebs-modify-volume.html
