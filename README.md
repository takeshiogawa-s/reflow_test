# Reflowテスト
基板のリフローに関する知見をまとめるものです。


# オーブンの選定
まずはオーブンの選定方法についてです。

以前はホットプレートでのリフローが主流でしたが、基板上面の温度が上がりにくい、加熱のしすぎで基板が変色する等の問題があり、現在では両面加熱可能なトースターやオーブンでの簡易リフローが主流になりました。

おすすめはコンベクション機能がついている下記の二つになります。<br>


|型番|メーカー|出力|値段|
|---|----|----|---|
|TSF601K-C|TESCOM|1200W|13000円|
|ST-2D451|siroca|1400W|19800円|

私はTESCOM製のものを使用しています。

# ペーストはんだ
リフローには、ペーストはんだが必要になります。
現状購入可能なものだとchipquickのものが有名です。

https://www.chipquik.com/store/

ThermalStableシリーズというものが冷蔵保存なしで12か月持つので個人利用ならこのタイプを購入するのが良いです<br>

組成は、一般的な鉛フリーのTS391SNL250が一般的です。
オーブンの温度が230度ぐらい必要なので低温タイプでもよいと思います。<br>

|型番|メーカー|組成|温度|粒径|
|---|----|----|---|---|
|TS391SNL250|chipquick|Sn96.5/Ag3.0/Cu0.5|217-220℃|20-38um|
|TS391LT250|chipquick|Sn42/Bi57.6/Ag0.4|138℃|20-38um|

低温タイプは、便利な反面ビスマスを含むので取り扱いには注意が必要です。デバッグ時に通常のはんだごてで手直しを行うともろくなりクラックするので140度ぐらいまで温度が下がる小手を用意することをお勧めします。

# 