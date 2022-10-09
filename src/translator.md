# 역자 노트 Translator's note

이 웹페이지는 [발라지 스리니바산(Balaji Srinivasan)](https://twitter.com/balajis?s=20&t=uPn_tyjwWfkas3DUSMFhiw)의 책 [<네트워크 국가 The Network State>](https://thenetworkstate.com)를 한국어로 번역하기 위해 만들어졌습니다.
이 북앱은 mdbook을 사용하여 제작되었습니다. 상단 좌측 메뉴들을 통해 다크모드 선택, 검색, 목차 탐색이 가능합니다. 상단 우측의 인쇄버튼을 이용해 종이에 인쇄하실 수도 있습니다.
원문은 [thenetworkstate.com](https://thenetworkstate.com)에서 무료로 읽으실 수 있습니다. 킨들로 오프라인에서도 읽고 싶으신 경우에는 [아마존](https://www.amazon.com/Network-State-How-Start-Country-ebook/dp/B09VPKZR3G/ref=sr_1_1?crid=1RJVMERI7OEPS&keywords=network+state&qid=1659386978&sprefix=network+state%2Caps%2C164&sr=8-1)에서 킨들 버전을 구입하실 수 있습니다.

가급적 원문에 가깝게 번역하려고 했으나, 직역이 곤란하거나 한국어 문장이 난잡해지는 경우 의역과 문장 재배열을 자유롭게 사용했습니다. 원문 자체가 지속적으로 업데이트 되기 때문에 번역본과 불일치가 생길 수 있으니 번역에 의문이 생길 경우 원문을 참고해 주세요.
번역자에게 생업이 따로 있기 때문에 첫 챕터  "Quickstart" 이후의 번역은 천천히 진행될 예정입니다.

비영리적 용도로 자유롭게 이용하실 때에는 [원저자(Balaji Srinivasan)](https://twitter.com/balajis?s=20&t=uPn_tyjwWfkas3DUSMFhiw)와 [번역자(nstate.eth)](https://twitter.com/nstate_eth?s=20&t=uPn_tyjwWfkas3DUSMFhiw)를 명시해주세요.

사토시 나카모토가 비트코인이라는 신대륙에 상륙하면서 새로운 프론티어가 다시 열렸습니다. 이제 쇠퇴하는 구대륙을 벗어나 새로운 마을, 새로운 도시, 새로운 문명을 건설할 기회가, 그리고 마침내는 신대륙에서 축적한 역량으로 구대륙마저도 새롭게 부활시킬 수 있는 기회가 눈앞에 펼쳐져 있습니다.

한국어 화자들, 특히 대한민국의 젊은 청년들이 쇠락하는 구대륙에서 우울과 비관에 빠져 사냥꾼이 아닌 사냥감으로서 무기력한 삶을 살아가거나, 또는 침몰하는 배에서 제로섬 게임에 몰두하는 모습을 보면 가슴이 답답하고 울화가 치밉니다. 그 우울한 광경은 항상 제 가슴을 바위처럼 무겁게 짓누릅니다. 바다 건너에 깃발만 꽂으면 내것이 되는 빈 땅이 널려있고, 그 빈 땅에서 모은 힘으로 다시 구대륙을 폭력 없이 정복할 수 있는데 말이죠.

제가 비트코인과 크립토가 보여주는 비전에 매혹되어 개종한 까닭은, 이 거대한 물결이 클라우드 위의 디지털 공간, 소위 메타버스에 멈추지 않을것이라는 확신 때문이었습니다. 이 물결은 디지털 공간으로부터 흘러 넘쳐, 결국 현재 점점 경화되어 가라앉는 물리적 세계를 휩쓸고, 다시 폭력 없이 정복하고, 마침내 새로운 생명을 줄 것입니다.
기존의 대기업이 비대하고 노쇠해져서 내부로부터의 개혁이 무의미해지고 새로운 환경에 적응하지 못할 때, 스타트업이 태어나 수명을 다한 기업들을 잡아먹고 세상을 다시 정복해야 합니다. 그렇다면 기존의 도시와 국가가 비대하고 노쇠해져서 내부로부터의 개혁이 무의미해졌을때는 무엇을 해야 할까요? 마찬가지로 우리는 스타트업 도시를 세우고 스타트업 국가를 세워서 세상을 새롭게 정복해야 합니다. 그리고 비트코인과 크립토가 이것을 기술적으로 훨씬 용이하게 해줍니다.

물론 이렇게 다시 열린 '와일드 웨스트'에서 '와일드'의 함의를 무시할 수는 없습니다. 빈 땅에 들짐승과 무법자들이 횡행하고, 황무지에는 홍수와 가뭄이 연달아 들이칩니다. 하지만 이 모든것들이 정복자의 군홧발 아래 결국은 복종하게 될 것이고, 한국어 화자들도 와일드 웨스트를 정복하러가는 개척자들의 행렬에 뒤쳐져서는 안됩니다. 아직도 대한민국, 더 나아가 한국어 공동체에 희망이 있다면, 가슴 깊이 불꽃이 살아 있는 청년들이 분명히 있을 것입니다. 모든 기회들이 사라지고 노인들만이 지배하는 쇠락하는 도시를 떠나, 이 폭력 없는 정복 전쟁에 뛰어들어 창업 군주가 되기를 열망하는 청년들이 말이죠. 그들이 알아야 할 것은 단지 (1) 프론티어가 다시 열렸고, (2) 그 프론티어 위에 새로운 도시와 국가를 세울 수 있고, (3) 나아가 그 프론티어에서 얻은 힘으로 노쇠한 옛 대륙을 다시 정복하고 부활시키는 것이 가능하다는 것입니다. 그래서 어떻게 해야 더 많은 한국어 화자들에게 이 복된 소식을 전할 수 있을까 고민하던 중, 이 책의 출판소식을 접하게 되었습니다. 다시 열린 프론티어에 대한 상상과 영감을 불러일으키는데 이보다 더 나은 책이 없다고 저는 판단했고, 이 책을 개인적으로라도 번역해서 핵심 아이디어들이 요약된 첫 챕터만이라도 한국어 웹에 신속하게 공급해야겠다는 결심을 하게 되었습니다. 

이 책의 모든 내용에 동의할 필요도 없고, 이 책을 마치 미래를 예견하는 예언서로 읽을 필요도 전혀 없습니다. 번역자인 저 자신도 그런식으로 이 책을 읽지 않으며, 저자의 모든 의견에 동의하지도 않습니다. 오히려 저자 스스로가 말하듯이, 이 책을 하나의 유용한 도구상자로 활용하는 것이 보다 적절한 방식일 것입니다. 인류가 처음 만난 이 신대륙에서, 무엇이 어디까지 가능할지는 아직 누구도 완전히 알지 못합니다. 이 책은 그 정복과 탐험의 여정에 도움이 되는 많은 영감과 아이디어, 그리고 여러가지 유용한 도구들을 제공해줄 수 있을 것입니다. 

이제 우리의 문명을 녹슬고 좀먹게 했던 오랜 망각에서 벗어나서, 우리가 누구인지 다시 기억을 되살릴 때가 되었습니다. 짧은 역자 노트를 마무리하며, 사람들의 기억에서 오랫동안 사라졌던 임무 명령서의 먼지를 털어내고 다시 한번 복명복창 해봅니다:

"하나님이 그들에게 복을 주시며 그들에게 이르시되 생육하고 번성하여 땅에 충만하라, 땅을 정복하라" 
(창세기 1:28, 개역한글)


______________________


This webpage was created to translate [Balaji Srinivasan](https://twitter.com/balajis?s=20&t=uPn_tyjwWfkas3DUSMFhiw)'s book , ["The Network State"](https://thenetworkstate.com/), into Korean. This bookapp is built using mdbook. You can select dark mode, search, and browse the book using the bottons on the top left. You can also print it using the botton on the top right. The original text is freely available at [thenetworkstate.com](thenetworkstate.com). If you want to read the original text on your Kindle, you can purchase the Kindle version of it on [Amazon](https://www.amazon.com/Network-State-How-Start-Country-ebook/dp/B09VPKZR3G/ref=sr_1_1?crid=1RJVMERI7OEPS&keywords=network+state&qid=1659386978&sprefix=network+state%2Caps%2C164&sr=8-1).

I tried to translate it as close to the original text as possible. Wherever it is difficult to translate it word-for-word or the literal translation of it gets ugly, however, I freely used paraphrasing and sentence rearrangement in Korean sentences. Because the original text itself is constantly updated, there might be discrepancies with the translation. Please refer to the original text if you have any doubt about the translation. The translation after the first chapter "Quickstart" will proceed rather slowly because I have a separate job.

Please mention [the original author (Balaji Srinivasan)](https://twitter.com/balajis?s=20&t=uPn_tyjwWfkas3DUSMFhiw) and [the translator (nstate.eth)](https://twitter.com/nstate_eth?s=20&t=uPn_tyjwWfkas3DUSMFhiw) when you use it freely for non-profit purposes.

A new frontier was reopened when Satoshi Nakamoto landed on a new continent called Bitcoin. The opportunity to break free from the declining old continent, to build new towns, new cities, and new civilizations, and eventually to revive even the old continent again with the capabilities accumulated in the new continent, is now unfolding before our own eyes.

It is deeply frustrating to see Korean speakers, especially young Koreans in South Korea, living a powerless life as a prey rather than a hunter, falling into depression and pessimism in the declining old continent, or immersing themselves in zero-sum games on the sinking ship. It is heartbreaking and painful to watch and this gloomy sight always weighs heavily on my chest like a rock. It is because there is an empty land across the sea, which they can just plant a flag on and make theirs, then they can conquer the old continent again with the power gathered from the new world, without violence.

The reason I was fascinated and converted by the vision of Bitcoin and crypto was the conviction that this huge wave would not stop at the digital space on the cloud alone, the so-called metaverse. This wave will overflow from the digital space, sweeping, re-conquering without violence, and eventually giving a new life to the now increasingly ossifying and declining physical world. When existing large corporations become bloated and senile and internal reforms become meaningless, startups must be born, eat dead companies, and conquer the world anew. What should we do, then, when existing cities and countries become bloated and senile and internal refoms become meaningless? We should likewise establish startup cities and countries, and conquer the world anew. And Bitcoin and crypto make it technically much easier. 

Of course, we cannot ignore the implications of the word 'wild' in this re-opened 'Wild West'. Wild beasts and outlaws prowl about the wasteland, and floods and droughts strike the wilderness one after another. But all of them will eventually become a footstool for the conquerors' feet and obey them, and the Korean speakers should not be left behind the caravan of pioneers, heading toward the Wild West. If there is still any hope in South Korea, or even the Korean-speaking community, there must be young people with a burning flame deep inside their hearts: young people who aspire to leave a withering city where all the opportunities are gone and only the elderly rule, and to jump into this non-violent war of conquest and become
founding monarchs. All they need to know is that (1) the Frontier is reopened, (2) it is possible to build new cities and countries on it, and furthermore (3) it is possible to conquer and resurrect the old world with the capabilities you get from that frontier. So while I was thinking about how to spread this good news to more Korean speakers, I came across the news of the publication of this book. I concluded that there is no better book to kindle imagination and inspiration for this frontier than this one. I decided to personally translate this book, at least the first chapter which summarizes the key ideas, and bring it quickly to the Korean web.  

You don't have to agree with everything in this book, and you don't need to read it as a prophecy for the future. Even as a translator, I myself do not read this book in that way, and I don't agree with every single claim the author made. Rather, as the author himself says, it would be more appropriate to use this book as a useful toolbox. In this new continent humankin encountered only recently, no one fully knows what will be possible to what extent. This book will provide you with many inspirations, ideas, and useful tools to help you on your journey of conquest and exploration.

Now the time has come for us to wake up from the old oblivion that has rusted and corroded our civilization, and to rekindle our memories of who we are. Wrapping up this short note, I dust off the long-lost mission orders, and recite it once again:

"And God blessed them. And God said to them, "Be fruitful and multiply and fill the earth and subdue it"" 
(Genesis 1:28, ESV)