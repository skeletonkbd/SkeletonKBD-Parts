# SkeletonKBD-Parts

自社製のKicad用のシンボルとフットプリントを置いています。実際に発注しての動作確認ができていないものを含んでいるので、ご利用は自己判断でお願いします。

## SK6812MINI-E_nusumi.kicad_mod
 
![SK6812MINI-E_nusumi.kicad_mod](https://user-images.githubusercontent.com/90203406/226605136-7b3a7155-ef40-458e-8a13-e0ac68462d71.jpg)

実装時にスロットにきちんとハマらないトラブルを避けるように対策を施したSK6812MINI-Eのリバースマウント用フットプリントです。手半田はもちろん、PCBAで使えることを目標に作成しています。

LED本体の寸法より15%大きいサイズのスロットにしています。さらにバリ対策として四隅にヌスミ（ドリル穴）を配置しています。

## WS2812B-4020.kicad_mod

横向きのLEDです。

## SK6812D-EC3210R_reverse.kicad_mod

![SK6812D-EC3210R](https://user-images.githubusercontent.com/90203406/226646191-80da7a33-2f6b-4d36-8ae2-af38f707dead.jpg)

3方向に実装できるイカした設計のLED。リバースマウント用のフットプリントを作ってPCBAを発注してみたけど「横向きにしか対応してません」と断られた悲しみ。

## WS2812C-2020_reverse.kicad_mod

ちっちゃいLED。リバースマウントできないこともないような気がしたのでフットプリントを作って（以下略

## LTW-C230DS.kicad_mod

単色のLED。フットプリントは`Device:LED_Small`
