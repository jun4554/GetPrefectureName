# GetPrefectureName
都道府県名を取得するAPI

パラメータに1から47の任意の数字を入れると、それに対応した都道府県名を取得するAPIです。
取得形式はJsonです。

【使い方】
1.任意のサーバーにgetPrefectureName.phpとreturnJson.phpを配置します。（２つのファイルは同じ階層に置いてください）
2.~/getPrefectureName.php?prefecture_no=13といった形でアクセスする。この例では"東京都"が取得されます。

都道府県番号は経済産業省が規定しているものに準拠します。
https://www.meti.go.jp/policy/chemical_management/kasinhou/files/ippantou/table_prefecturecode.pdf
