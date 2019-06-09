'''IOTA'''（アイオータ）は、[https://www.iota.org/the-foundation/the-iota-foundation IOTA財団]を主導に[[オープンソース]][[プロトコル]]に基づいて開発が行われている[[Peer to Peer|P2P]]型決済及びデータ共有網、[[暗号通貨]]である。[[ビットコイン]]など他の[[ブロックチェーン]]型暗号通貨とは違い、'''タングル'''（英: Tangle）と呼ばれる[[有向非巡回グラフ]]（英: Directed acyclic graph, '''DAG'''）を利用<ref>{{Cite web|url=https://assets.ctfassets.net/r1dr6vzfxhev/2t4uxvsIqk0EUau6g2sw0g/45eae33637ca92f85dd9f4a3a218e1ec/iota1_4_3.pdf|title=IOTA Whitepaper  1.4.3|accessdate=2019 4/4|publisher=}}</ref>して非許可型分散型台帳を実装している<ref>{{Cite web|title=What is IOTA?|url=https://www.iota.org/get-started/what-is-iota|website=www.iota.org|accessdate=2019-04-04|language=en}}</ref>。タングル上で行われる価値交換は暗号通貨である'''IOTAトークン'''を介して行われ、決済記録を含むタングル上でのあらゆるデータの読み書きに使われる形式及びタングルの仕組みそのものを一括りにして'''IOTAプロトコル'''と呼ぶこともある。{{Infobox currency
| currency_name               = IOTA
| image_1                     = [[File:iota_logo.png |frameless |Latest foundation logo]]
| image_title_1               = Prevailing IOTA logo
| iso_code                    = IOT
| iso_number                  =
| superunit_name_1            = KiloIOTA (Ki)
| symbol                      = IOT, MIOTA<ref name="CMC">{{cite web |url=https://coinmarketcap.com/currencies/iota/ |title=Coin Market Cap - IOTA (MIOTA) |language=en |accessdate=2018-05-22}}</ref>
| superunit_ratio_1           = {{val|e=3}}
| superunit_ratio_2           = {{val|e=6}}
| superunit_ratio_3           = {{val|e=9}}
| superunit_ratio_4           = {{val|e=12}}
| superunit_ratio_5           = {{val|e=15}}
| superunit_name_2            = MegaIOTA (Mi)
| superunit_name_3            = GigaIOTA (Gi)
| superunit_name_4            = TeraIOTA (Ti)
| superunit_name_5            = PetaIOTA (Pi)
| date_of_introduction        = {{Start date|df=yes|2016|6|11}}<ref name="First Chapter"/>
| date_of_introduction_source = [[Initial coin offering]]
| using_countries             = {{World}}
| issuing_authority_title     = IOTA Foundation|issuing_authority_website=iota.org
| inflation_rate              = 2,779,530,283,277,761 IOTA
| inflation_title             = 総発行量
| printer                     =
| printer_website             = {{URL|https://www.iota.org}}
| mint                        =
| mint_website                =
| footnotes                   = {{notelist |group=infobox}}
}}
2016年7月11日にIOTAのオープンベータテストが開始された<ref name="First Chapter">{{cite web |url=https://blog.iota.org/iota-first-chapter-synopsis-506fdf874437 |title=IOTA First Chapter Synopsis |year=2016 |last=Sønstebø |first=David |language=en |accessdate=2018-05-22}}</ref>。

IOTAの[[トランザクション]]はP2Pネットワークの参加者が共有するタングル上で、仲介者なしにユーザーが発行する。
ユーザーがトランザクションを発行するためには、タングル上の他の２つの過去のトランザクションを承認しなくてはならない<ref name="Tangle">{{cite web|url=https://iota.org/IOTA_Whitepaper.pdf|title=The Tangle Whitepaper|year=2018|last=Popov|first=Serguei|language=en|accessdate=2018-05-22}}</ref>。
送信されたトランザクションが、受け手から'''確定'''したと認められるためには、十分なレベルの承認を集めなくてはならない（つまり、他のユーザーたちから、十分な回数の承認を受けなくてはならない）<ref name="Consensus">{{cite web |url=https://github.com/noneymous/iota-consensus-presentation |title=IOTA Transactions, Confirmation and Consensus |year=2018 |last=noneymous |language=en |accessdate=2019-03-30|rel=harv}}</ref>。
このシステムは、中央格納[[データベース]]や単一の管理者を置かずに運用され、一般的な分散型台帳技術に固有の[[スケーラビリティ]]や取引手数料の問題に取り組んでいる<ref name="Forbes">{{cite web |url=https://www.forbes.com/sites/rogeraitken/2017/06/15/iotas-bitfinex-listing-surges-to-1-5b-record-breaking-crypto-capitalization-on-market-debut/#533e23f175a5 |title=IOTA's Bitfinex Listing Surges To $1.5B Record-Breaking 'Crypto' Capitalization On Market Debut |year=2017 |last=Aitken |first=Roger |language=en |accessdate=2018-05-22}}</ref>。

IOTAは、トランザクションで価値とデータを交換できる'''決済レイヤー'''と見なすこともできる<ref name="Primer">{{cite web |url=https://blog.iota.org/a-primer-on-iota-with-presentation-e0a6eb2cc621 |title=A Primer on IOTA (with Presentation) |year=2017 |last=Schiener |first=Dominik |language=en |accessdate=2018-05-31}}</ref>。
他の機能（例：[[スマート・コントラクト]]等）はその決済レイヤーの上層に構築される可能性があるが、IOTAのコア・プロトコルの開発は効率性の最大化に傾注されてきた。{{TOC limit}}

== 起源 ==
IOTAはデイビッド・サンステボ（David Sønstebø）とセルゲイ・イバンチェグロ（Sergey Ivancheglo）とドミニク・シーナー（Dominik Schiener）及びセルゲイ・ポポフ（Serguei Popov）博士の4名によって創設された<ref name="Primer"/>。
IOTAの起源は、2014年に4人が、[[モノのインターネット|IoT]]及び[[分散コンピューティング]]向けに全く新しいタイプの[[三進法]][[マイクロプロセッサ]]の開発を目指して内々に設立した[[ハードウェア]]の[[ベンチャー|スタートアップ]]にまで遡る。
4人は、この経験を通じて、IoTを実現可能にして[[マシンツーマシン|M2M]]経済の到来をもたらすには、安全な価値とデータの決済レイヤーが必要であることを認識した<ref name="First Chapter"/>。

4人は2010年〜2011年頃から[[ブロックチェーン]]界隈に関わってきて、分散型台帳技術に精通していた<ref>{{Cite web |url=http://businessblockchain.org/iota_dominik_schiener_interview_part1 |title=【IOTA創業メンバーDominik Schiener氏 BBC独占インタビュー】前編 |year=2017 |publisher=ブロックチェーンビジネス研究会 |accessdate=2018-06-02 |rel=harv}}</ref>。
2013年にはセルゲイ・イバンチェグロは、世界初の完全な[[プルーフ・オブ・ステーク]]を開発して、[[Nxt (仮想通貨)|Nxt]]というブロックチェーンに実装した<ref name="NXT Roadmap">{{cite web |url=http://www.nxter.org/bcnexts-nxt/ |title=BCNext's NXT |language=en |accessdate=2018-06-02}}</ref>。

4人は、このような経験を重ねて、IoTの基幹として必要な決済レイヤーを実現するために、2015年前半にIOTAの開発を始めた<ref name="Primer"/>。
公正な割り当てを確保するために、2015年11月から12月まで行われたクラウドセールでは、IOTAトークンの総供給数量が100％売り出されて、IOTA開発者や設立者たちには1枚のIOTAも割り当てられなかった。
[[ビットコイン]]1337枚相当の金額を（BTCやNXTやJinnトークンという形で）調達した<ref name="IOTA History">{{cite web| url=https://medium.com/konfid-io-blockchain-reports/iota-report-decoding-the-tangle-part-2-the-known-and-unknown-history-of-the-iota-project-3db9f5f3cfa3 |title=The Known and Unknown History of the IOTA Project |year=2018 |last=Konfidio |language=en |accessdate=2019-03-29 |rel=harv}}</ref>。
開発者や設立者たちへ配当されたIOTAが1枚もなかったことから、IOTAコミュニティーは非営利の'''IOTA財団'''を設立してドイツで登録するために、相当量のIOTAを寄附してIOTAプロジェクトのビジョンを支援することを決定した。
その後もIOTAコミュニティーは、大企業との協業やコミュニティー・プロジェクトや開発者の獲得のために資金を提供した<ref name="The Big Deal">{{cite web |url=https://forum.helloiota.com/17451/Archive-IOTA-Big-Deal |title=Archive: IOTA Big Deal |language=en |accessdate=2019-03-29 |rel=harv}}</ref><ref name="Ecosystem Fund">{{cite web |url=https://cryptoinsider.com/iot-operator-iota-launch-new-2-million-ecosystem-fund/ |title=IoT Operator IOTA Launch New $2 Million Ecosystem Fund |year=2017 |last=O’Higgins |first=Conor |language=en |accessdate=2019-03-29 |rel=harv}}</ref>。

2016年7月11日にIOTAのオープンベータテストが開始された<ref name="First Chapter"/>。
それから2017年6月12日に仮想通貨取引所Bitfinexに新規上場する<ref name="Bitfinex">{{cite web |url=http://blog.bitfinex.com/uncategorized/iota-launch/ |title=IOTA Launch |year=2017 |last=Bitfinex Blog |language=en |accessdate=2019-03-29 |rel=harv}}</ref>までの11ヶ月間は、ユーザー同士の相対取引（取引所を介さない売手と買手の直接取引）が行われていた。


== 設計 ==
=== タングル ===
IOTAは[[ブロックチェーン]]を用いる代わりに、DAGを使って分散型台帳を実装している<ref name="Tangle"/>。
'''タングル'''と呼ばれているIOTAのDAGプロトコルは、ブロックチェーンプロトコルを一般化したものである（ブロックチェーンはDAGの特殊なケースである）<ref>{{Cite web |url=http://cryptowiki.net/index.php?title=Blockchain-free_cryptocurrencies |title=Blockchain-free cryptocurrencies - CryptoWiki |website=cryptowiki.net |language=en |access-date=2019-03-30}}</ref>。
タングルは'''ブロック'''も'''チェーン'''もない構造となっているので、予めブロック時間を決めておく必要がなく、ネットワーク上のトランザクション数が増えると、最終的にトランザクションのスピードが速くなる。
しかし、トランザクションが確定されるまでの時間には、タングルの[[トポロジー]]やネットワーク内のノードの位置など様々な要因も影響する。
タングルはIOTAのトランザクションを保管する公開台帳であると同時に、非中央集権化されていて中央で管理する者は存在せず、[[メッシュネットワーク]]のトポロジーに従って組織化されるノード間のネットワークによって維持されている。
タングルは[[分散データベース]]として機能する。2019年4月現在はネットワーク上の各ノードにはタングルの全履歴が格納されている。
IOTAのトランザクションを送るためには、送り手はタングル上の他の二つのトランザクションを承認しなくてはならない<ref name="Primer"/>。
タングルのユニークな承認作業の並列化を可能としているのは、タングルが非同期型システムだからである。これは承認作業が逐次的に順番に行われる同期型のブロックチェーンとは対照的である。
IOTAネットワークを使用するための支払いは、（マイニング手数料を支払うのではなく）他の二つのトランザクションの承認という形で行われる。
そのために、承認者（ビットコインでは'''マイナー'''、プルーフ・オブ・ステークプロトコルでは'''ステイカー'''に相当）とトランザクションを送るユーザーはもやは別々の存在ではない。もっと簡単に言えば、IOTAネットワークでは、ユーザー全員がマイナー/ステイカーとなるのである<ref name="Tangle"/>。
タングルは[[バイナリ]]コードではなく三進法でプログラムされている。
三進法はバイナリに比べて効率性が有利である<ref name="Trinary">{{cite web |url=https://www.iota.org/get-started/faqs |title=Why does IOTA use ternary based logic? |year=2019 |last=IOTA Foundation |language=en |accessdate=2019-03-30 |rel=harv}}</ref>。

=== [[スケーラビリティ]] ===
[[File:Iota-tangle-1.png|thumb |'''IOTA Tangle'''
この図の各正方形は送られてきたトランザクションを表す。
新しいトランザクション毎に、タングルの中でランダムに選択された２つの未確定のトランザクションが承認される。
あるトランザクションに対する承認数<math>n</math>が一つ増えるごとに、そのトランザクションが正当なものである可能性が増えていき、閾値の<math>c</math>まで高まる。
この図ではピンクの正方形は<math>n>0</math>（承認数が１以上）であるが、<math>n<c</math>である（確定の閾値である<math>c</math>より小さい）ことを示している。
]]
各トランザクションの送り手は、タングル中の他の二つのトランザクションを承認する必要があるので、送られてくるトランザクションが多ければ多いほど、確定されるトランザクションの数が増える<ref name="Tangle"/>。
これはIOTAの[[スループット]]が、ネットワーク上のトランザクションの数に比例して拡大していくことを意味する<ref>{{Cite web |url=https://blog.iota.org/on-the-tangle-white-papers-proofs-airplanes-and-local-modifiers-44683aff8fea |title=On the Tangle, White Papers, Proofs, Airplanes, and Local Modifiers |year=2017 |language=en |last=Popov |first=Serguei |access-date=2019-03-30}}</ref>。
対照的に、従来のブロックチェーンは、予めブロック時間とブロックサイズを決めているので、スループットが制限されている<ref>{{Cite web|url=https://helloiota.com/iota-in-depth/ |title=IOTA IN-DEPTH |website=HelloIOTA.com |language=en |access-date=2019-03-30}}</ref>。
IOTAに先駆けて開始されたIoTと分散コンピューティング用に特化したCPUの開発は、現在も継続中である。
そのCPUによってハードウェアの性能が向上し、小さなエッジデバイスでも1秒間に何千回ものトランザクションが、あらゆるデバイス上で実行可能となる。
ハードウェアをサポートするこのCPUによって、ネットワークの処理能力のスケーラビリティは、理論的には物理法則（電波や光子の伝播）による限界があるのみとなる。
またそのハードウェア部品は、製造業者へ余計なコスト負担を増やすこともなく、オープンソースとなる<ref name="Transparency Compendium">{{cite web |url=https://blog.iota.org/the-transparency-compendium-26aa5bb8e260 |title=The Transparency Compendium |year=2017 |last=Sønstebø |first=David |language=en |access-date=2019-03-30}}</ref>。

=== トランザクション手数料===
IOTAのアーキテクチャーでは、トランザクション手数料は発生せず、承認者とユーザーは別々の存在ではない。
IOTAのネットワークを使うことによって、ユーザーはプルーフ・オブ・ワークを実行する承認者としての役割を果たして、タングル中の他の２つのトランザクションを承認する。
IOTAのプルーフ・オブ・ワークはまさに{{仮リンク|ハッシュキャッシュ|en|Hashcash}}に類似していて、[[スパム (メール)|スパム]]と{{仮リンク|シビル攻撃|en|Sybil attack}}を防ぐことを目的としている。
IOTAのプルーフ・オブ・ワークの難易度は高くなく、ノートパソコンやスマートフォンなどのほどんどのデバイスで実行でき、送り手のデバイスでも、受け手のデバイスでも実行できる。
あるいはプルーフ・オブ・ワークを効率的に実行できるように特化された外部のデバイスやサービスにアウトソースすることもできる<ref name="Powsrv">{{cite web |url=https://powsrv.io  |year=2019 |title=Fast and efficient PoWaaS (PoW-as-a-service) for your IOTA wallet, MAM-stream or any IOTA usecase requiring fast transaction turnout. |website=powsrv.io |language=en |access-date=2019-04-01}}</ref>。
このようにIOTAのプルーフ・オブ・ワークのシステム要件は、マイナーと承認者が別々の暗号通貨で使われているプルーフ・オブ・ワークと異なって、極小のマイクロコントローラーに適したものとなっている。
トランザクションと検証作業を同じ工程に配置することで、IOTAは承認作業が中央集権化するリスクを排除できるだけでなく、承認者に対してトークンの生成やトランザクション手数料などのインセンティブを与える必要性も排除できる。

=== 供給数量 ===
IOTAの総供給数量は<math>2,779,530,283,277,761</math>枚である。
この数量は三進法の計算に最適化されたもので、[[国際単位系]]としては<math>2.779\times10^{15}</math>として表わされる。
IOTAの総供給数量は、<math>33</math>桁の三進法の数である<math>111,111,111,111,111,111,111,111,111,111,111</math>に基づいていて、十進法の<math>3^{33}</math>に相当するものである。
<math>3^{33}</math>は、IOTAのプラスとマイナスの数値の全領域である。
<math>3^{33}</math>は奇数なので、IOTAの最大の絶対値は<math>(3^{33}-1)/2 = 2,779,530,283,277,761</math>となる。
これが一つのアドレスで所有できるプラスの最大値であり、その結果としてIOTAの総供給数量となっている。

IOTAの総供給数量は約<math>2.8\times10^{15}</math> IOTAであるのに対して、ビットコインの総供給数量は最小単位であるsatoshiで数えると<math>2.1\times10^{15}</math> satoshiなので、似通っているが、ビットコインと異なり、IOTAは小数や分数を使わずに、整数の値のみを処理する。
IOTAを整数単位で取扱うことの利点は、小数の四捨五入問題を回避できることである。
小数の四捨五入問題は、ソフトウェアが適切に設計されていないと、浮動小数点演算の誤差を引き起こす可能性がある。
IOTAは、分割できないトークンを使っているが、総供給数量が多く、トランザクションの処理手数料もかからないので、特に[[マイクロペイメント]]に適している。

発行されている全てのIOTAは、ジェネシス・トランザクション（一番最初のトランザクション）で生成された。
これはタングルのセキュリティを低下させないトークンの発行メカニズムが明らかでなく、セキュリティ面で安全なメカニズムがまだ確証されていないかったからである。

=== 単位===
IOTAの最小単位は、'''IOTA'''である。IOTAはトークン枚数が多いので、桁数に応じて　以下のような表記方によって表示される。
{| class="wikitable"
|-
! 単位 !! トークン枚数
|-
| IOTA (i) || <math>10^0 = 1</math>
|-
| KiloIOTA (Ki) || <math>10^3 = 1,000</math>
|-
| MegaIOTA (Mi) || <math>10^6 = 1,000,000</math>
|-
| GigaIOTA (Gi) || <math>10^9 = 1,000,000,000</math>
|-
| TeraIOTA (Ti) || <math>10^{12} = 1,000,000,000,000</math>
|-
| PetaIOTA (Pi) || <math>10^{15} = 1,000,000,000,000,000</math>
|}
これは1Mega USドルを用いて<math>100</math>万USドルを表すのと同じことである。

===[[暗号理論]]===
IOTAは、[[楕円曲線暗号]]ではなくヴィンテルニッツハッシュベース暗号を用いている<ref name="On the Security of the Winternitz One-Time Signature Scheme">{{cite web |url=https://eprint.iacr.org/2011/191.pdf |title=On the Security of the Winternitz One-Time Signature Scheme |year=2011 |last1=Buchmann |first1=Johannes |last2=Dahmen |first2=Erik |last3=Ereth |first3=Sarah |last4= et. al. |access-date=2019-04-02}}</ref><ref name="Hash Ladders for Shorter Lamport Signatures">{{cite web |url=https://gist.github.com/karlgluck/8412807 |title=Hash Ladders for Shorter Lamport Signatures |year=2014 |last=Gluck |first=Karl |access-date=2019-04-02}}</ref><ref name="Merkle-Winternitz-HORS signature scheme for Tahoe-LAFS">{{cite web |url=https://tahoe-lafs.org/pipermail/tahoe-dev/2010-July/004587.html |title=Merkle-Winternitz-HORS signature scheme for Tahoe-LAFS |year=2010 |last=Hopwood |first=David-Sarah |access-date=2019-04-02}}</ref>。
{{仮リンク|ハッシュベース署名|en|Hash-based cryptography}}は楕円曲線暗号よりはるかに速度が速いだけでなく<ref name="Efficient Hash-Based Signatures on Embedded Devices">{{cite web   |url=https://www-old.cdc.informatik.tu-darmstadt.de/reports/reports/papers/Finished/52_SECSI.pdf |title=Efficient Hash-Based Signatures on Embedded Devices |last1=Rohde |first1=Sebastian |last2=Eisenbarth |first2=Thomas |last3=Dahmen |first3=Erik |last4= et. al. |access-date=2019-04-02}}</ref>、署名と検証作業がかなり簡略化されており、タングルプロトコルの全体的な複雑性が軽減されている。

[[量子コンピュータ]]は、[[グローバーのアルゴリズム]]を活用すると、総当たり攻撃を非常に効率よく実行できるとされている。
ビットコインのブロックを生成するために、暗号学的な[[ノンス|ナンス]]を見つけ出すプロセスは、そのような総当たり攻撃に対して特に脆弱となる。
従来型のコンピュータが解決するためには<math>\Theta(N)</math>回の演算処理を必要とする問題を、量子コンピュータでは<math>\Theta(\sqrt{N})</math>回の演算処理だけで済む。
そのために、量子コンピュータなら、従来型コンピュータより約何百億倍も効率的にビットコインのマイニングができる可能性がある。
このようにビットコイン（や他のブロックチェーンプロトコル）には量子コンピュータに対する脆弱性があることが分かっている。

しかしIOTAでは、トランザクションのハッシュ値を見つけ出すためにチェックすべきナンスの数は<math>3^8</math>だけである<ref name="Tangle"/>。
そのため、IOTAの設定では、量子コンピュータによって向上する効率性は<math>3^4=81</math>倍となるが、これは上述したビットコインの脆弱性に比べたら、取るに足らないほどのものである。
元々、IOTAは設計的に、ナンスを見つけ出すのに掛かる時間が、一つのトランザクションを発行するのに必要な他の諸々の作業に要する時間と比べてもあまり長くないので、そもそもIOTAのセキュリティーと機能性は、量子計算ができる環境の中でも脅かされることはないのである。

== 出典 ==
{{脚注ヘルプ}}
{{Reflist}}

== 関連項目 ==
* [[暗号通貨]]
* [[仮想通貨]]

== 外部リンク ==
* [https://iota.org 公式サイト]
* [https://github.com/iotaledger プロジェクトリポジトリ]

{{暗号通貨}}

{{デフォルトソート:あいおおた}}
[[Category:暗号通貨]]
