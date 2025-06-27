# web-nixie-like-clock
ニキシー菅風の時計アプリです、それ以上でもそれ以下でもありません。

HTML, CSS, JavaScriptのみで作成された、レトロなニキシー管風のWeb時計です。年月日と時刻（ミリ秒まで）を、雰囲気のあるグローエフェクトで表示します。

![image](https://github.com/user-attachments/assets/3b7536cc-a3a0-4f92-92da-3ea788988751)

https://you-sk.github.io/web-nixie-like-clock/

## 主な特徴 / Features

  * **統一されたニキシー管デザイン**: 年月日と時刻を、温かみのあるオレンジ色の光で表示します。
  * **詳細な時刻表示**: 年(下2桁)、月、日、時、分、秒、ミリ秒までリアルタイムで更新します。
  * **リアルなエフェクト**:
      * 数字が発光するグローエフェクト (`text-shadow`)
      * ガラス管の立体感と反射光 (`box-shadow`, `gradient`, `::before`)
      * 点灯していない数字がうっすらと背景に見える表現
  * **レスポンシブ対応**: PC、タブレット、スマートフォンなど、さまざまなデバイスの画面サイズに最適化されています。
  * **軽量・依存なし**: モダンなWebブラウザだけで動作し、外部のJavaScriptフレームワークは使用していません。
  * **雰囲気のある背景**: レトロな質感を演出するノイズとビネット効果をCSSで表現しています。

## 技術スタック / Tech Stack

  * **HTML5**
  * **CSS3**
      * Tailwind CSS (CDN経由で使用)
      * カスタムCSSプロパティ
      * Flexbox
      * CSS Animations (`@keyframes`)
  * **JavaScript (ES6+)** (Vanilla JS)
  * **Google Fonts**
      * [Cutive Mono](https://fonts.google.com/specimen/Cutive+Mono) (数字フォント)
      * [Orbitron](https://fonts.google.com/specimen/Orbitron) (区切り文字フォント)

## ライセンス / License

このプロジェクトはMITライセンスの下で公開されています。

