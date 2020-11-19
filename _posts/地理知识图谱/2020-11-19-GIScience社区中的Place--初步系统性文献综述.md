---
layout:     post
title:      "地理知识图谱「 13 」"
subtitle:   "GIScience社区中的Place--初步系统性文献综述"
date:       2020-11-19 13:00:00
author:     "西山晴雪"
header-img: "img/post-bg-android.jpg"
categories: Geographic Knowledge Graph
tags:
    - Platial Information
    - 地理空间语义
    - Sematic Web
    - 语义网
    - GeoAI
    - 认知地理
    - 定性推理
---

# GIScience社区中的Place--初步系统性文献综述

## 1 概述

### 1.1 Place在当代的重要性

​			用户生成信息的使用，从正常人的日常视角部分地描述了世界，这在地理信息科学（GIScience）中变得司空见惯。 因此，面向经验和感知空间的place概念（与通常使用的几何概念相反）目前正在流行（Purves等，2019; Westerholt等，2018a）。 但place的概念模糊且难以掌握。 此外，各种学术学科常常通过时间和哲学思潮来制定自己与学科相关的定义和关于place的词汇。 GIScience对place的统一理解尚不存在（Merschdorf和Blaschke，2018）。 然而，基于place的GIS的愿景（Goodchild，2011年）要求对place进行明确定义、形式化，并从主观用户生成数据中提取有意义的信息的方法（Merschdorf和Blaschke，2018年）

### 1.2 当前存在的问题

​		近年也出现了一些使用place或基于place数据的出版物（例如Chen等人，2018; Gao等人，2017; Scheider和Purves，2013; Winter和Freksa，2012）。 而GIScience中许多与place有关的出版物都利用了从人文地理学中借鉴的概念框架，并将其应用于不同的环境。这种概念上的差异表明缺乏共识，这激发了当前研究的主要研究问题：地理科学和相关学者以何种方式利用place概念？

### 1.3 论文采用的研究方法

​		我们通过系统的文献综述来解决这个研究问题。 为了根据确定的语料库回答研究问题，将收集到的所有文章从各个方面进行分解。 也就是说，我们提取了作者在贡献中明智地使用place概念的方式。 这使我们可以得出有关GIS科学学者对place概念及其使用方式的理解的结论。 我们调查此问题的一种方法是查看参考的地理文献。 采取的另一条途径是研究所采用的方法论，因为这些方法可能暗示对作者所使用place的理解。 我们考虑的另一个途径是确定记录中发现的研究目标。 获得的结果清楚地表明了社群如何处理基于place的数据。 他们还提出了未来的方向，以发展明确的GIS科学定义和对place概念的理解。

## 2 关于Place的讨论

​		哲学家和地理学家都对place感兴趣。 术语" place"和" platial"以不同方式和上下文使用-从Aristotle（Drum，2011）到Yi-Fu Tuan（Tuan，1977）到Mike Goodchild（Goodchild，2011）。 古希腊哲学家柏拉图和亚里斯多德可能是最早提出系统place哲学的人。 他们创造了术语" topos"和"chôra"，类似于当代关于space和place的地理概念（Agnew，2011； Casey，1997）。 因此，他们区分了两种含义：一是具有空间（topos）的地理空间，指没有性质的空位置；二是被认为充满意义和身份的空间（chôra）："Place\[\...\]是地球表面的一部分， 不等同于任何其他事物，在不改变一切的情况下不能与其他任何事物交换。 取而代之的是，有了space，每个部分都可以被另一个部分取代，而无需任何改变"（Farinelli，2003，第11页）。 因此，这种二元论具有悠久的传统，至今仍在当代文学中发现。

​		当代有关Place（包括GIS科学领域）的辩论受到1970年代开始的人文地理学论著的强烈影响。 通常分为三个分支：区域地理位置说明、人文地理学思想、激进地理学家的以过程为导向的观点（Cresswell，2014年）。 从那以后出现的一种理解是，空间与位置之间的明晰的二元论不能成立。 Tuan-Fu Tuan是最有影响力的学者之一，他于1977年指出，"当我们越来越了解并赋予其价值时，无差别的space就变成了无处不在的place"（Tuan，1977，p. 6）。 这清楚地表明，在居住space意义上，space的抽象概念和place之间存在内在联系（Soja，2008年）。 GIScience学者们面临着将这些复杂概念综合成一个可以在更多技术背景下被形式化的概念的挑战。

​		任何有关place的数学和计算机方法都需要形式化的输入、标准化和已定义的规则、定义明确的概念和术语（Goodchild，2011年）。Place的另一个组成部分是它对上下文（语境）的依赖。 不同背景的人有不同方式来体验他们的日常地理place。 例如，这体现在以不同语言表达（和表达）place概念的各种方式中（Blaschke et al，2018）。 尽管place是一个异质和模糊的概念，但它也有一个核心共识：所有语言都将space更多地视为容器，而place通常与人类经验和感知的概念交织在一起。 为了有效地开展工作并确保研究方法的可比性，学者们应将重点放在这一共同核心上，该核心可作为将来对GIS科学中地位的透彻了解的基础。

## 3 综述采用的研究方法途径

​		回答问题的方法是系统的文献综述。 因此，我们借鉴了Borrego的指导原则，以便在发展跨学科领域中进行系统的审查（Borrego等，2014）。 此外，我们将作者分为两类：GIScience社区的核心成员和该领域的贡献者。 我们对作者进行分类的方式如下：在论文中明确指出自己是GIS科学家的作者被视为核心成员。 由于这可能太严格了，我们放宽了条件，将那些明确提到由Mike Goodchild提出并由Thomas Blaschke和Helena Merschdorf修订的核心研究议程中某个主题的作者也纳入核心成员(Blaschke and Merschdorf, 2014; Goodchild, 1992, 2010)。 然后，GIScience边缘领域作者，至少处理了该议程中两个主题。此处使用的GISci边缘包括作者，他们至少从该议程中与place讨论了两个主题。 我们期望这只是将社区细分为更精细部分的一种方法。 尽管如此，它仍可以使人们更清楚地了解社区如何处理place问题。 

​		通过对1520篇文献的处理，最终采纳了其中58篇，其中有48篇期刊文章，4篇短论文，4篇会议论文和2篇文献评论。 所有这些记录在1994年至2019年之间发布，其中39个在2009年之后发布，并且每年的发布速度在不断提高。 这一发现支持了以下观点：place概念最近在GIScience社区中变得越来越流行（Purves等，2019; Westerholt等，2018a）。 

​		在机构方面，作者主要来自地理（约占50％）和GIScience /地理信息（约占30％）领域，以及建筑，制图，遥感和历史等其他领域（约占20％）。仔细研究作者发现，托马斯·布拉施克（Thomas Blaschke）参与了三份出版物。 Tim Cole，Song Gao，Alberto Giordano，Helena Merschdorf和Emmanuel Papadakis都参加了两个出版物。 这些是我们资料库中最活跃的作者。 但是，结果中缺少像Ross Purves这样的关键人物。 这表明我们介绍的方法中可能缺少一些重要的关键字。 因此，可以将本简短论文中提出的结果视为对GIScience参与程度进行全面评估构想的推动力。

## 4 研究结果

### 4.1 被采用的地理Place概念

​		资料种共由20种概念被采用，有13种概念使用少于3次，其中9种仅使用一次。 GIScience社区的核心成员似乎使用了更多的概念。 其中，超过57％的概念使用过一次，而贡献者记录中为47％。 运用最广泛的place概念是从Tuan-Fuan Tuan和相关学者提出的对place的现象学理解中得出的。 Tuan（Tuan，1977）的概念被应用了14次，紧随其后的是Agnew（1987）的工作，它被使用了6次；Cresswell的概念（Cresswell，1996）被应用了4次；Curry的概念（Curry，1999）被采用了4次。Lefebvre的社会place概念被引用了2次。

### 4.2 被使用的Place-based数据

​		最常用的数据类型是在线地理标记数据（例如从社交媒体提取的数据；贡献者：22％；核心成员：21％），其次是为调查特定地点而获取的访谈数据（贡献者：24％；核心成员： 没有），从学术文献中识别出的辅助数据（贡献者：11％；核心成员：43％）和传统的GIS数据（例如，行政数据集；贡献者：9％；核心成员：29％）。

### 4.3 被采用的技术方法

​		确定了11种不同的方法论。 在所有记录中大约有超过36％有案例研究（贡献者：36％；核心成员：38％）。 数据探索方法的覆盖率达到19％（贡献者：21％；核心成员：8％），文献回顾和分析方法所占份额约为12％（贡献者：7％；核心成员：31％），调查与place相关数据的方法也比较流行（贡献者：7％；核心成员：23％），社会科学和人文地理研究设计方法（贡献者：9％；核心成员：无 ）。

### 4.4 作者的研究目标

​		总体上可以分为19类。 研究place与人的关系是最经常阐明的目标（n˘15），其次是sense of place分析（n places 9），对place含义的调查（n˘8）。 place可视化（n˘8）。 总体而言，GIScience社区的核心成员重点表现在更多的技术和概念。 相比之下，GIScience贡献者似乎对将Place-based信息和概念应用于相关任务更感兴趣。

## 5 讨论与结论

### 5.1 趋势和模式

#### （1）理论立场

​		 我们语料库中涵盖的大多数GIScience作者并未详细阐述其理论立场。 通常，会引用许多人文地理和哲学方面的作者，但并未详细阐述实际采取的本体论立场，尤其是在基于place的信息方面。 一方面，这表明GIScience作者意识到地理学中可用的一系列概念。观察结果也证明了这一发现，即核心GIS科学社区成员所指的place概念要多于来自该领域边缘的贡献者。另一方面，该观察结果还表明，在许多情况下，place以不明确的方式使用。 显然，有必要对place（在地理意义上）和place-based信息的性质（在GIS科学意义上）进行更透彻的了解，以促进GIS科学领域该领域的有效和富有成果的未来发展。

#### （2）Place概念

​		最常用的place概念是那些从人文地理学借来的概念。 因此，我们发现Tuan-Fu Tuan和John Agnew是被引用次数最多的两位作者，都来自扎根于经验的现象学背景。 同时，人文地理学还关注"place的本质"，即赋予place对人类和人类生存至关重要的核心元素（Cresswell，2014）。 GIScience作者可能更喜欢这种对基础结构的关注，因为信息科学中采用的更为正式的方法更容易与此观点相吻合。 但是，与其他方法（如在描述性区域地理，面向过程的基本地理知识中发现的方法）或更近的关系方法（如在非代表性地理学中的方法）的更深入接触，将有益于基于地点的信息的整体GIS科学概念的发展。

#### （3）研究特点

​		我们进一步发现，探索性在研究设计中很普遍，也证明了Place在GIS科学中尚未达成共识，探索性方法的普遍性似乎非常合理。 因此，也需要基础研究以明确更清晰的场景：从理论上阐明利用placebased信息到底能够用来做什么？ 从该意义上讲，探索性框架使人们能够对复杂问题进行简单研究，这些问题缺乏清晰的共识，这是由于围绕place概念的歧义以及社区打算如何处理这一问题而引起的（Shields and Rangarajan，2013）。 这也与其他重要的研究设计类型（案例研究）保持一致。

#### （4）研究对象

​		在数据方面，在线地理标记信息的可用性日益提高，在一定程度上推动了GIScience研究发展。 在我们的研究结果中，发现所有被考虑的手稿中有22％主要以经验方式处理一种特定类型的数据集。 这些数据集包括社交媒体，还包括带有地理标记的博客以及来自Geoweb的其他项目（Scharl和Tochtermann，2007年）。 认识到该领域的技术性质，可以认为这是一种务实的方法。 现在已经有了新的数据类型，社区似乎正在寻找方法来理解这些提供的新信息。 因此，获得的结果表明GIScience社区在某种程度上以务实的方式对新数据源的可用性做出了响应。 尽管如此，GIScience社区不仅受数据驱动，而且部分受与地理重叠的驱动。 许多地理科学学者正在地理机构中工作，因此与人类地理的同事保持着密切联系。 因此，这可以解释人们对人地关系的浓厚兴趣，包括人的sense of place（与place的物理和其他方面相对），特别是在社区的核心成员之间。 这一发现证实了地理信息科学与人文地理学者之间存在着某种智力上的共同点。

### （5）总结

-  GIScience社区当前似乎专注于人文地理方法，但可能会受益于对place地理方法的包容和更广泛的考虑；

- 结果表明，社区非常看重可用数据集，因此采取了非常务实的观点。 独立于特定数据形式的更多概念性工作可能对该领域的未来发展有利。 在这个方向上已经有一些有希望的作品（例如，Scheider和Janowicz，2014； Winter和Freksa，2012）；

- 3.审查结果表明，GIScience核心成员与其边缘贡献者之间对Place的理解存在偏差，从而导致行为发生偏差。 因此，核心成员所做的工作在本质上似乎更具概念性。 这是有希望的，因为它表明社区的核心成员似乎专注于开发处理place-based信息的新颖概念，而相关的经验学者则通过应用这些观点得到了另外一些有价值的观点。

  

### 注：据我们所知，Casey（1993）首次使用了形容词platial

## 6 参考文献

- Agnew, John A: Place and politics. Winchester, MA, USA: Allen and Unwin, 1987  —— Space and place. In: Agnew, John and Livingstone, David N (eds.), The SAGE Handbook of Geographical Knowledge, London, UK: SAGE, 2011, vol. 2011. 316–331
- Blaschke, Thomas and Merschdorf, Helena: Geographic information science as a multidisciplinary
  and multiparadigmatic field. Cartography and Geographic Information Science, 41(3), 2014, 196–213.doi: 10.1080/15230406.2014.905755
- Blaschke, Thomas; Merschdorf, Helena; Cabrera-Barona, Pablo; et al.: Place versus space: from
  points, lines and polygons in GIS to place-based representations reflecting language and culture. ISPRS International Journal of Geo-Information, 7(11), 2018, 452. doi: 10.3390/ijgi7110452
- Borrego, Maura; Foster, Margaret J; and Froyd, Jeffrey E: Systematic literature reviews in engineering education and other developing interdisciplinary fields. Journal of Engineering Education, 103(1),2014, 45–76. doi: 10.1002/jee.20038
- Casey, Edward: The fate of place: a philosophical history, 1997
- Casey, Edward S: Getting back into place: toward a renewed understanding of the place-world. Bloomington, IN, USA: Indiana University Press, 1993
- Chen, Hao; Winter, Stephan; and Vasardani, Maria: Georeferencing places from collective human
  descriptions using place graphs. Journal of Spatial Information Science, 2018(17), 2018, 31–62. doi:10.5311/JOSIS.2018.17.417
- Cresswell, Tim: In place/out of place: geography, ideology, and transgression. Minneapolis, MN, USA:University of Minnesota Press, 1996—— Place. An introduction. Hoboken, NJ, USA: Wiley and Sons, 2014
- Curry, Michael R: “Hereness” and the normativity of place. In: Proctor, James D and Smith, David M
  (eds.), Geography and Ethics, London, UK: Routledge, 1999. 95–105
- Davies, Clare: Place and placing locations: a cognitive perspective. In: Westerholt, Rene; Mocnik,
  Franz-Benjamin; and Zipf, Alexander (eds.), Proceedings of the 1st Workshop on Platial Analysis
  (PLATIAL’18). 2018, 15–20. doi: 10.5281/zenodo.1472737
- Drum, Peter: Aristotle’s definition of place and of matter. Open Journal of Philosophy, 1(1), 2011, 35–36.doi: 10.4236/ojpp.2011.11006
- Farinelli, Franco: Geografia: un’introduzione ai modelli del mondo. Turin: Einaudi, 2003
- Gao, Song; Janowicz, Krzysztof; Montello, Daniel R; et al.: A data-synthesis-driven method for detecting and extracting vague cognitive regions. International Journal of Geographical Information Science, 31(6), 2017, 1245–1271. doi: 10.1080/13658816.2016.1273357
- Goodchild, Michael F: Geographical information science. International Journal of Geographical
  Information Systems, 6(1), 1992, 31–45. doi: 10.1080/02693799208901893
- —— Twenty years of progress: Giscience in 2010. Journal of Spatial Information Science, 2010(1), 2010,3–20. doi: 10.5311/JOSIS.2010.1.2
- —— Formalizing place in geographic information systems. In: Burton, Linda M; Matthews, Stephen A; Leung, ManChui; Kemp, Susan P; and Takeuchi, David T (eds.), Communities, neighborhoods, and health, New York, NY, USA: Springer, 2011. 21–33. doi: 10.1007/978-1-4419-7482-2_2
- Lefebvre, Henri and Nicholson-Smith, Donald: The production of space. Chichester, UK: Wiley, 1992
- Merschdorf, Helena and Blaschke, Thomas: Revisiting the role of place in geographic information
  science. ISPRS International Journal of Geo-Information, 7(9), 2018, 364. doi: 10.3390/ijgi7090364
- Purves, Ross S; Winter, Stephan; and Kuhn, Werner: Places in information science. Journal of the
  Association for Information Science and Technology, 70(11), 2019. doi: 10.1002/asi.24194  
- Scharl, Arno and Tochtermann, Klaus: The geospatial Web. London, UK: Springer, 2007
- Scheider, Simon and Janowicz, Krisztof: Place reference systems. A constructive activity model of
  reference to places. Applied Ontology, 9(2), 2014, 97–127. doi: 10.3233/AO-140134
- Scheider, Simon and Purves, Ross: Semantic place localization from narratives. Proceedings of the
  1st ACM SIGSPATIAL International Workshop on Computational Models of Place (COMP), 2013. doi:10.1145/2534848.2534858
- Shields, Patricia M and Rangarajan, Nandhini: A playbook for research methods: integrating conceptual frameworks and project management. Stillwater, OK, USA: New Forums Press, 2013
- Soja, Edward W: Thirdspace: toward a new consciousness of space and spatiality. In: Ikas, Karin and Wagner, Gerhard (eds.), Communicating in the Third Space, New York, NY, USA: Routledge, 2008.63–75
- Tuan, Yi-Fu: Space and place. The perspective of experience. Minneapolis, MN, USA: University of
  Minnesota Press, 1977
- Westerholt, Rene; Gröbe, Mathias; Zipf, Alexander; and Burghardt, Dirk: Towards the statistical
  analysis and visualization of places. Proceedings of the 10th International Conference on Geographic Information Science (GIScience), 2018a. doi: 10.4230/LIPIcs.GISCIENCE.2018.63
- Westerholt, Rene; Mocnik, Franz-Benjamin; and Zipf, Alexander: Introduction to the PLATIAL’18
  workshop on platial analysis. In: Westerholt, Rene; Mocnik, Franz-Benjamin; and Zipf, Alexander
  (eds.), Proceedings of the 1st Workshop on Platial Analysis (PLATIAL’18). 2018b, 1–5. doi: 10.5281/zenodo.1475267
- Winter, Stephan and Freksa, Christian: Approaching the notion of place by contrast. Journal of Spatial Information Science, 5, 2012, 31–50. doi: 10.5311/JOSIS.2012.5.90  