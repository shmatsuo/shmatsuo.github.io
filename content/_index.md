---
title: 'Home'
date: 2023-10-24
type: landing

sections:
  - block: hero
    content:
      title: Theory Meets Blockchain Engineering (TMBE)<br> <font size="4">エンジニアが作るブロックチェーンの安全性を暗号研究者と共に理論的に高める合宿</font>
      text: 2024年 1月26日 - 1月27日　場所：[Solidity House](https://www.solidityhouse.com)（佐賀県嬉野市）
      primary_action:
        text: 
        url: 
        icon: 
      secondary_action:
        text: 
        url: 
      announcement:
        text: 
        link:
          text: 
          url: 
    design:
      css_class: dark
      background:
        image:
          # Add your image background to `assets/media/`.
          filename: DSCF7310_edited.jpg
          filters:
            brightness: 0.5
  - block: markdown
    content:
      title: 日時・場所
      subtitle: 
      text: <b>日時：</b><br>2024年1月26日 15:30-18:00<br>2024年1月27日　9:00 - 16:30<br>（時間は現時点での予定）<br><b>場所：</b>Solidity House <a href="https://www.solidityhouse.com">リンク</a>（佐賀県嬉野市）<br><iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d428267.18979809934!2d129.6834732496871!3d33.00806153421156!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x354025f9a20089c9%3A0xde8c5ff6fac19a05!2sTei-4021%20Shiotach%C5%8D%20%C5%8Caza%20Kuma%2C%20Ureshino%2C%20Saga%20849-1404%2C%20Japan!5e0!3m2!1sen!2sus!4v1702522483183!5m2!1sen!2sus" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
  - block: markdown
    content:
      title: 背景と目的
      subtitle: 
      text: 2008年のSatoshi Nakamotoを著者とするBitcoinの未査読の論文の発表以降、ブロックチェーン技術は現代暗号理論の有益な応用として、Bitcoinのような支払い手段のみならず、多くの実用化の試みがなされている。この実用化の主役はいわゆるブロックチェーンエンジニアと呼ばれる人たちである。<br>一方で、Bitcoin論文が未査読であると書いたように、現代暗号理論が「証明可能安全性」のフレームワークで構築されてきたにもかかわらず、多くのブロックチェーンやその周辺のプロトコルは、安全性の証明や検証がなされないまま、数千億円以上の価値を支える状況になっている。その結果として、ブロックチェーンエンジニアも、ブロックチェーン企業も、現実のシステム上のリスクを算定できない状況のまま、巨額のセキュリティインシデントが毎日のように発生している。<br>せっかく暗号研究者が証明可能安全性を有する暗号技術を部品として提供していながら、その利用方法について正しい理解がなされていないことがその主要な原因であり、一方で暗号研究者がブロックチェーン技術者が未来に向けて構築しようとしているものへのキャッチアップが不十分であるため、安全性の研究対象としての漏れが発生しているといえる。<br>本合宿は、このような暗号研究者とブロックチェーンエンジニアの間の知識の断絶を解消するための第一歩として、暗号研究者からは暗号技術の理論的背景や暗号技術の部品（これには、ハッシュ関数や電子署名だけでなく、ゼロ知識証明やマルチパーティ計算を含む）の安全性の理論や想定される使い方（あるいはしてはいけない使い方）の知見を、ブロックチェーンエンジニアからはブロックチェーンの世界で構築しようとしてる新たなシステムや技術のプランを、お互いに共有し、<b>「安全なブロックチェーンのシステムをつくる」</b>という、スケーラビリティを犠牲にしても最低限守らなければいけない最低目標を達成する方法を、議論と共同作業の形で追求することを目的とする。<br><br><br>本合宿の参加者は、直前に長崎で行われる、<a href="https://www.iwsec.org/scis/2024/">電子情報通信学会 暗号と情報セキュリティシンポジウム（SCIS2024）</a> に参加する暗号研究者・ブロックチェーン研究者（アカデミア）と、ブロックチェーンエンジニアによって構成される。
  - block: features
    id: features
    content:
      title: 合宿で得られるもの
      text: 
      items:
        - name: 暗号技術の安全性理論
          icon: magnifying-glass
          description: 改めてブロックチェーン技術に使われている暗号技術の部品に関する安全性の考え方を確認する
        - name: 暗号プロトコルの安全性の知見
          icon: bolt
          description: ブロックチェーンプロトコルの他、ゼロ知識証明やマルチパーティ計算などの安全性の考え方を確認する
        - name: ブロックチェーンアプリの安全性の検証
          icon: sparkles
          description: 現在エンジニアが取り組んでいる技術開発について、暗号研究者の視点からの指摘を得る
        - name: ブロックチェーンのエンジニアリング上の課題の共有
          icon: code-bracket
          description: ブロックチェーンエンジニアが日常において技術の設計や実装において直面している課題やセキュリティ上の疑問の共有と解決
        - name: ブロックチェーンエンジニアの技術ロードマップに対する議論
          icon: star
          description: 現在考えられている技術ロードマップについて、暗号研究者から見たときに過不足、問題点などの指摘やアドバイスを行う
        - name: 暗号研究者とブロックチェーンエンジニアの今後の連携の模索
          icon: rectangle-group
          description: これまで断絶していた暗号研究者とブロックチェーンエンジニアが、安全なブロックチェーン技術の確立に向けての連携のあり方を議論する
  - block: markdown
    content:
      title: フォーマット、およびプログラム
      subtitle: 
      text: 決定次第お知らせします
  - block: markdown
    content:
      title: 参加者
      subtitle: 
      text: 本合宿は、暗号研究者と、理論的背景を交えた議論を行いたいブロックチェーンエンジニアによる、相互の貢献を求める形で行います。そのため、すべての議論の質を担保するために人数の制限を行います。具体的には、上限が25名で、おおむね暗号研究者が15名、エンジニアが10名で構成することを予定しています。<br>エンジニア枠での参加者は、必ずしも暗号理論に関しての深い知識を備えていることを条件とはしませんが、現状取り組んでいるブロックチェーンのプロジェクトや研究において、実際に安全に技術を確立する上で困っている点を共有し、合宿参加者でその解決の筋道を見いだす議論に積極的に参加することを基本とします。<br><b>Update：<br>- エンジニア枠の当初予定の枠（10人）は埋まりました。これからエンジニア枠で応募される方は、枠に余裕ができた時（エンジニア枠の拡大、あるいはキャンセルの発生）のためのWaiting Listの中に入ることをご了承ください。<br>- 暗号研究者、ブロックチェーン研究者（アカデミア）枠に、「暗号の安全性証明などの知識を有し、SCIS、CSS、査読付きのジャーナル・カンファレンスで論文などを発表している人」の注釈をつけました。証明可能安全性の理論からの議論ができる人を前提にしています。</b>
  - block: cta-image-paragraph
    id: solutions
    content:
      items:
        - title: 参加申し込み
          text: 参加の申し込みはGoogle Formsからお願いします。参加費用は3,000円で、参加費用には宿泊費用などは含まれません。支払い方法については、参加申し込みをされた方に別途お知らせいたします。
          # Upload image to `assets/media/` and reference the filename here
          image: 336654917_730785965501098_6903692826250572592_n-3.jpg
          button:
            text: 参加申し込み
            url: https://docs.google.com/forms/d/e/1FAIpQLSelu4AoiYNwbics56v_ytUx-vNsDTh5QwKiHItjnuwMnxBPCg/viewform
#        - title: Large Community
#          text: Join our large community - ask questions and share your Hugo knowledge with others.
#          # Upload image to `assets/media/` and reference the filename here
#          image: coffee.jpg
#          button:
#            text: Join Discord
#            url: https://discord.gg/z8wNYzb
#  - block: cta-card
#    content:
#      title: Build your future-proof website
#      text: As easy as 1, 2, 3!
#      button:
#        text: Get Started
#        url: https://hugoblox.com/templates/
---
