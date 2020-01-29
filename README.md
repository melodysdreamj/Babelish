
[공식문서](https://melodysdreamj.synology.me:31935/oo/r/505881752508611605)

이문서는 이 [깃허브](https://github.com/melodysdreamj/Babelish)를 바탕으로 마련되었습니다.
사용법은 [이곳](https://github.com/netbe/Babelish/wiki/How-to-Use)에서 [이것](https://github.com/netbe/Babelish/blob/master/test/data/test_data_multiple_langs.csv)을 바탕으로 마련하였습니다. 저기 예시파일에서 another string부분이 채워져있어야합니다.

명령어는 다음과같습니다.

안드로이드 얻는법 - 타켓파일 - [test_data_multiple_langs.csv](https://melodysdreamj.synology.me:31935/oo/r/532761700382847915#tid=1)

babelish csv2android --filename=target_csv.csv --langs ko:ko en:en ja:ja es:es pt:pt fr:fr ar-XA:ar-XA de:de --output_dir=android_lang

ios 얻는법

babelish csv2strings --filename=target_csv.csv --langs ko:ko en:en ja:ja es:es pt:pt fr:fr ar-XA:ar-XA de:de --output_dir=ios_lang
