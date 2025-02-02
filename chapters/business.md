# 仕事が忙しくてOSS活動に時間を割けない！

「OSSの開発に関わるのはとても有意義だと分かってはいるけど、プライベートな時間や睡眠時間が削られてしまうのが辛い……」という声はよく聞かれます。筆者も、OSS以外にも映画も見たければ遊びにも行きたい思いがあるので、気持ちはよく分かります。

もしあなたが業務上でOSSを使用しているなら、筆者としては、それらのOSSへのフィードバックを*業務の範疇*として認めてもらうように、上司やマネージャーに交渉してみて頂きたいです。

本章では、そのような交渉の材料になる情報を色々ご紹介します。うまくいけば、あなたも業務時間中に堂々とOSSにフィードバックできるようになるかも……？


## 企業とOSSの健全な関係って？

今現在OSSを利用しているにも関わらず、OSSにフィードバックをしていない、という企業は多いでしょう。そのような企業にとって、OSSは単に*「無料で手に入る、そこそこ質のいい商材や道具」*と認識されているのではないでしょうか。

その認識のもとでは、OSSへフィードバックするのは*「余計なコスト」「余計なリスクを増やすこと」*と捉えられるのも致し方ないでしょう。たとえば、以下のような疑問を持たれているかもしれません。

* OSSというのは、先進的なことをやってる企業だけが積極的に関わるもので、*そうでない泥臭いビジネスをしている我が社には関係ない*のではないか？
* 業務時間は自社の業務に集中するべきで、*業務外の*OSSなんかにうつつを抜かしていては、仕事にならないのではないか？
* 改良の成果を公にフィードバックしてしまうと、*我が社の競争力が失われて、ビジネス上で不利になってしまう*のではないか？

場面や状況によっては、これらの疑問が当を得ていることもあります。

しかし、それは言い換えれば、この種の懸念は取り越し苦労である場合もある、ということです。それどころか、*自社の利益のためと思ってした判断が、自社の不利益になる*ことすらもあります。

企業がOSSに関わるときに大切なのは、「*リスクの内容を適切に把握して、適切に怖がる*」考え方です。リスクの内容を把握しないまま闇雲に怖がっていても、効果がないどころか、逆効果になってしまいかねません。


## フィードバックしないと損をする！

### 売名上等！

組織名を公にした状態でOSSにフィードバックすることには、*OSSに関心がある技術者に対する組織の知名度の向上や、好感度の向上*の効果が見込めます。所属組織を明らかにしているメンバーがOSSに積極的にフィードバックしていると、「この組織はOSS開発に理解がある」「この組織に所属している技術者にはちゃんとした知識がある」ということの間接的なアピールになるからです。

OSSプロジェクトに寄附をしたり、技術イベントにスポンサーとして資金を提供したりブースを出したりすることも、「親OSS」であることのアピールになります。しかし、ニュースリリースやイベントの時しか名前を見かけないのでは、現場の開発者の印象に残りにくいのは否めません。

それに対し、イシュートラッカーやリポジトリ上でその組織の所属エンジニアが積極的に活動していると、プロジェクト関係者やユーザーからの印象は爆上がりです。もしかしたら、*その様子を見た優秀なITエンジニアが転職を検討してくれる*かもしれません[^recruiting]。

[^recruiting]: 実際に、そういう経緯で当社を知って応募してきて下さった方もいました。

また、フィードバックを通じてOSSプロジェクトに還元をすることは、*コミュニティとの良好な関係*を築くことにもつながります。逆に言えば、フィードバックをしなさすぎると、OSSプロジェクトから嫌われて*排除されてしまう*リスクがあります。

実際に2018年の半ば頃、大手クラウドベンダーに対してRedis、MongoDB、KafkaなどのOSSの開発元が、これらのOSSをクラウド事業の基盤に利用して得た利益を技術コミュニティに十分に還元していないと批判して、一部のソフトウェアについてクラウドビジネスでの商用利用を禁止する形にライセンスを変更した[^non-oss]、ということが話題になっていました[^change-to-non-open-license]。

[^change-to-non-open-license]: AWSなどの「オープンソースのいいとこ取り」に開発元が猛反発、続々とライセンス変更 ｜ビジネス+IT https://www.sbbit.jp/article/cont1/36018
[^non-oss]: この結果MongoDBが採用するようになった「Server Side Public License（SSPL）」や、RedisやKafkaから分離された一部のモジュールに設定されたライセンスは、オープンソースライセンスではないため、これらは「OSS」ではなくなっています（RedisやKafkaのコアモジュールは依然としてOSSです）。

このような点を意識してフィードバックを行うことを、「売名行為だ」と非難する向きもあるかもしれません。しかし、無意味なフィードバックでかえって開発コミュニティに負担をかけてしまっている、ということでもない限り、*良質で有用なフィードバックが多くもたらされる*のは、OSSプロジェクトにとっては単純にありがたいことです。

また、OSSの世界には「実際に手を動かす人が誰よりも正しい」という共通の価値観があります。自分では手を動かさないでいて、他人のことを「売名行為だ」と非難する人の言うことは、あまり気にする必要はないでしょう。

### 自社製品の競争力を維持するために

「うちの会社は技術コミュニティと仲良くなくてもべつに構わない。そういう所から人を採りたいとも特に思っていない。うちはOSSを使って製品やサービスの価値を高めたいだけだ……」という場合でも、フィードバックにはメリットがあります。というよりも、*フィードバックしないことにデメリットがあります*。

自社製品やサービス自体、あるいはその開発過程で使用する（依存する）OSSには、不具合が含まれている場合があります。

枯れたバージョン[^good-old-version]だけを使えばいい、と思うかもしれませんが、十分に枯れたバージョンは今のニーズに対して機能が不足していがちなので、そのままでは要件を満たせないことも珍しくないです。結局、*不具合を直しながら最新の開発版を使ったり、自社製品向けに独自の改変を加えたり*、といった形で何らかの変更をすることになります。

[^good-old-version]: エンジニアリングの世界では、市場に出回った後に十分な時間が経過し、不具合が修正され尽くして、運用ノウハウが十分に蓄積され、予想外のことが起こるリスクが低くなった状態のことを「枯れた」と形容します。

そういった変更はあくまで「作業を行った時点のリビジョンに対する変更」なので、そのOSSを更新すると、同じ変更を適用できなくなる場合があります。

しかし、だからといって使用するOSSのバージョンを固定してしまうと、そのバージョンが致命的な脆弱性を含んでいた場合、*自社製品までもが脆弱な状態が長く続いてしまいます*。製品開発のプロセス上も、自社の*顧客に対する責任*の面でも、これはリスクです。

### GitHub社の事例に学ぼう

*修正や必要な変更をフィードバックしてOSS本体に取り込んでもらっておけば、そのようなリスクを減らせます*。そうしておけば、新しいバージョンがリリースされた際も、スムーズにそのOSSの更新を自社製品に反映できます。2019年に行われた、GitHubでのRails 6.0への移行[^github-moves-to-rails-6]は、この話の非常に分かりやすい例です。

[^github-moves-to-rails-6]: GitHub、Rails 6.0へのアップグレードを完了 | マイナビニュース https://news.mynavi.jp/article/20190910-891948/

GitHubのサービスはRuby on Railsの上に構築されていますが、多くの人が利用するサービスなので、GitHub社としてはいつまでも古いRailsを使い続けるわけにはいきません。しかし、Railsの新バージョンが公開されてから移行作業を始めたのでは、まず単純に作業に時間がかかりますし、それだけでなく、*移行を始めてから発覚したRails自体の不具合や非互換の問題への対処*によっても、作業期間はどんどん延びていってしまいます。

そこでGitHub社では、Rails 6.0について*開発段階から積極的にフィードバックを行い、事前にRails側の不具合や非互換に関する懸念をあらかた解決しておく*方針をとったそうです。これにより、あれだけの大規模のサービスであるにも関わらず、サービスで使用するRailsのバージョンの切り替え作業は、*Rails 6.0の公開からわずか9日で完了できた*といいます。

GitHubのようなWebサービス企業だけでなく、サーバー向け製品やソリューションビジネスの開発・販売を手がける企業でも、同様のことが言えます。実際に、NEC・日立・富士通・日本IBMといった大企業はLinuxカーネルにコントリビュートしていることで知られています[^kernel-contribution-by-japanese-big-companies]し、組み込み分野ではルネサスからのコントリビュートも有名です[^kernel-contribution-by-renesas]。彼らも自社製品やサービスにLinuxを組み込む都合上そうしているのであって、その目的は基本的に*「自社の利益のため」*なのです。

[^kernel-contribution-by-japanese-big-companies]: 富士通には約250人のLinuxカーネル開発者がいる | 日経クロステック（xTECH） https://xtech.nikkei.com/it/article/Interview/20090107/322420/
[^kernel-contribution-by-renesas]: LinuxCon最終日レポート、大物カーネル開発者がアドバイスする「Kernel Developer Panel」など - クラウド Watch https://cloud.watch.impress.co.jp/docs/event/649881.html

## さらに先のことを見据えたフィードバック

### OSSでもロビイングは必要

フィードバックは、今ある物についてだけでなく、*これから実装される機能、これからそのOSSが向かっていく方向性そのもの*についても行えます。

自分にとって嬉しい方向へ社会が向かっていくように、法律や制度を作る立場の人に意見や情報を伝え、これから作られる法や制度に間接的に影響を与えていくことを、*ロビイング（ロビー活動）*と言います[^lobbying]。OSSでは、コードに直接変更を行っていく決定権があるのはコミット権を持つ開発者の人達なので、彼らの判断に影響を与えるよう働きかけるのは、一種のロビイングと言えるでしょう。

[^lobbying]: たとえば、営利企業は規制緩和や税制改革をしてもらおうとロビイング活動をしていますし、生活困窮者を支援する人達は社会保障制度を整備してもらおうとロビイング活動をしていますし、漫画家協会は著作権にまつわる制度の整備をしてもらおうとロビイング活動をしています。

*イシューを立てて要望を伝える*のは、典型的なロビイングです。例として、筆者が所属する株式会社クリアコードでの事例をご紹介します。

　

クリアコードは「Firefoxの法人向け技術サポートサービス」を提供しており、その中では、「顧客企業のニーズに合わせたFirefoxのカスタマイズ」も行っています。

そのFirefoxについて、「カスタマイズの自由度を下げて、ある程度決まった項目のカスタマイズだけを『ポリシー設定』として行えるようにし[^firefox-policy-engine]、速度や安定性を向上させる」方針での改革が進められることが決定した、という報せは、クリアコードのビジネスにとっては見過ごせない情報でした。顧客企業の望むカスタマイズができないと、顧客満足度が低下し、顧客離れにつながって、ひいては会社の収益源につながるからです。

[^firefox-policy-engine]: Mozilla Firefox ESR60でのPolicy Engineによるポリシー設定の方法と設定項目のまとめ https://www.clear-code.com/blog/2018/5/12.html

そのため、筆者は自社のビジネス上で頻出のカスタマイズ項目を「ポリシー設定」のリストの中に入れてもらうよう、イシューを立てて積極的に提案していきました。また、そのうちいくつかはパッチの提供もしました。提案のすべてが採用されたわけではありませんが、重要なものは採用してもらえたため、クリアコードは今も安心して「Firefoxを顧客企業のニーズに合わせてカスタマイズする」サービスを提供できています。

　

このようなロビイングは、新しいイシューを立てるだけでなく、*すでに立てられて動き始めているイシュー*に対しても行えます。たとえば、ある機能が「この機能は利用者が少ないようだ」という理由で削除されようとしているとき、「うちの顧客企業では広く使われていて、非常に重要だ」とコメントして反対票を投じる、というのはその分かりやすい例です。

### OSSでのロビイングで押さえておくべき点

このようなロビイングをするときのポイントはいくつかありますが、何より大事なのは、*「企業の代表者」ではなく「開発コミュニティの一員」として振る舞う*ことです。

具体的には、「うちではこういうビジネスをしている。だからこうして欲しい」といった言い方は避けたほうがよいでしょう。というのも、よほどの大口スポンサーでもない限り、*よその組織の都合に従う動機は、OSSプロジェクト側にはほとんどない*からです。

それにもかかわらず自社の都合を前面に出すと、*「道理の通らない話をゴリ押ししようとしている」という見え方になり、非常に印象が悪い*です。開発社側としては、「そんなに大事ならスポンサーになってくれ」「それか、自前でフォークしてメンテナンスしてくれ」と反感を抱いてしまいます。

　

そのような失敗の事例として、「Mozillaの証明書ストアに日本政府の公開鍵基盤（GPKI）の認証局証明書を入れてもらえなかった」というエピソード[^mozilla-rejected-gpki]があります。

[^mozilla-rejected-gpki]: Mozilla、日本政府の公開鍵基盤（GPKI）について「対応予定なし」というステータスに https://it.srad.jp/story/18/03/01/072235/

この事例では、日本政府を代表する立場と思しきユーザー[^anonymous-apca]が、Mozillaの求めるセキュリティ水準を満たさない状態であるにも関わらず、その状態を解消するための行動はしないで、ただ「日本政府」の権威のもとに要求だけを繰り返す、ということが行われていました。それに対するMozillaの対応は、「運用ルールに従ってくれない以上、証明書は入れない」というものでした。*一国の政府だからといって、OSSの世界では特別扱いはされない*、ということがこの例からは見て取れます。

[^anonymous-apca]: ユーザー名は「apca」で、これは「Application Certification Authority」の略と思われます。メールアドレスは「apca@gpki.go.jp」で、セカンドレベルドメイン「go」が「government（政府系）」であることから、政府で働く職員が複数人で共用する「代表者アカウント」だと思われます。

![一人の開発者として信頼を得る必要がある](images/business-personaility.png)

そうではなく、ロビイングにあたっては、「この機能は実際にユーザーのニーズがあり、機能を入れると、*このOSSプロジェクトのユーザー全体にメリットがある*」ということを、そのような状況を知る一人の開発者として訴える、という形を取るのがよいです。筆者も、前述のポリシー設定の提案にあたってはこの点に気をつけて提案することを心がけました。筆者は詳細を追っていませんが、前述のRailsに対するGitHub社のフィードバックも、そういう形を取っていたのではないかと思っています。

もちろん、提案はあくまで提案なので、採用されないこともあります。筆者のした提案も、ユーザー全体のメリットが大きそうな物から採用され、メリットの小さい物は却下されました。そのような場合でも、*捨て台詞を吐いて開発者を罵るようなことをしてはいけない*、というのはすでに述べたとおりです。

### 日頃からの情報収集を！

また、適切なタイミングでロビイングを行うためには、*情報収集*も重要です。

イシュー上で行われている議論には、*議論が行われているまさにそのとき*[^realtime-discussion]に話に加わる必要があります。そのときの参加者間で議論がし尽くされて決定が下ってしまった後で、ノコノコやってきて「これは困る」とコメントしても、時すでに遅しです。そのイシューでの決定を受けて、すでに実際に作業が進み始めている、という状況では、プロジェクトの翻意にはまず期待できません。

[^realtime-discussion]: といっても、口頭でのリアルタイムの議論でないため、イシュー上での議論は、短ければ数日から、長ければ数ヶ月といった時間をかけて行われることもあります。

むしろ、普段からそのOSSプロジェクトに深く関わっていて、開発者からの信頼を得られていると、「この話題については彼が詳しいから、耳に入れておいたほうが良さそうだ」ということで、*プロジェクトの側から情報が回ってくる*ことすらあります。企業が著名なOSSプロジェクトのコミッターを雇用するケースは、そのような場面で自社にとって不利にならないように物事を進めてもらうための交渉役としてのはたらきに期待して、という部分もあるようです。

### 自社製品の寿命を延ばすために

資金援助や、プルリクエストなどで労力を提供するといったフィードバックには、*プロジェクトの継続への寄与*という効果が期待できます。

OSSの中には、多くのプロジェクトから利用され非常に重要度が高いにもかかわらず、実際の開発やメンテナンスはたった一人の個人によって行われている、というものが度々あります。そのようなプロジェクトは、*開発者の個人的な事情で突然終了してしまう*ことがありますが、かといってそれに代わる実装が存在しないことも多く、企業にとっては大きなリスクとなってしまいます。

実際に、様々なソフトウェアで安全な通信のために使われているライブラリであるOpenSSLについて、2014年にHeartbleedと呼ばれる深刻な脆弱性が発覚したときには、資金不足のためフルタイムの開発者は一人だけしかいない状況であった[^openssl-developers]ことが大きな話題となりました。

[^openssl-developers]: OpenSSLの場合、その当時はフルタイムでないコントリビューターは10人程度はいたそうです。しかし、Heartbleedの脆弱性はその状況下で2年以上気付かれずに存在していたということで、十分な開発体制でなかったと言わざるを得ないでしょう。

金銭的な寄付を募っているOSSであれば金銭的に支援できますが、寄付を募っていない場合、できる支援の手段は、実際に手を動かすことしかありません。そのOSSに長生きして欲しければ、積極的にフィードバックしたほうがよいということです。

### リスクマネジメントのためという観点

ソフトウェアが高度化・複雑化している現代では、一社で製品の上から下まで構成要素すべての面倒を見続けるのは、現実的ではありません。現実的な理由からOSSを構成部品に採用する必要に迫られることは多く、OSSプロジェクトの去就がビジネスを左右してくる場面も多いです。

「ある日突然ハシゴを外されてしまう」悲劇を避けるためには、企業側もある程度積極的にOSSに関わっていく必要があります。「社会貢献」のような美しい話でも、「攻めの経営」のようなキラキラした話でもなく、*現実的なリスクマネジメントとして、企業にはOSSに関わる動機がある*と言えます。

そう考えると、「担当者が個人的に、定時後や深夜に、眠い目を擦りながら自分のプライベートな時間を削ってOSSに関わる」というのは、企業としては*いつ破綻するか分からない爆弾を抱えた状態*と言わざるを得ません。きちんと枠を取って、定時の中で*業務の一環として責任感を持ってOSSに関われるようにする*、それが自社のビジネスために大事なことだと言えるのではないでしょうか。


## リスクを最小化して、メリットを享受するために

### フィードバックは「できるところから」「リスクの低いところから」やろう

会社によっては、外に情報を一切出せなかったり、いわゆる「GPL汚染」を懸念して（これについては別途詳しく述べます）、OSSを持ち込むことはおろかOSSのソースコードを見ることすら禁止されている、という場合もあると聞きます。

*秘密の情報が組織の利益の源泉になっている*ケースでは、情報が公になることに強い忌避感を抱くのも道理です。実際に、先に紹介した「RedisやMongoDBらが大手クラウドベンダーをフリーライダー[^free-rider]として批判した」事例は、「自社のビジネスの基盤を自ら競合相手に気前よく渡してしまい、後から慌てている」という見方もできます。

[^free-rider]: OSSプロジェクトに益をもたらさずに利益だけを持っていく人や組織のことを、運賃を払わずに電車やバスなどに乗る人になぞらえて言った言い方。

とはいえ、すでに述べたとおり、使っているOSSにまったくフィードバックしないことにもリスクがあります。リスクを最小化するためには、*自社の競争力・利益の源泉がどこにあるのかをきちんと分析し、どこまでは秘密にしないといけなくて、どこからは公にしても大丈夫か、ということを改めて考える*必要があります。

* 「製品・サービスそのものには特別な技術は使っていないが、その開発工程のツールには特別な技術が含まれている」場合なら、製品・サービスの構成部品に関するOSSへのフィードバックからであれば、低リスクで始められるでしょう。
* 逆に、「開発工程のツールには特別なものはなく、製品・サービスそのものが特別な技術で成立している」場合なら、ツールに関するOSSにフィードバックすることから始めるとよいでしょう。

筆者の所属会社の場合、以下のような方針をとっています。

* OSSに対する法人向けのサポートビジネスに関しては、製品そのものに秘密はなく、問題の原因を調べ解決する能力のほうを価値としています[^skill]。そのため、サポートの過程では対象のOSS自体や関連するOSSに積極的にフィードバックしています。
* その一方で、非公開のソフトウェアの受託開発案件に関しては、開発の成果自体は当然非公開ですが、その過程で使用したツール類のほうにはフィードバックをしています。

[^skill]: 秘密の技能と言うよりは、言語化や共有が難しい属人的な技能という面が強いです。

このように、*1つの会社であっても、事業や案件の性質ごとに何を公開するか・できるかは変わってきます*。フィードバックは「できる所から」で構わないのです。

### 社名を出すべき？　出さないべき？

ここまでで名前を挙げたいくつかの会社は、社名を出してOSSに関わっています。その中には、メディアの取材に応じて知られるようになった事例もあれば、積極的に広報している例もあります。これらの事例を見ていると、「OSSに関わるなら社名は必ず前面に出さないといけない」という印象を持つかもしれません。

筆者としては、社名を堂々と出してOSSに関わる企業が増えてくれると嬉しいのですが、とはいうものの、*無理に社名の公表をおすすめするものでもありません*。たとえば、特定の分野のOSSに特定の会社のエンジニアからのフィードバックが急に増えたら、「その会社がその領域で何かしようとしている」と外部に悟られる可能性はあります。秘密のプロジェクトを進めたい場合、そういったリスクは避けたいところでしょう。

社名をアピールすることの効果に特に期待しないのであれば、社名を公表しない状態で淡々とフィードバックして問題ありません。その場合でも、*「自社で変更を抱え込むことのリスクを低減する」「意見を届けて、自社に不利益にならないような判断をしてもらう」*といった目的は問題無く達成できます。

むしろ、社名を伏せることには、ロビイングの説明で紹介した日本政府のGPKIの事例のような、「組織名を笠に着てしまい、開発者コミュニティと適切に接することができない」失敗を避けやすくなる効果があると言えるかもしれません。

### 企業とOSSとの付き合い方のガイドライン

こういったことを一人一人のエンジニアが自分で判断できるとよいのですが、新人とベテランで判断が変わる場合は往々にしてあります。特に、経験が浅いほど判断がブレてしまうものです。ある人は問題無いと判断したことを別のある人は問題ありと判断した、ということがあまりに頻繁に発生するようだと、判断基準がよく分からない人にとっては、萎縮してしまって身動きが取れなくなります。

そういった問題の発生を防ぐためには、*その企業なりの状況を踏まえたガイドライン*を策定するのが有効でしょう。このような、*プロプライエタリな製品・サービスを事業の柱としていつつも、OSSとの適切な距離感を図っていこうとする場合のガイドライン策定*の事例として、サイボウズ社が2018年に公開した「OSSポリシー」が挙げられます。

[サイボウズのオープンソースソフトウェアポリシーを紹介します - Cybozu Inside Out | サイボウズエンジニアのブログ](https://blog.cybozu.io/entry/oss-policy)

この文書では、コードの著作権を誰が持つのか、商標の取り扱いをどうするのか、社内でOSSを使用する場合はどう使えばよいのか、等々、*OSSの使用・公開・フィードバックのさまざまな場面で必要となる判断の基準*が示されています。これからOSSに関わっていこうとする企業にとって、大いに参考になる資料と言えます。

なお、このOSSポリシー自体はパブリックドメイン扱いとされており、自社でそのまま運用することも、自社の状況に合わせてカスタマイズすることもできます。個人としてはOSSへのフィードバックで迷うことが無くなった人でも、暗黙知として蓄積された判断基準を、社内で他の人に分かりやすい形で共有するのは難しいものです。本書と併せて読んで、判断基準の可視化の参考にしてみてください。

### [column] コラム：Amazonは全くフィードバックしていなかったの？

本文で触れた「大手クラウドベンダーが得た利益をコミュニティに十分に還元していない」という批判は、実際には、主にAWSを擁するAmazonに対して向けられたもののようです。では、Amazonはこれらのプロジェクトに実際にはどのくらいフィードバックをしていたのでしょうか？

この点でわかりやすい指標としては、プルリクエストを通じてマージされた変更の数や、それに関わった人の数が挙げられます。[筆者が簡単に調べてみたところ](https://twitter.com/piro_or/status/1225229158818533377)、各プロジェクトのコントリビューターの中でコントリビュート数が多い上位100人の中で、プロフィールにはっきりと「AWS」または「Amazon」と所属を書いている人の状況は、以下のようになっていました。

|{width=18} プロジェクト |{width=18} 全体のコントリビューター数 |{width=18} 全体のコミット数 |{width=18} Amazonからのコントリビューター数 |{width=18} Amazonからのコミット数 |
| ------------ | -------------------------- | ---------------- | --------------------------------- | ---------------------------------------------- |
| [Redis](https://github.com/antirez/redis) | 328 | 8788 | 2 | 33 |
| [MongoDB](https://github.com/mongodb/mongo) | 397 | 50094 | 0 | 0 |
| [Kafka](https://github.com/apache/kafka) | 623 | 7067 | 1 | 84 |

未調査の部分も多いため、この数字がすべてではありませんが、RedisとKafkaに関しては、まったくフィードバックしていないわけでもないようです。少なくとも、筆者がFirefoxやThunderbirdにフィードバックした回数よりは多い気がします。

ただ、これらのOSSプロジェクトのオーナーは自身でもクラウドサービスを提供しているクラウドベンダーで、AmazonのAWSはまさに*商売敵である*、という点には注意が必要です。

仮に商売敵であっても、これらのOSSプロジェクトについて各々が投じた費用の比率と、そこから得られた収益額の比率が近いのであれば、各ベンダーはこれらのOSSプロジェクトを*共通の基盤として共同で開発している*、という状況だと言えます。しかし実際には、クラウドベンダー業界におけるAWSのシェア占有率は、これらのプロジェクトのオーナー達に比べれば圧倒的に高いです。MongoDBの創業者が言うように、得ているリターンに対してAmazonが支払っているコストがあまりに小さすぎる、いびつな状況にあったのは間違いありません。

Amazonは「良い商材をなるべく安く仕入れて、なるべく高く売る」小売店の戦略に忠実に商売している、ということを考えると、Amazonがクラウドベンダー事業を行う以上は、このような状況が発生してしまうのは必然とも言えます。

AWSのサービス開始は2006年、MongoDBの開発の開始は2007年でした。彼らは、先行するベンダーとも協業して「クラウド業界」を盛り立てていければと思っていたのかもしれませんが、だとすれば、*「協力する気が薄い競合プレイヤーがいるところに、無防備に自社のコア商材を公開しながら参入してきた」*形になってしまったということで、甘い判断をしてしまったと言えそうです。この事例を見ていると、OSSとビジネスの関係について改めてよく考える必要性を意識させられます。

なお、筆者（の所属する会社）が商売している領域は、Mozillaが直接は商売をしていない領域なので、両者は競合関係にはありません。*OSSを「使って」ビジネスをするときは、それぞれの商売上の領域を侵さないような棲み分けが大事だ*、ということは言えそうです。

### [/column]
