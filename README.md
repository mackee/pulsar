# Pulsar - The functional keyboard for creators

## 部品の不足や不具合, その他のお問い合わせ

Twitterの私のアカウントまでDMをしてください [@mackee\_w](https://github.com/mackee_w)

## ビルドガイド

このビルドガイドはRev.2(11キー)版のビルドガイドです。Rev.1(9キー+OLED付き) のビルドガイドはこちら

https://gist.github.com/mackee/b5231e5609be889129ee4aa5c9ab0aaa


### 同梱しているもの

![img](https://github.com/mackee/pulsar/blob/master/docs/img/pulsar_package.jpg)

#### Pulsar本体基板

![img](https://github.com/mackee/pulsar/blob/master/docs/img/pulsar_main_board.jpg)

メイン基板と、LEDがついたボトムプレートが一体になっています。

#### トッププレート

![img](https://github.com/mackee/pulsar/blob/master/docs/img/pulsar_top_plate.jpg)

本体基板とは別に添付しています。

#### ネジ袋

![img](https://github.com/mackee/pulsar/blob/master/docs/img/screw_bag.jpg)

ネジが入った袋です。袋の中には以下の物が含まれています。

* M2 スペーサー 高さ7.5mm x 8本
* M2 ネジ x 16本

### 別途使用に必要なもの

#### キースイッチ x 11個

Cherry MX互換のキースイッチに対応しています。

[Kailh BOX](https://yushakobo.jp/shop/kailh-box/), [Kailh Speed](https://yushakobo.jp/shop/kailh-speed/), [Gateronスイッチ](https://yushakobo.jp/shop/a0200ga/)の適合を確認しています

#### キーキャップ x 11個

入手されたキースイッチに適合するキーキャップが必要です

#### ノブ/つまみ

親指ロータリーエンコーダ部分に使用するノブです。

軸φ6.1に対応しているつまみが使用できます。また、直径2.3cm以上のつまみはキーキャップと干渉します。

秋月電子で売られている[K-59](http://akizukidenshi.com/catalog/g/gP-12529/)や、千石電商で扱いがある[BR-20](https://www.sengoku.co.jp/mod/sgk_cart/detail.php?code=6A8D-DNEV)が使用できることを確認しています。

### 別途組み立てに必要な道具

* \+ 精密ドライバー
* ラジオペンチ

### 組み立て方

#### 1. 基板を分割する

Pulsar基板本体をメイン基板とボトムプレートに分割します。

![](https://github.com/mackee/pulsar/blob/master/docs/img/cut_board1.jpg)

4箇所あるので、できるだけ近い部分を持ちつつ折ってください。写真のようにラジオペンチを使うときれいに折れます。

![](https://github.com/mackee/pulsar/blob/master/docs/img/cut_board2.jpg)

#### 2. ボトムプレートにスペーサーを立てる

ネジ袋からスペーサーを8個全部と、黒いネジを8個取り出します。

ボトムプレートの何も部品がない面から、ネジを差し込み、反対側からスペーサーを取り付けます。

![](https://github.com/mackee/pulsar/blob/master/docs/img/bottom_plate_screw.jpg)

このとき、はじめは手で軽く締めていって、最後に精密ドライバーでネジを、ラジオペンチでスペーサーを持って固く締めます。

![](https://github.com/mackee/pulsar/blob/master/docs/img/bottom_plate_screw2.jpg)

8箇所ある穴すべてにスペーサーを立てます。

#### 3. メイン基板をボトムプレートに重ねる

メイン基板を、スペーサーを立てたボトムプレートの上に重ねます。

![](https://github.com/mackee/pulsar/blob/master/docs/img/layered_bottom_main.jpg)

メイン基板の取り付け穴はスペーサーの直径よりも大きいので、穴の中にスペーサーを通すようにします。

また、ロータリーエンコーダを右下にしたときに、ボトムプレートには 3本のピンヘッダーが、メイン基板にはピンヘッダを通すための穴があります。

![](https://github.com/mackee/pulsar/blob/master/docs/img/zigzag_pin_header.jpg)

電気的に接触するため、メイン基板側の真ん中の穴が少しずれています。重ねたときに、ボトムプレートのピンがメイン基板の穴に刺さるようにします。

![](https://github.com/mackee/pulsar/blob/master/docs/img/zigzag_pin_header_pushed.jpg)

止まるまでグググッと押し込みます。

#### 4. トッププレートを取り付ける

ボトムプレートに、メイン基板を重ねた物の上にさらに、トッププレートを重ねます。

スペーサーの位置とトッププレートの位置を合わせて、トッププレートを残りのネジで固定します。

![](https://github.com/mackee/pulsar/blob/master/docs/img/topplate1.jpg)

これで、Pulsarの本体は完成です。

#### 5. キースイッチを取り付ける

トッププレートの穴から、キースイッチを差し込んでいきます。

![](https://github.com/mackee/pulsar/blob/master/docs/img/keyswitch1.jpg)

このとき、メイン基板の黒い丸の部品と、キースイッチのピンの位置を合わせます。

![](https://github.com/mackee/pulsar/blob/master/docs/img/keyswitch2.jpg)

また、キースイッチのピンが曲がっているときは、差し込んだときに折れてしまうことがあるため、ラジオペンチなどでまっすぐにしておきます。

トッププレートと、キースイッチの縁が当たるまで、強く押し込みます。

![](https://github.com/mackee/pulsar/blob/master/docs/img/keyswitch3.jpg)

#### 6. キーキャップを取り付ける

キースイッチにキーキャップを取り付けます。

![](https://github.com/mackee/pulsar/blob/master/docs/img/keycap.jpg)

#### 7. つまみ/ノブを取り付ける

ロータリーエンコーダにつまみ/ノブを取り付けます。

![](https://github.com/mackee/pulsar/blob/master/docs/img/knob.jpg)

これで完成です！ お疲れさまでした。

## ファームウェアの書き込み方

## キーマップ変更

**NOTICE: 本家qmk_firmwareへPull Request予定です。マージされたあとに手順が変わります**

qmk configuratorは現在ロータリーエンコーダに対応していないため、ソースコードを変更してキーマップを変える手順を記述します。

事前に`qmk_firmware`を扱える環境を構築しておきます。

[はじめに - QMK Firmware](https://docs.qmk.fm/#/ja/newbs_getting_started)

参考: Windowsユーザ向け [プログラマーではない人向けのQMK Firmware入門](https://qiita.com/cactusman/items/ac41993d1682c6d8a12e)

### 1. `pulsar` ブランチを指定して `github.com/mackee/qmk_firmware`をcloneします。

```console
$ git clone -b pulsar github.com/mackee/qmk_firmware
```

すでに`qmk_firmware`のclone済みブランチがある場合は、

```console
$ git remote add mackee https://github.com/mackee/qmk_firmware
$ git fetch mackee pulsar
$ git checkout pulsar
```

と、リモートリポジトリを追加してcheckoutします。

### 2. ファームウェアを書き込む

動作確認のためにファームウェアを書き込みます。頒布時点で書き込まれているキーマップは`default`です。

`qmk_firmware`のディレクトリにCLIターミナル内で移動し、以下のコマンドを実行します。

```console
$ make pulsar/rev2:default:dfu-util
```

`Detecting USB port, reset your controller now...` と表示されたら、右下レバースイッチを押し込みながら、一番右上のキーを押します。すると、書き込みが開始されます。

`avrdude done.  Thank you.` と表示されたら成功です。

### 3. キー配置を変更する

`default`キーマップをもとにキー配置を変えてみます。

まず、`keyboard/pulsar/keymaps/rev2/default`ディレクトリをコピーして`keyboard/pulsar/rev2/keymaps/mykeymap`ディレクトリを作ります。

```console
$ cp -R keyboard/pulsar/rev2/keymaps/default keyboard/pulsar/rev2/keymaps/mykeymap
```

その後にお好きなテキストエディタで`keyboard/pulsar/rev2/keymaps/mykeymap/keymap.c`を編集します。

例えば`S`と入力されるように設定しているキーを`D`に変更するには以下のように`keymap.c`を変更します。

```diff
@@ -28,7 +28,7 @@ enum {

 const uint16_t PROGMEM keymaps[][MATRIX_ROWS][MATRIX_COLS] = {
   [_BASE] = LAYOUT( /* Base */
-    KC_LSHIFT, KC_A,    KC_S,     KC_Y,    KC_M,             \
+    KC_LSHIFT, KC_A,    KC_D,     KC_Y,    KC_M,             \
     KC_LCTRL,  KC_Z,    KC_X,     KC_C,    KC_V,             \
                                   KC_LALT,                   \
     JP_LBRC,   XXXXXXX, LT(_LED, KC_ENTER), XXXXXXX, JP_RBRC \
```

キーコードの参考ドキュメント: [キーコードまとめ](https://syon.github.io/refills/rid/1471100/)

キーマップの最下段はレバースイッチのキーマップです。レバースイッチには半押しも検知できる機能があるのですが、使いにくいため`default`キーマップでは使っていません。

`JP`がプレフィックスにあるキーコードは、日本語キーボード向けのキーコードです。Windowsですでに日本語キーボードが別にある環境で利用してください。

保存後にキーボードにキーマップを書き込むには、 2と同様の手順で、以下のコマンドを実行します。

```console
$ make pulsar/rev2:mykeymap:dfu-util
```

### 4. ロータリーエンコーダの挙動を変更する

ロータリーエンコーダは`keymap.c`内の`encoder_update_user`関数で挙動を定義しています。

```c
void encoder_update_user(uint8_t index, bool clockwise) {
  if (index == 0) {
    if (clockwise) {
      if (get_mods() & MOD_LCTL) {
        rgblight_step();
      } else if (get_mods() & MOD_LSFT) {
        tap_code(KC_END);
      } else {
        tap_code(KC_MS_WH_DOWN);
      }
    } else {
      if (get_mods() & MOD_LCTL) {
        rgblight_step_reverse();
      } else if (get_mods() & MOD_LSFT) {
        tap_code(KC_HOME);
      } else {
        tap_code(KC_MS_WH_UP);
      }
    }
  }
}
```

`KC_`から始まるキーコードを変更すれば、そのまま挙動を変えることが出来ます。

`clockwise`が`true`の場合は時計回り、`false`のときは反時計回りの場合です。また、`get_mods() & MOD_***`では装飾キーの同時押しの場合の挙動を記述しています。

### LICENSE

#### ハードウェア

回路図, パーツリスト, 基板配線図などハードウェア部分

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="クリエイティブ・コモンズ・ライセンス" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />この 作品 は <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">クリエイティブ・コモンズ 表示 - 継承 4.0 国際 ライセンス</a>の下に提供されています。

#### ソフトウェア

本製品のファームウェアは[qmk firmwareのライセンス](https://qmk.fm/license/)に従います。
