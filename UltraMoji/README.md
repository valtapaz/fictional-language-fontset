# UltraMoji Font / ウルトラ文字フォント
A fan-made font for the writing system of the Land of Light （日本語は下にあります。）

## Basis
The alphabet of M-78, known as ウルトラ文字 or UltraMoji, is based phonetically on Japanese (which usually has a consonant component and a vowel component for each character), but its writing system splits the Japanese Kana into English-compatible symbols, making English use also possible. I wasn't able to find any fonts based on this language, so I decided to make my own.

(Below image for reference; image copyright Tsuburaya Productions)
![The Ultra alphabet](https://m-78.jp/wp-content/uploads/2021/07/%E3%82%A6%E3%83%AB%E3%83%88%E3%83%A9%E6%96%87%E5%AD%97.jpg)

Since Japanese does not include certain Roman letters (such as L or V), this font comes in two variants: 
 - M-78 Inochi, which uses self-made approximations of what these letters may look like. Most of these are preexisting letters with the same kinds of Dakuten (") or Handakuten (°) that separates the UltraMoji (and Japanese) letters T and D, although X had to be more custom, combining a K and an S into one symbol. 
 - M-78 Seigi, which drops any non-Japanese letters, save reusing the K symbol for C. 

In UltraMoji, direct vowels (i.e. ones that are not preceded by a consonant) have a symbol that exists neither in English nor in Japanese; I have assigned that symbol to the forward slash for now (/), but in the future I would like to integrate it into the OTF features listed below.

## OTF Notes
While releasing as a TTF would be more universally compatible, some Japanese elements retained by UltraMoji made it unfeasible without a more complex format. The OTF font allows for the following features: 
 - "N": Japanese/UltraMoji has two uses for this letter: one as a consonant, and one when next to a vowel. The OTF will default to the consonant N, but will automatically change it to the with-vowel form when vowels (including Y, as it's closer to a vowel in English than in Japanese)
 - "W": this character interacts with other characters differently, with each UltraMoji vowel component placed inside of the consonant one rather than next to it. The OTF uses a consonant-only form of W by default, but will automatically replace a W followed by a vowel (again, including Y) with this form. I do not know whether the intent was to place all letters, consonant or vowel, inside the W character, so consonants are not included here, although I might later add the letter H in this ruleset given how frequently it appears next to W in English. 

## Misc
To my knowledge, the canon UltraMoji does not include numbers, so I included some Ultra signatures in lieu of them. Numbers 1-9 represent the nine Showa Ultra Brothers from Zoffy to 80, while the number 0 is, well… Zero. (Part of me wanted to take the joke further and put Seven and 80 under 7 and 8, but that would just jumble and confuse the rest of the content.)

Regarding uses, the LICENSE file goes into more detail, but basically: If you are working with Tsuburaya Productions officially and would like to use this font in any official capacity, I would love it if you did so, but I'd ask that you let me know in advance (you can reach out to me on Twitter via @MxylValtapaz). Beyond that, this font should not be used for commercial purposes by businesses unaffiliated with Tsuburaya Productions. 


## 日本語
（悪い日本語で書いてごめんなさい）
M78のウルトラ文字は日本語のひらがなみたいけど、この文字は英語で書ける可能性もあると思います。フォントを探したけど見つけられなかったから、一人で作ってみました。このフォントが二つあります：
 - M-78_Inochi (命).otf - 英語でXやLみたいな日本語にあらない文字があるから、このフォントに自分の作った文字があります。濁点と半濁点をを使ってみたけど、Xの方が新たな文字をいりました。
 - M-78_Seigi (正義).otf - このフォントには作ったXやLがありません。日本語だけで書くと、このフォントはInochiと同じみたいです。

ウルトラ文字の「あ・い・う・え・お」の前に日本語や英語にあらない文字があります。今のところ、この文字はスラッシュ「/」です。小さいかながまだありません。

## OTFについて
TTFほど全てのシステムと互換性ではないが、より多くの機能を持っています。
 - 日本語と同じ、ウルトラ文字で「ん」と「な・に・ぬ・ね・の」の「N」が違っています。OTFで「N」を書くと「ん」が現るんですが、「NA」や「NI」や「NY」を書くとウルトラ文字の他の「N」になります。
 - 「わ」について、ウルトラ文字の母音は父音の中にあります。OTFはこのルールに従う事が出来ます。今母音だけがWに入っています。

## その他
ウルトラ文字に数字があらないかもしれません。その代わりに、ウルトラ兄弟の名前をお借りしました： 1-9はゾフィーからウルトラマン80までの名前です。私のまあまあ頭は「もしかして、ゼロはゼロでしょう？」って思ったから0はそのウルトラです。
７
円谷プロダクションか円谷プロのパートナーで働けば、円谷に使っても素晴らしいです。それ以外、これはファンのためにあるから商用目的、そしてヘイトスピーチやR18目的で使わないで。

読んでありがとうございます。一緒に正義や命のためにがんばりましょう！
