搜索引擎的技术架构
==================

## 1. 搜索引擎的分类
搜索引擎按其工作方式主要可分为三种：

> 1. 分别是全文搜索引擎（Full Text Search Engine）

> 2. 目录索引类搜索引擎（Search Index/Directory）

> 3. 元搜索引擎（Meta Search Engine）。 

## ■ 全文搜索引擎
&emsp;&emsp;全文搜索引擎是名副其实的搜索引擎，国外具代表性的有Google、Fast/AllTheWeb、AltaVista、Inktomi、Teoma、WiseNut等，国内著名的有百度（Baidu）。它们都是通过从互联网上提取的各个网站的信息（以网页文字为主）而建立的数据库中，检索与用户查询条件匹配的相关记录，然后按一定的排列顺序将结果返回给用户，因此他们是真正的搜索引擎。     
  
&emsp;&emsp;从搜索结果来源的角度，全文搜索引擎又可细分为两种，一种是拥有自己的检索程序（Indexer），俗称“蜘蛛”（Spider）程序或“机器人”（Robot）程序，并自建网页数据库，搜索结果直接从自身的数据库中调用，如上面提到的7家引擎；另一种则是租用其他引擎的数据库，并按自定的格式排列搜索结果，如Lycos引擎。     
  
&emsp;&emsp;在搜索引擎分类部分提到过全文搜索引擎从网站提取信息建立网页数据库的概念。搜索引擎的自动信息搜集功能分两种。一种是定期搜索，即每隔一段时间（比如Google一般是28天），  蜘蛛搜索引擎搜索引擎主动派出“蜘蛛”程序，对一定IP地址范围内的互联网站进行检索，一旦发现新的网站，它会自动提取网站的信息和网址加入自己的数据库。另一种是提交网站搜索，即网站拥有者主动向搜索引擎提交网址，它在一定时间内（2天到数月不等）定向向你的网站派出“蜘蛛”程序，扫描你的网站并将有关信息存入数据库，以备用户查询。由于近年来搜索引擎索引规则发生很大变化，主动提交网址并不保证你的网站能进入搜索引擎数据库，目前最好的办法是多获得一些外部链接，让搜索引擎有更多机会找到你并自动将你的网站收录。      
      
&emsp;&emsp;当用户以关键词查找信息时，搜索引擎会在数据库中进行搜寻，如果找到与用户要求内容相符的网站，便采用特殊的算法——通常根据网页中关键词的匹配程度、出现的位置、频次、链接质量——计算出各网页的相关度及排名等级，然后根据关联度高低，按顺序将这些网页链接返回给用户。这种引擎的特点是搜全率比较高。      
  
## ■ 目录索引
&emsp;&emsp;虽然有搜索功能，但严格意义上不能称为真正的搜索引擎，只是按目录分类的网站链接列表而已。（更简单说就是网址导航网站）

&emsp;&emsp;用户完全可以按照分类目录找到所需要的信息，不依靠关键词（Keywords）进行查询。目录索引中最具代表性的莫过于大名鼎鼎的Yahoo、新浪分类目录搜索。    
       
&emsp;&emsp;与全文搜索引擎相比，目录索引有许多不同之处。      
  
&emsp;&emsp;首先，搜索引擎属于自动网站检索，而目录索引则完全依赖手工操作。用户提交网站后，目录编辑人员会亲自浏览你的网站，然后根据一套自定的评判标准甚至编辑人员的主观印象，决定是否接纳你的网站。  目录索引其次，搜索引擎收录网站时，只要网站本身没有违反有关的规则，一般都能登录成功。而目录索引对网站的要求则高得多，有时即使登录多次也不一定成功。尤其象Yahoo这样的超级索引，登录更是困难。
  
&emsp;&emsp;此外，在登录搜索引擎时，我们一般不用考虑网站的分类问题，而登录目录索引时则必须将网站放在一个最合适的目录（Directory）。
  
&emsp;&emsp;最后，搜索引擎中各网站的有关信息都是从用户网页中自动提取的，所以用户的角度看，我们拥有更多的自主权；而目录索引则要求必须手工另外填写网站信息，而且还有各种各样的限制。更有甚者，如果工作人员认为你提交网站的目录、网站信息不合适，他可以随时对其进行调整，当然事先是不会和你商量的。
  
&emsp;&emsp;目录索引，顾名思义就是将网站分门别类地存放在相应的目录中，因此用户在查询信息时，可选择关键词搜索，也可按分类目录逐层查找。如以关键词搜索，返回的结果跟搜索引擎一样，也是根据信息关联程度排列网站，只不过其中人为因素要多一些。如果按分层目录查找，某一目录中网站的排名则是由标题字母的先后顺序决定（也有例外）。
  
&emsp;&emsp;目前，搜索引擎与目录索引有相互融合渗透的趋势。原来一些纯粹的全文搜索引擎现在也提供目录搜索，如Google就借用Open Directory目录提供分类查询。而象 Yahoo! 这些老牌目录索引则通过与Google等搜索引擎合作扩大搜索范围（注）。在默认搜索模式下，一些目录类搜索引擎首先返回的是自己目录中匹配的网站，如中国的搜狐、新浪、网易等；而另外一些则默认的是网页搜索，如Yahoo。这种引擎的特点是找的准确率比较高。

## ■ 元搜索引擎 (META Search Engine)

&emsp;&emsp;元搜索引擎在接受用户查询请求时，同时在其他多个引擎上进行搜索，并将结果返回给用户。著名的元搜索引擎有InfoSpace、Dogpile、Vivisimo等（元搜索引擎列表），中文元搜索引擎中具代表性的有搜星搜索引擎。在搜索结果排列方面，有的直接按来源引擎排列搜索结果，如Dogpile，有的则按自定的规则将结果重新排列组合，如Vivisimo。


除上述三大类引擎外，还有以下几种非主流形式：

> 1. 垂直搜索引擎     
>　　垂直搜索引擎为2006年后逐步兴起的一类搜索引擎。不同于通用的网页搜索引擎，垂直搜索专注于特定的搜索领域和搜索需求（例如：机票搜索、旅游搜索、生活搜索、小说搜索、视频搜索等等），如国内的酷讯，去哪儿，携程等。在其特定的搜索领域有更好的用户体验。相比通用搜索动辄数千台检索服务器，垂直搜索需要的硬件成本低、用户需求特定、查询的方式多样。
> 2. 集合式搜索引擎     
>　　集合式搜索引擎：该搜索引擎类似元搜索引擎，区别在于它并非同时调用多个搜索引擎进行搜索，而是由用户从提供的若干搜索引擎中选择，如HotBot在2002年底推出的搜索引擎。
> 3. 门户搜索引擎     
>　　门户搜索引擎：AOLSearch、MSNSearch等虽然提供搜索服务，但自身既没有分类目录也没有网页数据库，其搜索结果完全来自其他搜索引擎。
> 4. 免费链接列表         
>　　免费链接列表（Free For All Links简称FFA）：一般只简单地滚动链接条目，少部分有简单的分类目录，不过规模要比Yahoo！等目录索引小很多。


## 2. 搜索引擎的技术架构 
&emsp;&emsp;优秀的搜索引擎需要复杂的架构和算法，以 此来支撑对海量数据的获取、存储，以及对用户查询的快速而准确地响应。

&emsp;&emsp;从架构层面，搜索引擎需要能够对以百亿计的海量网页进行获取、存储、处理的能力，同 时要保证搜索结果的质量。

&emsp;&emsp;如何获取、存储并计算如此海量的数据？

&emsp;&emsp;如何快速响应用户的査 询？

&emsp;&emsp;如何使得搜索结果能够满足用户的信息需求？

&emsp;&emsp;这些都是搜索引擎面对的技术挑战。 下图是一个通用的搜索引笨架构示意图：



![img_01](https://github.com/lifezq/notebook/blob/master/imgs/search_engine/687474703a.jpeg)      

<center  style="color:red;text-align:center;">搜索引擎架构</center>



&emsp;&emsp;搜索引擎由很多技术模块构成，各自负责整体 功能的一部分，相互紀合形成了完善的整体架构。

### 抓取网页:
&emsp;&emsp;搜索引擎的信息源来自于互联网网页，通过网络爬虫将互联网的信息获取到本地. 因 为互联网页面中有相当大比例的内容是完全相同或者近似重复的，"网页去重"模块会对此做 出检測，并去除重复内容。

### 建立索引：

&emsp;&emsp;抓取到网页后，搜索引擎会对网页进行解析，抽取出网页主体内容和相关信息，（包括网页所在URL、编码类型、页面内容包含的关键词、关键词位置、生成时间、大小、与其它网页的链接关系等）。根据一定的相关度算法进行大量复杂计算，得到每一个网页针对页面内容中及超链中每一个关键词的相关度（或重要性），然后用这些相关信息建立网页建立索引。为了加快响应用户査询的速度，网页内容通过"倒排索引"这种高效查询数据 结构来保存，而网页之间的链接关系也会予以保存。之所以要保存链接关系，是因为这种关系 在网F相关性排序阶段是可利用的，通过"链接分析"可以判断页面的相对重要性，对于为用 户提供准确的搜索结果帮助很大。

&emsp;&emsp;由于网页数量太多，搜索引擎不仅需要保存网页原始信息，还要存储一些中间的处理结果 使用单台或者少量的机器明显是不现实的。Google等商业搜索引擎为此开发了一整套云存储与 云计算平台，使用数以万计的普通廉价PC搭建了海量信息的可靠存储与计算架构，以此作为搜索 引擎及其相关应用的基础支撑。优秀的云存储与云计算平台已经成为大型商业搜索引擎的核心 竞争力。 上面所述是搜索引擎如何获取并存储海量的网页相关信息，这些功能因为不需要实时计 算，所以可以被看做是搜索弓I擎的后台计算系统。

### 查询词分析

&emsp;&emsp;搜索引擎的最重要目的是为用户提供准确全 面的搜索结果，如何响应用户査询并实时地提供准确结果构成了搜索引擎前台计算系统。 当搜索引擎接收到用户的査询词后，首先需要对查询词进行分析，希望能够结合查询词和 用户信息来正确推导用户的真正搜索意图。在此之后，首先在缓存中査找，搜索引擎的缓存系 统存储了不同的查询意图对应的搜索结果，如果能够在缓存系统找到满足用户需求的信息，则 可以直接将搜索结果返回给用户，这样既省掉了重复计算对资源的消耗，又加快了响应速度; 

### 搜索结果排序
&emsp;&emsp;如果保存在缓存的信息无法满足用户需求，搜索引擎需要调用"网页排序"模快功能，根据用 户的査询实时计算哪些网页是满足用户信息需求的，并排序输出作为搜索结果。而网页排序最 重要的两个参考因素中，一个是内容相似性因素，即哪些网页是和用户查询密切相关的；另外 一个是网页重要性因素，即哪些网页是质量较好或者相对重要的，这点往往可以从链接分析的 结果获得。结合以上两个考虑因素，就可以对网页进行排序，作为用户查询的搜索结果。

[阅读原文](http://blog.csdn.net/hguisu/article/details/7955985)