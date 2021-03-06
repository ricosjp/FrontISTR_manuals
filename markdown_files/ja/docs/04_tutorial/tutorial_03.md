## 静解析（弾性）

本解析の実施には、tutorial/01\_elastic\_hinge のデータを用います。

### 解析対象

解析対象はヒンジ部品で、形状を図4.1.1に、メッシュデータを図4.1.2に示します。
メッシュには四面体2次要素を用い、メッシュ規模は要素数49,871、節点数84,056です。

<div style="text-align: center;">
<img src="../fig/image1.png" width="350px"><br>
図4.1.1　ヒンジ部品の形状
</div>

<div style="text-align: center;">
<img src="../fig/image2.png" width="350px"><br>
図4.1.2　ヒンジ部品のメッシュデータ
</div>

### 解析内容

図4.1.1に示す拘束面の変位を拘束し、強制面に集中荷重を負荷する応力解析を実施します。
解析制御データを以下に示します。

### 解析結果

ミーゼス応力のコンター図をREVOCAP\_PrePostで作成して図4.1.3に示します。
また、解析結果の数値データとして、解析結果ログファイルの一部を以下に示します。

<div style="text-align: center;">
<img src="../fig/image3.png" width="350px"><br>
図4.1.3　ミーゼス応力の解析結果
</div>
