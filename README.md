<p align="center">
    <img src=".//assets/img/logo.png">
</p>

<p align="center">
    <img src="https://img.shields.io/badge/Category-Data Leakage-red.svg">
    <img src="https://img.shields.io/github/last-commit/No-Github/Dork-Admin.svg?style=popout">
    <img src="https://img.shields.io/badge/Count->=205-blue.svg">
</p>

---

# Manual🦄

**简介 :** 盘点各国各行业的数据泄露、供应链污染事件

**灵感来源 :** https://haveibeenpwned.com/PwnedWebsites、 https://www.freebuf.com/articles/paper/147403.html

**消息源 :** [verizon DBIR](https://enterprise.verizon.com/resources/reports/dbir/)、[haveibeenpwned](https://haveibeenpwned.com)、[securityaffairs](https://securityaffairs.co/wordpress/tag/data-leak)、[hackernews](http://hackernews.cc/archives/category/%E6%95%B0%E6%8D%AE%E6%B3%84%E9%9C%B2)、[Freebuf](https://www.freebuf.com)、[bleepingcomputer](https://www.bleepingcomputer.com)、[zdnet](https://www.zdnet.com)、[Solidot](https://www.solidot.org)、[Rainbowtabl.es](https://rainbowtabl.es/)

**更新间隔 :** 1个月

**隐私保护 :** 配合隐私保护方案食用效果更佳 : [Digital-Privacy](https://github.com/No-Github/Digital-Privacy)

**项目地址 :** https://github.com/No-Github/Dork-Admin

<p align="center">
    <img src=".//assets/img/readme.png">
</p>

---

## 免责声明

1. `本项目所有内容、新闻皆来源于网络,非本人捏造,一切来源可查`

2. `本项目所有内容、新闻皆不代表本人态度、立场`

3. `未收及不会收取任何广告费用,所有记录事件与本人无任何利害关系`

4. `因个人水平、精力有限，无法保证所有新闻真实性、实时性，因个人英语能力实在不佳，大部分内容只能机翻，请观者自行斟酌`

---

# 数据泄露
## 2019🤦‍

### 10月

- **Leafly** 数据泄露

    - 事件经过:

        大麻信息平台 Leafly 向其一些客户发送了通知电子邮件，让他们知道他们的某些信息在数据泄漏事件中暴露。

        Leafly在9月30日发现，自2016年7月2日起，存储在用户记录中的客户信息已由辅助数据库公开。

        “在9月30日，我们进行了合作，未经许可就披露了在 Leafly 数据库中保存的，日期为2016年7月2日的一组 Leafly 用户记录。您的电子邮件地址在该文件中，”警报发送给受影响的客户。

        Leafly 补充说，该公司不收集或存储国家识别码或信用卡信息，也没有证据表明在安全事件中未经授权也可以访问其生产网站。

        该公司与所有受影响的客户联系，删除了暴露的数据库，雇用了法医安全审核员来调查事件并评估情况，并且正在审查数据保护实践和程序。

    - link: https://www.bleepingcomputer.com/news/security/leafly-cannabis-website-leaked-user-info-via-exposed-database/

- **Dutch hookers.nl论坛** 数据泄露

    - 事件经过:

        在荷兰和意大利，很受欢迎的卖淫和护送论坛遭受数据泄露，暴露了其注册会员的用户名，电子邮件地址和哈希密码。

        由于卖淫在荷兰和意大利是合法的，因此创建了论坛，允许用户查看服务或直接与性工作者互动。

        根据荷兰新闻网站NOS的报道，黑客在网上论坛上以300美元的价格出售 Dutch hookers.nl论坛数据库。该数据库包括大约250,000个成员的用户名，哈希密码和IP地址。

        Hookers.nl成员争先恐后地要求删除其帐户，以防止其暴露，但不幸的是数据库已被盗并且已经造成破坏。

    - link: https://www.bleepingcomputer.com/news/security/hacker-selling-user-info-stolen-from-prostitution-forums/

- **Twitter** 某些用户电话号码和电子邮件地址（例如2FA）可能被意外地用于广告定位。

    - 事件经过:

        Twitter说，为帐户安全性提供的某些用户电话号码和电子邮件地址（例如两因素身份验证）可能被意外地用于广告定位。

        “我们最近发现，当您出于安全性目的使用电子邮件地址或电话号码（例如，两因素身份验证）时，该数据可能无意中被用于广告目的，尤其是在我们的量身定制的受众群体和合作伙伴受众群体广告系统中， ”该公司说。

        由于Twitter不知道此事件中受影响的确切人数，该公司希望让所有人都知道发生了什么，因此该信息已公开共享。

        Twitter补充说：“从未与我们的合作伙伴或任何其他第三方在外部共享个人数据。” “从9月17日开始，我们已经解决了导致这种情况发生的问题，并且不再使用出于安全性目的收集的电话号码或电子邮件地址进行广告宣传。”

    - link: https://www.bleepingcomputer.com/news/technology/twitter-apologizes-for-using-your-phone-number-for-advertising/

- **TransUnion Canada** 数据泄露

    - 事件经过:

        未经授权的人可以访问TransUnion Canada网站门户，并使用它来提取消费者信用文件。通过使用从有权访问门户的TransUnion客户窃取的凭据来完成此操作。

        BleepingComputer已获悉，从上周开始，加拿大TransUnion开始通过邮政向消费者发送数据安全事件通知，该消费者的信息是通过未经授权的登录访问的。

        这些通知指出，未经授权的用户在2019年6月28日至7月11日期间使用TransUnion业务门户执行信用文件查找。攻击者能够使用其凭据被盗的TransUnion客户帐户来访问门户。

        一旦未授权用户访问了TransUnion门户，他们就可以使用消费者的姓名，地址，DOB或社会保险号（“ SIN”）进行信用搜索。

        如果输入了正确的信息，则将显示一个信用证文件，其中包含消费者的姓名，出生日期，当前和过去的地址以及与信用证有关的信息，例如贷款义务，欠款和付款历史。但是，实际帐号不会包含在报告中。

    - link: https://www.bleepingcomputer.com/news/security/credit-info-exposed-in-transunion-data-security-incident/

- 新西兰 **PHO** 数据泄露

    - 事件经过:

        来自新西兰的初级卫生组织（PHO）TūOra Compass Health披露了一项安全漏洞，导致大约100万人的医疗和个人身份信息（PII）暴露。

        PHO是非政府组织（NGO），旨在主要通过一般做法为已登记人员提供基本的初级卫生保健服务支持。

        该事件在图拉（TūOra）网站遭到破坏后于8月5日被发现后，将该事件通知了国家网络安全中心，卫生部，警察局和其他执法机构。

    - link: https://www.bleepingcomputer.com/news/security/1-million-people-had-their-medical-data-exposed-in-t-ora-breach/

- **UAB Medical** 数据泄露

    - 事件经过:

        在2019年8月7日，攻击者开始向假装为高管的员工发送电子邮件，要求他们填写调查表。作为此调查的一部分，要求员工提供一些用户名和密码。

        这使攻击者可以访问UAB Medical的工资系统，在该系统中，他们试图将员工的付款重定向到攻击者控制下的银行帐户。

        尽管攻击者未能成功转移薪金存款，但他们能够访问包含近20,000名患者的医疗信息的员工电子邮件。该信息包括患者姓名，出生日期，诊断，治疗信息，以及一小部分的社会保险号。

        “由于这次攻击，UAB Medicine正在通知19,557名患者其受保护的健康信息已经暴露，并且可能已被黑客查看，” 阿拉巴马大学的一份通知说。“受保护的健康信息各不相同，但可能包括患者姓名和以下一个或多个数据元素：病历号，出生日期，服务日期，服务地点，诊断和治疗信息。一小部分患者，并且已经明确通知了那些患者。”

        除了在这些电子邮件帐户和工资系统中找到的数据之外，没有其他数据库可以访问。

        UAB Medical已开始向受违规行为影响的患者发出通知，并建议受感染者监视其信用报告和保险对账单是否存在欺诈或可疑活动。

    - link: https://www.bleepingcomputer.com/news/security/uab-medicine-data-breach-exposes-patient-info-in-phishing-attack/

- 9200万 **巴西人** 的详细信息在地下论坛上拍卖

    - 事件经过:

        有人正在地下论坛上拍卖一个据称包含9200万巴西公民个人信息的数据库。他们声称每条记录都是真实而独特的。

        卖方还刊登了针对巴西人的搜索服务广告，称他们可以从最少的初始数据中挖掘有关个人的详细信息。

        BleepingComputer在一个论坛上看到一个帖子，通知该数据库的大小为16GB，采用SQL格式。拍卖的起拍价为15,000美元，加价幅度为1,000美元。

        根据注册为X4Crow的卖方的记录，每个省的记录都是分开的，并包括个人的姓名，出生日期和纳税人ID（CPF-Cadastro de PessoasFísicas）。该数据库还列出了有关法人或CNPJ（Cadastro Nacional da PessoaJurídica）的纳税人详细信息。

        BleepingComputer收到了该数据库的样本，并能够验证有关个人的信息是否准确，并且还包括母亲的姓名和性别。我们使用了巴西联邦税收网站上的CPF查找服务，该服务还提供了死者的去世年份。

        尽管缓存的来源未在卖方的公告中披露，但BleepingComputer被告知这是一个政府数据库。X4Crow说，它包含9200万条独特的记录，涵盖了“几乎所有巴西公民”。

    - link: https://www.bleepingcomputer.com/news/security/details-of-92-million-brazilians-auctioned-on-underground-forums/

- 一名 **前Yahoo工程师** 入侵了6,000个 Yahoo Mail 帐户

    - 事件经过:

        Yahoo Mail在全球拥有超过2亿活跃用户，这使其成为网络犯罪分子的丰厚目标，但是这次Yahoo的内部人员由于各种错误原因而成为头条新闻。显然，一名前Yahoo工程师入侵了6,000个Yahoo Mail帐户，以提取受害者的个人信息，主要是色情图片和视频。

        根据美国司法部（DOJ）的新闻稿，现年34岁的雷耶斯·丹尼尔·鲁伊斯（Reyes Daniel Ruiz）于2019年9月30日星期一在圣何塞的联邦法院认罪，入侵了包括不当用户但还包括不当用户的Yahoo Mail帐户。还有他的私人朋友和工作同事。

        此外，Ruiz承认使用他在Yahoo上的特殊访问权限来破解受害者的密码，并访问Yahoo的内部系统来破解目标帐户。然后，他下载并复制了被盗图像和视频，并将数据存储在家用计算机中。

    - link: https://www.hackread.com/yahoo-employee-hacked-6000-accounts/

- **Zendesk** 数据泄露

    - 泄露内容:

        - 代理商和最终用户名称以及联系信息
        - 用户名以及哈希密码和盐腌密码
        - 客户提供给Zendesk的传输层安全（TLS）证书
        - 应用程序市场设置，包括少量的集成密钥或密码，Zendesk应用程序使用这些集成密钥或密码对第三方服务进行身份验证

    - 事件经过: 客户服务软件公司Zendesk今天发布了一篇博客文章，并向用户发送有关安全事件的通知，该事件可能影响到2016年11月1日之前激活的大约10,000个Zendesk支持和聊天帐户。

    - link: https://www.bleepingcomputer.com/news/security/zendesk-security-breach-may-impact-orgs-like-uber-slack-and-fcc/

- 游戏巨头 **Zynga** 数据泄露：2.18亿条记录被盗

    - 事件经过:

        一款名为“ Words with Friends”的游戏最近成为数据泄露的受害者，该数据泄露了2.18亿用户的记录，其中包括他们的姓名，电子邮件地址，电话号码，哈希密码和Facebook ID。

        这个叫Gnosticplayers的黑客也早些时候参与了在黑暗网络上出售超过30家公司的泄露数据。其中还包括另一个名为Armor Games的游戏开发平台，似乎他特别喜欢针对游戏社区。不过，关于他如何获得数据的访问尚未得到证实。

        该组织的另一项违规行为还包括对在线图形设计工具Canva的黑客攻击，其中超过1.39亿用户的个人和登录数据被盗并在Internet上泄漏。这位黑客曾因出售从几家公司偷来的1.26 亿个帐户和9200万个帐户而登上新闻头条。

        在与Hackread的独家对话中，Gnosticplayers还分享了从Zynga漏洞中提取的深入细节和示例数据。

    - link: https://www.hackread.com/gaming-giant-zynga-data-breach-218-million-records-stolen/

- 2000万 **俄罗斯人** 的税收记录泄露

    - 泄露内容: 名称、地址、居住状况、护照号、电话号码、税号、税额、雇主详细信息，例如姓名和电话号码

    - 事件经过:

        据一份报告，20个多万的税收记录与来自2009-2016俄罗斯公民的个人身份信息发现再未保护的发现亚马逊网络服务（AWS） Elasticsearch集群。

        从时间轴可以看出，我们可以放心地说，数据在一年多的时间内没有曝光。尽管无法确定数据是否未经授权，但我们确实了解到以下事实：“第一个数据库在2010年至2016年期间包含超过1400万个人和税收记录，第二个数据库在2009年至2015年包含了600万以上的记录。”

    - link: https://www.hackread.com/leaky-database-exposes-tax-records-of-20-million-russians/

- **Comodo论坛** 数据泄露

    - 泄露内容:

        属于Comodo论坛所有用户一半以上的帐户数据已被盗，现在可以在线交易。该漏洞可能是通过利用为论坛提供支持的软件中的漏洞来实现的。

        Comodo今天发布了安全通知，通知用户入侵者可能已经访问了论坛数据库。

        通知开始说：“最近，vBulletin软件中的一个新漏洞已公开，它是用于网站注释（包括Comodo论坛）的最受欢迎的服务器应用程序之一。”

        根据Comodo的公告，攻击者于周日美国东部时间04:57利用vBulletin安全漏洞；他们的行动导致“在Comodo论坛上潜在的数据泄露”。

        该调查尚处于初期阶段，并且正在努力确定已访问了哪些数据。

    - link: https://www.bleepingcomputer.com/news/security/comodo-forums-breached-data-of-over-170-000-users-up-for-grabs/

### 9月

- 美国外卖服务 **DoorDash** 数据泄露：影响 490 万人

    - 泄露内容:

        北京时间9月27日早间消息，美国外卖服务DoorDash周四宣布，一项安全漏洞暴露了该公司大约490万客户、商家和送货员的个人数据。

        这家总部位于旧金山的公司在一份声明中说，此次泄露的信息可能包括大约10万名送货工人的驾驶执照号码，其他数据可能包括“姓名、电子邮件地址、交货地址、订单历史记录、电话号码”等。

        该公司还在声明说，一些消费者支付卡的最后四位数字也可能被暴露出来，但其中没有包含足够的数据来进行欺诈性收费。送货员和商家的银行帐号最后四位数可能已被他人访问。但该公司表示，该信息不足以进行欺诈性提款。

        DoorDash表示已采取其他措施来保护存储在其系统中的数据。该公司称，此次泄露的数据仅限于在2018年4月5日或之前加入公司平台的客户、商家和送货员。

        DoorDash表示，他们本月初已意识到该漏洞，并于5月4日确定“未经授权的第三方访问了DoorDash的某些用户数据”。

        DoorDash的一位发言人表示，该数据泄露行为涉及第三方服务提供商，目前正在进行调查。

    - link: http://hackernews.cc/archives/27567

    - link: https://www.bleepingcomputer.com/news/security/doordash-data-breach-exposes-info-of-roughly-5-million-users/

- **Heyyo** 数据泄露

    - 事件经过:

        在线约会应用程序Heyyo使服务器暴露在互联网上而不受保护，数据存储在Elasticsearch实例上。

        公开的数据包括近72,000名用户的个人详细信息，图像，位置数据，电话号码和约会偏好。

    - link: https://securityaffairs.co/wordpress/91708/breaking-news/heyyo-data-leak.html

- **诺基亚** 员工泄露 **俄罗斯SORM情报**

    - 泄露内容: 俄罗斯珍贵情报1.7 TB

    - 事件经过:

        与俄罗斯SORM计划相关的数据，泄露了1.7TB，被upguard发现并披露。泄露的信息详细说明了整个俄罗斯联邦的电信设施。这些数据包括原理图，管理凭证，电子邮件存档以及与电信基础设施项目相关的其他材料。

        直到最近，这些文件都托管在配置为公共可访问性的rsync服务器上。虽然数据含有来自俄罗斯几家主要电信提供商的文件和数据，但数据泄露源头主要为诺基亚和俄罗斯移动电信系统。

        事后，诺基亚发言人Katja Antila在一份声明中说：“现任员工将包含旧工作文件的USB驱动器连接到家用电脑上。” “由于配置错误，他的PC和连接到它的USB驱动器无需身份验证即可从互联网访问。”

        发言人说：“在我们注意到之后，我们联系了员工，机器已断开连接并被带到诺基亚。”

    - link: https://www.anquanke.com/post/id/187042

- **陕西普通话等级查询网** 将考生数据直接写在源码里

    - link: https://www.cnbeta.com/articles/tech/893573.htm

- **Google日历** 数据泄露

    - 事件经过:

        成千上万的Google日历正在网上泄漏私人信息，威胁到用户的隐私。

        Google日历有超过十亿用户，由于实施了“邀请”功能中的问题，因此有可能公开其私人事务。必须指出的是，这不是Google日历中的安全漏洞，而是可能会影响曾经共享其Google日历的任何人的问题。

        安全研究员Avinash Jain发现了超过8000个在线公开的Google日历，这些日历由Google搜索引擎索引。这意味着任何人都可能访问敏感德塔 并添加可用于共享虚假信息或恶意链接的新事件。

        “我发现的是-使用一个Google dork（高级搜索查询），我可以列出所有公开的Google日历或所有将日历设置为公开的用户。我发现数十个日历被Google的搜索引擎索引，揭示或披露了一些敏感信息。” 专家写道。 “我能够访问各个组织的公共日历，泄露敏感信息，例如电子邮件ID，事件名称，事件详细信息，位置，会议链接，缩放会议链接，Google环聊链接，内部演示文稿链接等等，”

    - link: https://securityaffairs.co/wordpress/91393/digital-id/google-calendar-data-leak.html

- **Lion Air** 数百万旅客记录泄露

    - 泄露内容: 乘客和预订ID，实际地址，电话号码，电子邮件地址，姓名，出生日期，电话号码，护照号码和护照过期日期。

    - 事件经过:

        Lion Air拥有的两家航空公司的客户提供的数千万条记录已经在数据交换论坛上流传了至少一个月。该信息存储在Web上打开的Amazon存储桶中。

        记录存在于两个数据库中，一个数据库中有2100万条记录，另一个数据库中有1400万条记录，这些目录中保存着于2019年5月创建的备份文件，这些文件主要是为Malindo Air和Thai Lion Air创建的。

        另一个备份文件名为“ Batik Air”，这是一家航空公司，其母公司也是Lion Air。

    - link: https://www.bleepingcomputer.com/news/security/millions-of-lion-air-passenger-records-exposed-and-exchanged-on-forums/

- 4亿张医学放射图像在互联网上开放

    - 事件经过:

        总部位于德国的漏洞分析和管理公司 Greenbone Networks 研究了大约2300个连接到公共互联网的图片存档和通信系统（PACS）系统，发现了暴露机密信息的重大问题。

        PACS在医疗保健领域中用于存储和服务从X射线，CT或MRI机器等成像设备获取的医学信息。他们使用DICOM（医学数字成像和通信）标准来传输，存储，检索，打印，处理和显示医学成像数据。

        在7月中旬至9月初之间，Greenbone Networks 使用公共设备发现引擎，确定了590台PACS服务器，可以通过互联网访问这些服务器，并允许检索约2430万患者记录。

    - link: https://www.bleepingcomputer.com/news/security/400-million-medical-radiological-images-exposed-on-the-internet/

- **Thinkful** 数据泄露

    - 事件经过:

        在线开发人员训练营公司Thinkful正在发送电子邮件通知，指出未经授权的用户可以访问员工帐户凭据。因此，他们要求所有用户在下次登录时重设密码。

        根据Thinkful的电子邮件，他们发现未经授权的用户可以访问员工凭证，并立即将密码更改为这些帐户。由于此安全漏洞，出于谨慎考虑，他们决定重设所有用户的帐户。

    - link: https://www.bleepingcomputer.com/news/security/thinkful-resets-all-user-passwords-after-security-breach/

- **厄瓜多尔** 超 2000 万公民数据泄露

    - 泄露内容: 全名（第一，中，最后）、性别、出生日期、出生地、家庭地址、电子邮件地址、家庭，工作和手机号码、婚姻状况、结婚日期（如适用）、死亡日期（如适用）、教育程度

    - 事件经过:

        vpnMentor 的研究团队发现了一个可能影响厄瓜多尔数百万人的大规模数据泄露事件。泄露的数据库包括超过 2000 万人。
        在线数据存储在配置错误的 ElasticSearch 服务器上，使其变得十分危险。公开的数据包括完整的 PII、婚姻状况和结婚日期、教育水平、财务信息等。
        这也许是目前最大的国家性数据泄露，这些数据的暴露对于厄瓜多尔公民构成严重威胁。
        令人在意的事，厄瓜多尔全国人数也只有1700多万，但 ElasticSearch 服务器总共包含大约 2000 万个用户记录，这个记录大于这个国家的人口总数。
        泄露数据量约有 18GB，其中多出的数据来自重复记录或旧记录，比如已去世者的记录。

        对数据的分析表明，数据来源从政府来源（大多数来自厄瓜多尔政府）和私人数据库收集的数据组成。
        专家们还发现，泄露信息中有18万名18岁以下儿童，其中包含姓名， cedulas，出生地，性别，家庭住址。
        该数据库泄露问题于2019年9月11日被 vpnMentor 通知厄瓜多尔 CERT（计算机应急响应小组）团队。

    - link: https://www.vpnmentor.com/blog/report-ecuador-leak/

    - link: https://securityaffairs.co/wordpress/91337/data-breach/ecuador-data-leak.html

- **Delaler Leads** 泄露了 1.98 亿条记录

    - 泄露内容: 姓名，电子邮件，电话，地址，IP

    - 事件经过:

        研究员 Jeremiah Fowler 发现了一个在线暴露的无担保数据库，属于汽车经销商营销公司 Dealer Leads。其中包含 1.98 亿条记录，总计 413GB 的数据，涵盖潜在购车者，车辆，贷款和财务查询的信息，以及访客IP地址的日志数据等。任何浏览器都可以访问 Elastic 数据库，其记录包括纯文本中的姓名，电子邮件，电话，地址，IP 和其他敏感或可识别信息。存档还包括 IP 地址，端口，路径和存储信息。

        好消息是，在专家向公司报告他的发现之后，它已经确保数据库限制了对存档的公共访问。

    - link: https://securityaffairs.co/wordpress/91264/data-breach/delaler-leads-data-leak.html

- **Option Way** 数据泄露事件

    - 泄露内容: 客户姓名，出生日期，性别，电子邮件地址，电话，号码，家庭住址和邮政编码以及有关用户航班和旅行安排的信息

    - 事件经过:

        研究人员 vpnMentor 在飞行预订平台 Option Way 中发现了一个巨大的数据泄露事件，作为网络映射项目的一部分。

        Option Way服务允许其用户查找往返世界各地的航班优惠。

        Noam Rotem 和 Ran Locar 领导的研究团队扫描熟悉的 IP 模块，找出导致组织数据泄露的安全漏洞。
        专家们发现，Option Way 平台使用的大部分数据库完全不受保护且未加密。

        “该公司使用 Elasticsearch 数据库，该数据库通常不是为 URL 使用而设计的。但是，我们能够通过浏览器访问它并操纵 URL 搜索标准来暴露大量数据。“读取专家发布的分析。

        “Option Way 客户和他们平台上的航空公司必须意识到他们在使用技术方面所承担的风险，这些技术只需要很少的努力来保护用户。”

        专家们发现了超过 100GB 的数据，包括客户的未加密个人详细信息（客户姓名，出生日期，性别，电子邮件地址，电话，号码，家庭住址和邮政编码）以及有关用户航班和旅行安排的信息。专家声称，平台网站上发布的以下声明不正确，因为客户的个人身份信息（PII）未加密。

    - link: https://securityaffairs.co/wordpress/90688/uncategorized/option-way-data-breach.html

- **XKCD** 论坛遭网络攻击:大量用户数据被盗

    - 影响人数: 56 万

    - 泄露内容: 用户名、电子邮件和 IP 地址以及 MD5 phpBB3 格式存储的密码

    - 事件经过:

        据外媒报道，黑客攻击了人气网络漫画网站 XKCD 的论坛并从中窃取了约 56 万个用户名、电子邮件和IP地址以及散列密码。

        论坛方面表示，等到他们能够检查漏洞并确保论坛已经安全之后才会重新上线这个论坛。“如果你是 echochamber.me/xkcd 用户，那么你应当立即更改你使用了同一个或类似密码的另一个账号的密码。”

        XKCD 是 Randall Munroe 创作的流行网络漫画，其已经有14年的历史、主要关注科技、科学和互联网文化。Munroe 还以其现在的标志性简笔人物画风格出过几本书，包括《How To》、 《Thing Explainer》、《What If》。

        Hunt 表示，这些数据由白帽子公安全研究员 Adam Davies 发现。

    - link: https://www.cnbeta.com/articles/tech/885565.htm

    - link: https://securityaffairs.co/wordpress/90748/data-breach/xkcd-data-breach.html

    - link: https://www.bleepingcomputer.com/news/security/xkcd-forum-breach-exposes-emails-passwords-of-562-000-users/

- **Facebook** 超过4亿用户电话号码泄漏

    - 泄露内容: Facebook ID 和电话号码,一些记录还包含了用户的姓名、性别和国别。

    - 事件经过:

        储存数亿 Facebook 用户关联电话号码的服务器被发现没有任何密码保护就能访问。暴露的服务器包含了超过 4.19 亿条记录，其中包括 1.33 亿美国用户，1800 万英国用户，5000 多万越南用户。每一条记录包含了用户唯一的 Facebook ID 和电话号码。一些记录还包含了用户的姓名、性别和国别。GDI Foundation 的安全研究员 Sanyam Jain 发现了无密码保护的数据库，因无法识别所有者而联络了 TechCrunch，在联络了托管商之后数据库已经下线。Facebook 发言人 Jay Nancarrow 称，该公司去年关闭了对用户电话号码数据的访问，这些数据是在关闭前抓取的。Facebook 声称这些数据不是新的，但几乎没有人会频繁更换电话号码。

    - link: https://www.solidot.org/story?sid=61980

    - link: https://securityaffairs.co/wordpress/90860/data-breach/facebook-phone-numbers-exposed.html

    - link: https://www.hackread.com/unsecured-database-leaks-phone-numbers-of-facebook-users/

- **Garmin SA** 购物网站付款数据被盗

    - 泄露内容: 付款信息，支付卡的号码，到期日期和 CVV 代码，以及姓名，实际地址，电话号码和电子邮件地址

    - 事件经过:

        Garmin 南非（Garmin SA）今天在向客户发送的一系列通知中披露，这些付款和敏感的个人信息是从 shop.garmin.co.za 购物门户网站上的订单中窃取的。

        Garmin SA 之前曾是 Garmin 经销商，名为 Garmin Distribution Africa（GDA），之后于2011年9月被卫星导航全球领导者 Garmin 收购。

        在2019年7月31日发布的新闻稿中，Garmin 宣布“创纪录的第二季度收入为9.55亿美元，增长7％，其中航空，航海，健身和户外集团比去年同期增长12％。”

        “我们最近发现通过 shop.garmin.co.za（由 Garmin 南非运营）下订单中的客户数据被盗，这些订单损害了您通过网站下达的订单的个人数据，”南非的 Jennifer Van Niekerk 说。常务董事。

        “受损数据仅限于 Garmin 的南非网站，并包含付款信息，包括您的支付卡的号码，到期日期和CVV代码，以及您的姓名，实际地址，电话号码和电子邮件地址。”

        Garmin SA 建议其客户审查并监控所有未经授权的购买的所有支付卡记录。

    - link: https://www.bleepingcomputer.com/news/security/garmin-sa-shopping-portal-breach-leads-to-theft-of-payment-data/

    - link: https://securityaffairs.co/wordpress/91220/data-breach/garmin-sa-data-breach.html

### 8月

- **BioStar 2** 数据泄露

    - 事件经过:

        vpnMentor的团队最近在安全平台BioStar 2中发现了一个巨大的数据泄露事件。

        BioStar 2是基于Web的生物识别安全智能锁平台。它是一个集中式应用程序，允许管理员控制对设施安全区域的访问，管理用户权限，与第三方安全应用程序集成以及记录活动日志。

        作为生物识别软件的一部分，BioStar 2使用面部识别和指纹技术来识别用户。

        该应用程序由Suprema构建，Suprema是世界50强安全制造商之一，在EMEA地区的生物识别访问控制中占有最大的市场份额。Suprema最近与Nedap合作，将BioStar 2集成到其AEOS访问控制系统中。

        AEOS已在83个国家/地区的5700多家组织中使用，其中包括一些最大的跨国企业，许多小型本地企业，政府，银行，甚至是英国大都会警察局。

        漏洞中泄漏的数据具有高度敏感的性质。它包含员工的详细个人信息以及未加密的用户名和密码，从而使黑客可以使用BioStar 2访问设施中的用户帐户和权限。恶意代理可以利用此来入侵安全设施并操纵其安全协议进行犯罪活动。

        这是一个巨大的泄漏，危及相关企业和组织及其员工。我们的团队能够访问超过100万个指纹记录以及面部识别信息。结合个人详细信息，用户名和密码，犯罪活动和欺诈的可能性非常大。

        一旦被盗，就无法获取指纹和面部识别信息。一个人一生可能会受到影响。

    - link: https://www.vpnmentor.com/blog/report-biostar2-leak/

- **万事达** "Priceless Specials" 活动遭遇数据泄露

    - 影响人数: 89,388

    - 泄露内容: 电子邮件地址，IP地址，姓名，部分信用卡数据，电话号码

    - 事件经过:

        万事达卡向德国和比利时数据保护机构（DPA）披露了数据泄露事件，涉及该公司 Priceless Specials 忠诚度计划的客户数据。

        数据在互联网上公布，客户姓名，支付卡号，电子邮件地址，家庭住址，电话号码，性别和出生日期都包含在泄露的信息中。

        万事达卡表示“此事件仅限于特价计划”，而且泄露的唯一支付卡信息是支付卡的数量。

        在发现数据泄露后，万事达卡暂停了德国 Priceless Specials 并取消了其网站，只留下一条消息说“此问题与万事达卡的支付网络无关。”

    - link: https://www.bleepingcomputer.com/news/security/mastercard-reports-data-breach-to-german-and-belgian-dpas/

    - link: https://securityaffairs.co/wordpress/90286/data-breach/mastercard-priceless-specials-loyalty-data-breach.html

    - link: https://haveibeenpwned.com/PwnedWebsites#MastercardPricelessSpecials

    - link: https://www.mastercard.de/de-de/faq-pricelessspecials.html

- **币安** 数千名客户的 KYC 泄露，官方回应:泄露的 KYC 数据来自第三方供应商

    - 事件经过:

        8月初，一些人的细节（即相片持有身份证的个人，如护照和选民身份证）在网上泄露。现在 Binance 确认黑客从第三方供应商那里获得了其用户的 KYC 数据。

        交易所最近证实，一些泄露的照片与实际账户相符，但其他人则被攻击者用 Photoshop 操纵。

        “这项调查的最新证据表明，一些泄露的图像与第三方供应商处理的图像重叠，而 Binance 在2017年12月初至2018年2月底之间签订了几次合同。” 该公司发布的最新消息。

        “在我们审查泄露的图像时，有多个 Photoshop 处理或者更改了与我们数据库中的 KYC 图像不匹配的图像，并将其纳入综合调查。此外，通过 Binance 处理的每个用于 KYC 目的的图像都嵌入了隐藏的数字水印，这在所有泄露的图像中都是显而易见的。

        该公司指出，通过 Binance 处理的用于 KYC 目的的图像嵌入了隐藏的数字水印，该水印在所有泄露的图像中都不存在。

        Binance 补充说，在线泄露的 KYC 数据可能已被更改或用于设置欺诈性的 Binance 帐户。

        该公司仍在调查此事件，同时，它正在通知潜在的受害者，为他们提供“隐私保护和恢复原状的指导”，并建议受影响的用户应在各自的地区申请新的身份证明文件。

        Binance 还通过终身 Binance VIP 会员资格来补偿受影响的用户，包括优惠交易费，支持和更多服务。

    - link: https://securityaffairs.co/wordpress/90391/cyber-crime/binance-leaked-kyc-data.html

- **福昕** 通知客户服务器遭到黑客入侵

    - 泄露内容: 用户名 、电邮地址、企业名称、电话号码、用户账号密码和 IP 地址

    - 事件经过:

        福昕 PDF 阅读器和编辑器的开发商福建福昕软通知客户，黑客入侵了它的服务器访问了用户数据。在给受影响客户的邮件通知中，福昕称，未经授权的黑客访问了 My Account 区域，可能访问的用户数据包括了用户名 、电邮地址、企业名称、电话号码、用户账号密码和 IP 地址。它声称信用卡或其它支付信息没有暴露。福昕没有解释泄露的密码是否是加密或加盐还是明文储存，它建议用户下一次登陆时修改密码。

    - link: https://www.solidot.org/story?sid=61920

    - link: https://securityaffairs.co/wordpress/90580/data-breach/foxit-software-data-breach.html

    - link: https://www.bleepingcomputer.com/news/security/foxit-software-discloses-data-breach-exposing-user-passwords/

    - link: https://www.foxitsoftware.com/support/security-advisories.php

- **Imperva** 数据泄露,客户信息曝光

    - 泄露内容: 电子邮件地址、加盐的 Hash 密码

    - 事件经过:

        网络安全 Imperva 公司披露了一项数据泄露事件，该数据泄露事件暴露了云网应用防火墙（WAF）产品（以前称为 Incapsula）的部分客户的敏感信息。

        mperva 首席执行官 Chris Hylen 透露，该公司于2019年8月20日获悉该事件，当时该公司了解了影响云网络应用防火墙（WAF）产品的数据风险。

        "在2019年8月20日，我们从第三方那里了解到数据曝光会影响我们的云 WAF 产品的一部分客户，这些客户的账户截至2017年9月15日。截至2017年9月15日，Incapsula 客户数据库的元素已曝光。其中包括:电子邮件 地址 哈希和盐渍密码 “

        泄露的数据包括2017年9月15日之前注册的所有Cloud WAF客户的电子邮件地址和散列和盐渍密码。

        Hylen 此外，对于 Incapsula 客户的一部分，截至2017年9月15日，已公开 API 密钥和客户提供的 SSL 证书。

    - link: https://securityaffairs.co/wordpress/90464/data-breach/imperva-data-breach.html

    - link: https://www.bleepingcomputer.com/news/security/cybersecurity-firm-suffers-security-breach-client-info-exposed/

- **Hostinger** 披露了影响 1400 万客户的数据泄露事件

    - 泄露内容: 用户名，电子邮件，散列密码，名字和IP地址

    - 事件经过:

        Hostinger，最大的托管服务提供商之一，披露了最近的安全漏洞，允许攻击者访问客户端数据库。

        安全漏洞发生在8月23日，可能已经影响了1400万 Hostinger 顾客。

        “2019年8月23日，我们收到了一条信息警报，指出我们的某台服务器已被未经授权的第三方访问过。该服务器包含一个授权令牌，用于获取对我们的系统 RESTful API Server * 的进一步访问和升级权限。此 API Server * 用于查询有关客户及其帐户的详细信息。

        暴露的数据包括 Hostinger 用户名，散列密码（SHA1），客户的IP地址，名字和姓氏以及联系信息（即。电话号码，电子邮件和家庭住址）。根据 Hostinger 的说法，财务数据没有暴露在攻击中。

        为了应对这一事件，该公司重置了所有受影响客户的密码。

    - link: https://securityaffairs.co/wordpress/90377/data-breach/hostinger-data-breach.html

    - link: https://www.bleepingcomputer.com/news/security/hostinger-data-breach-affects-almost-14-million-customers/

- **德邦快递员工** 卷入货到付款诈骗:窃取 50 万用户信息 案值 1200 万

    - 事件经过:

        据央视报道，今年 7 月，南京的刘女士报警称，女儿替她签收了一份“99 元货到付款”包裹，在付钱后，她发现，包裹里的东西竟是一个看上去价值仅有几元钱的劣质灯，而事实上，刘女士并没有在下过单。而更加令她惊讶的是，包裹上的个人信息，完全和她本人相符。

        南京警方一查，竟然牵出了德邦快递多名员工大肆窃取用户信息，并勾结电商公司老板，全国撒网进行"99 元货到付款"精准诈骗的黑幕。

        据警方介绍，犯罪嫌疑人为了窃取信息，还说服了河南郑州的三个区域经理。这三个区域经理为了增加自己营业部的发货量，主动将自己的账户密码交给犯罪嫌疑人，以供其窃取用户信息。为了提高诈骗成功率，电商老板郑某还会筛选，选择那些网购量大同时又喜欢货到付款的用户进行诈骗。

        经警方初步核算，案值超过 1200 万，被侵犯的公民个人信息数量总数不少于 50 万。目前，包括德邦快递 6 名员工在内的 13 名犯罪嫌疑人，因涉嫌侵犯公民个人信息罪或诈骗罪被刑事拘留。

    - link: https://linux.cn/article-11249-1.html

- 成人网站 **Luscious** 的 119.5 万用户个人数据遭泄露

    - 泄露内容: 用户名、所在地、性别以及用户活动日志也遭到泄露，活动日志包含了视频上传、建立图册、评论、发帖、收藏夹、关注列表等内容

    - 事件经过:

        近日，据外媒报道，vpnMentor 发布报告称，成人网站 Luscious 的 119.5 万用户个人数据遭泄露，泄露内容包括个人电子邮件地址（部分包含用户全名）。 除此之外，包括用户名、所在地、性别以及用户活动日志也遭到泄露，活动日志包含了视频上传、建立图册、评论、发帖、收藏夹、关注列表等内容。据估计，大约 20％ 的 Luscious 帐户使用一次性或假电子邮件帐户，但这仍然会留下大约 800,000 个合法电子邮件地址和私人资料。

    - link: https://www.cnbeta.com/articles/tech/880657.htm

- **Choice Hotels** 700,000条记录在线泄露

    - 泄露内容: 姓名，电子邮件地址和电话号码

    - 事件经过:

        Comparitech 的专家在研究员 Bob Diachenko 的帮助下发现了一个不安全的数据库，其中包含来自酒店特许经营连锁酒店的 700,000 条记录。在归档被BinaryEdge搜索引擎索引之后，专家们在2019年7月2日发现了包含 560 万条记录的未授权 MongoDB 档案。

        Diachenko 立即通知公司暴露的 MongoDB 实例，但似乎黑客首先得到它。他们留下了赎金票据要求0.4比特币 Choice Hotels 试图淡化问题，解释说档案中的大多数记录都包含测试信息，除了 700,000 个真实的条目。
        暴露的记录包含访客数据，包括姓名，电子邮件地址和电话号码。

        Diachenko 立即向 Choice Hotels 报告了他的调查结果，然而，骗子们已经获得了数据，并试图勒索这项业务。

        在分析数据库时，Diachenko 发现黑客留下的赎金票据要求该公司提供 0.4 BTC（4,000美元）。可能入侵者已经对数据进行了备份，并且在要求支付赎金之前将要擦除档案。

    - link: https://securityaffairs.co/wordpress/90146/hacking/ruby-libraries-backdoor.html

- **新西兰航空** 遭受钓鱼攻击，客户信息被泄露

    - 事件经过:

        新西兰航空公司向注册其 Airpoints 忠诚度计划的客户发送电子邮件，警告他们网络钓鱼攻击成功破坏了两名员工的电子邮件帐户，这可能导致攻击者访问个人信息。

        虽然电子邮件确实说安全事件中没有访问客户的 Airpoints 帐户，但 O'Brien 的电子邮件声明“我们的内部文件中可能会显示与您的会员资料相关的一些信息。您的Airpoints密码和您的信用卡卡详情不受影响。“

        在发现网络钓鱼攻击后，该公司保护了两个受感染的电子邮件帐户，并开始调查以了解攻击者如何能够访问数据。奥布莱恩还表示，新西兰航空公司现在也在“进一步加强我们的安全流程，以帮助防止未来发生任何类似事件。”

    - link: https://www.bleepingcomputer.com/news/security/customer-information-exposed-in-air-new-zealand-phishing-attack/

- 知名约会软件 **3Fun** 泄露大量用户隐私和地理定位

    - 泄露内容: 出生日期、性偏好、聊天信息和私人照片。

    - 事件经过:

        近期，为“好奇和单身人士”服务的 3Fun 手机约会应用被曝出发生了会员数据数据泄露事件，涉及用户隐私和地理定位。

        3Fun 声称在全球拥有超过 150 万会员。每天会产生超过 18 万条交流信息。

        Pen Test Partners 的安全研究人员发现，这款约会应用存在几个严重的安全漏洞，导致用户的实时位置和其他敏感数据被泄露。具体数据包括出生日期、性偏好、聊天信息和私人照片。此外，信息泄漏和用户设置无关，即使用户正确地启用了隐私设置，个人数据也会被泄漏。

        研究人员注意到，该应用对数据的管理过滤只在客户端实现，攻击者只需使用简单的流量中转软件，即可绕过安全限制，查看到敏感信息。

    - link: https://nosec.org/home/detail/2854.html

    - link: https://securityaffairs.co/wordpress/89655/data-breach/3fun-data-leak.html

    - link: https://www.bleepingcomputer.com/news/security/3fun-dating-app-exposes-exact-location-of-users-and-personal-info/

- **Sephora** 数据泄露事件

    - 泄露内容: 登录名，加密密码，注册日期和最后活动，注册IP，最后IP，性别，姓名，种族，眼睛颜色，肤色，皮肤类型，头发颜色，头发问题，化妆品必需品他说，以及护肤程序

    - 事件经过:

        总部位于新加坡的网络安全公司 Group-IB 表示，它发现了两个数据库，地下论坛上的客户数据“可能与丝芙兰有关”。首席执行官 Ilya Sachkov 在发布中表示，第一个数据库分别于7月7日和7月17日在两个地下论坛上做广告。根据卖方的说法，该数据库包含 500,000 条记录，包括 Sephora 印度尼西亚和泰国网站的用户名和散列密码。

    - link: https://www.channelnewsasia.com/news/singapore/sephora-data-breach-customer-records-for-sale-dark-web-11772722

- 安全漏洞导致 **Suprema Biostar** 1百万人指纹数据曝光

    - 泄露内容: 指纹，面部识别信息，未加密的用户名和密码以及员工的个人信息。

    - 事件经过:

        据悉，研究人员在 Suprema 的系统中发现了一个安全漏洞，使之能够访问超过100万人的身份验证数据。英国《卫报》指出，这些数据包括了指纹/面部识别数据、未加密的用户名和密码、甚至员工的个人信息。以色列研究人员 Noam Rotem、Ran Locar 与 vpnmentor 一起寻找到了 Suprema 的安全漏洞，并且获得了Biostar 2 数据库的访问权限。在获得访问权限后，安全研究人员发现该数据库缺乏应有的保护，且大多数据处于未加密的存储状态，很容易访问到总量超过2780万条（23GB+）的记录。除了敏感信息，安全研究人员还能够轻松监控存储的生物识别数据的实际使用情况。比如实时查看哪个用户通过特定的安全门进入任何设施，甚至查看到管理员账户的密码。

    - link: https://bgr.com/2019/08/14/suprema-biostar-2-data-security-breach-exposes-actual-fingerprint-data/

    - link: https://securityaffairs.co/wordpress/89929/data-breach/suprema-biostar-2-data-leak.html

- 数以万计的 **MoviePass** 客户的信用卡号码在网上曝光

    - 泄露内容: MoviePass 借记卡号及其到期日，卡的余额和激活时间

    - 事件经过: 一位安全专家发现了电影票订阅服务商 MoviePass 已经暴露了数以千计的客户卡号和个人信用卡信息。由于数据库未加密，包含信用卡数据的数据库被泄露，涉及包含 1.61 亿条记录，并且数据量继续实时增长。

    - link: https://securityaffairs.co/wordpress/90165/data-breach/moviepass-data-leak.html

- 12 万人数据被泄露？**雪球** 回应:已进行核实

    - 泄露内容: 姓名，身份证，手机，账号/邮箱，密码，持股前3支，持股数，交易风格。

    - 事件经过: 8月21日消息，网上流传称雪球网数据泄露，涉及12万人的数据只卖75美元，包含姓名，身份证，手机，账号/邮箱，密码，持股前3支，持股数，交易风格。对此雪球回应称，不会以任何方式将个人信息泄露给第三方，对此问题已进行核实。

    - link: http://hackernews.cc/archives/27064

- **本田** 汽车云端数据库未保护，CEO 及全球员工大量资料险遭泄露

    - 泄露内容: 经查这批资料包括几乎所有 Honda 电脑相关资料，其中一个表格包含员工电子邮件、部门名称、Honda 机器主机名称、MAC 地址、内网 IP、作业系统版本。另一个表格则有员工姓名、部门、​​员工编号、帐号、手机号码及最近登入时间。

    - 事件经过: 安全研究人员发现日本汽车大厂本田汽车（Honda Motor）一个云端数据库，内含超过1亿份文件，包含员工电脑主机名称、IP、使用哪套安全软件等信息。该数据库没有设置身份验证措施，任何人均可访问，本田公司已经在接获通报后迅速修补了该隐患。

    - link: https://www.freebuf.com/news/210249.html

- [30亿条信息泄露，96家互联网公司遭殃，案子破了！](https://www.leiphone.com/news/201908/L1mPvhOLN9Hg0kGW.html)

- **StockX** 遭黑客攻击，暴露了数百万用户记录

    - 泄露内容: 姓名，电子邮件地址，哈希密码（加盐 MD5）以及其他个人资料信息，如鞋码和交易货币。受损数据还包括用于内部目的的设备信息和其他信息。

    - 事件经过: 运动鞋交易平台 StockX 上周向用户发送一封密码重置的电子邮件，但并没有说明原因。一位未透露姓名的数据卖家向媒体透露，黑客在 5 月份从网站上窃取了 680 多万条记录。卖家提供 1000 条数据样本，经证实这些信息确实是真实的。

    - link: https://techcrunch.com/2019/08/03/stockx-hacked-millions-records/

    - link: https://securityaffairs.co/wordpress/89464/data-breach/stockx-hacked.html

    - link: https://www.bleepingcomputer.com/news/security/stockx-hack-exposes-personal-information-of-customers/

- **Poshmark** 数据泄露事件

    - 泄露内容: 用户名，哈希密码，姓名，性别信息和居住城市

    - 事件经过: 8月1日，美国社交商务市场 Poshmark 披露了数据泄露事件。该公司发现未经授权访问其服务器，入侵者窃取 个人信息 用户，包括 用户名，哈希密码，姓名，性别信息和居住城市。攻击者还可以访问服装尺寸偏好，用户电子邮件和客户的社交媒体资料信息。当时事件发生时尚不清楚。

    - link: https://securityaffairs.co/wordpress/89384/data-breach/poshmark-data-breach.html

- **ESA** 网站漏洞导致超过 2000 名参与报道 E3 的记者个人信息泄漏

    - 事件经过: 在参与报道了全球最大的视频游戏大会E3之后，由于组织方系统存在的安全漏洞导致大量记者的个人联系信息被公开曝光。在报告中称目前已经有超过2000人受到影响，除了各大新闻机构和媒体的记者、编辑之外，还有YouTube和Twitch等视频网站上的网红主播，以及高盛、IMDb和其他公司的工作人员。

    - link: https://www.cnbeta.com/articles/science/874939.htm

### 7月

- **Club Penguin Rewritten** 遭遇数据泄露

    - 影响人数:400万

    - 泄露内容: 电子邮件地址，IP地址，密码，用户名

    - 事件经过: 2019年7月，儿童游戏网站Club Penguin Rewritten（CPRewritten）遭遇数据泄露（注:CPRewritten是迪士尼俱乐部企鹅游戏的独立娱乐）。 除了影响170万个帐户的早期数据泄露之外，随后的漏洞还暴露了400万个唯一的电子邮件地址以及存储为bcrypt哈希的IP地址，用户名和密码。

    - link: https://haveibeenpwned.com/PwnedWebsites#ClubPenguinRewrittenJul2019

- **LAPD** 数据泄露致 2500 名警官个人信息被盗

    - 泄露内容: 姓名、电子邮件地址、出生日期、部分职工序列号及密码。

    - 事件经过:

        洛杉矶警察局（LAPD）遭遇数据泄露，暴露了数千名警察和申请人的姓名，电子邮件地址，密码和出生日期。

        NBCLosAngeles 证实，数据泄露是在 2019 年 7 月 20 日发现的，当地媒体透露，有2,500名洛杉矶警察局官员和大约 17,500 名警务人员的个人信息被曝光。

        “一名黑客声称他或她偷走了大约 2,500 名洛杉矶警察局官员，受训人员和新兵的个人信息，以及大约 17,500 名警察申请人“。报道的媒体。

        该市机构总经理特德罗斯说:“该市的信息技术机构上周表示，有人声称访问并下载了数据，并且该人提供了一些示例文件，表明他们实际上已经获得了数据。”

    - link: https://www.bleepingcomputer.com/news/security/lapd-data-breach-exposes-personal-info-of-roughly-25k-officers/

    - link: https://securityaffairs.co/wordpress/89134/data-breach/lapd-data-breach.html

    - link: https://www.cnbeta.com/articles/tech/873075.htm

- **Capital One** 超一亿人信用数据外泄案

    - 泄露内容: 14万个美国社保号码、1百万个加拿大社会保险号码和约8万个银行账号，包括用户姓名、住址、信用值、信用额度等大量信息遭到泄露。

    - 事件经过:

        7月30日讯 据美国广播公司新闻网（ABC News）消息，当地时间本周一早晨，西雅图地区一女子因涉嫌参与窃取美国第一资本金融公司（Capital One）超一亿名用户的信用数据被逮捕。

        美国第一资本金融公司当地时间本周一发表声明表示，其在7月19日发现一个安全漏洞，有一个未经授权的来源获得了该公司信用卡用户的“特定类型的个人信息”，此次信息泄露共涉及到大约1亿美国人以及6百万加拿大人。

    - link: https://securityaffairs.co/wordpress/89114/data-breach/capital-one-data-breach.html

    - link: https://www.cnbeta.com/articles/tech/873011.htm

- **CPRewritten** 遭遇数据泄露

    - 泄露内容: 电子邮件地址，IP 地址，密码，用户名

    - 事件经过: 2019年7月，儿童游戏网站 Club Penguin Rewritten（CPRewritten）遭遇数据泄露（注:CPRewritten是迪士尼俱乐部企鹅游戏的独立娱乐）。 除了影响 170 万个帐户的早期数据泄露之外，随后的漏洞还暴露了 400 万个唯一的电子邮件地址以及存储为 bcrypt 哈希的 IP 地址，用户名和密码。

    - link: https://haveibeenpwned.com/PwnedWebsites#ClubPenguinRewrittenJul2019

- 俄罗斯联邦安全局承包商 **SyTech** 被黑客窃取 7.5TB 的数据

    - 事件经过: 2019年7月13日，一群名为 0v1ru $ 的黑客入侵了 SyTech 的活动目录服务器，从那里他们获得了访问该公司整个IT网络的权限，包括一个 JIRA 实例。为了证明他们可以访问 Sytech 的服务器，0v1ru $ 发布了 Sytech 网站的内部页面以及 Windows 域控制器中的服务器驱动器和用户的图像。这些被盗数据随后被传递给另一个名为 DigitalRevolution 的黑客组织  ，后者与俄罗斯媒体分享了这些数据。DigitalRevolution 声称在 2018 年攻击了俄罗斯研究机构“Kvant”。

    - link: https://www.bleepingcomputer.com/news/security/russian-fsb-intel-agency-contractor-hacked-secret-projects-exposed/

    - link: https://securityaffairs.co/wordpress/88657/intelligence/fsb-contractor-sytech-hacked.html

- **国内某移动应用营销公司** 约 900G 数据泄漏，数百万泄露的记录来自 100 多款手机贷款应用

    - 泄露内容: 身份信息、信用卡、银行、设备、位置、贷款记录、交易信息、风险管理数据、账单、已安装应用程序列表、app tracking data、用户密码。

    - 事件经过: 最初发现数据泄露的研究人员安努拉格森(Anurag Sen)表示，尽管在阿里云下线该服务器后，泄露的数据库现在无法访问，但拥有该数据库的公司却不为人知。然而，根据研究人员的意见，泄露的数据似乎归移动应用程序营销机构所有，该机构将大量信息存储在租用的服务器上。在阿里云下线，可公开访问的数据库将超过 460 万个移动设备的数据在开放状态下保留了大约两周。

    - link: https://www.bleepingcomputer.com/news/security/real-time-location-of-millions-exposed-by-mobile-loan-apps/

- **Evite** 1.01 亿账号信息泄露

    - 影响人数: 1.01 亿

    - 泄露内容: 姓名，用户名，电子邮件地址，密码，电话号码，出生日期

    - 事件经过: 电子邀请网站 Evite 发布安全通知，承认部分用户账号信息被盗。名叫 Gnosticplayers 的黑客今年四月在暗网销售六家公司的用户数据，其中一家就是 Evite。Evite 在通知中称，恶意活动始于 2019 年 2 月 22 日，它在 4 月才得知系统被未经授权访问，5 月 14 日它得出结论黑客获取了它的一个不使用的数据存储文件，储存了 2013 年之前的用户数据，其中包括姓名，用户名，电子邮件地址，密码，如果用户填入的话还包括电话号码、出生日期和邮箱地址。Evite 称它没有收集社会安全号码或银行账号信息。它已经向受影响的用户发去通知重置密码。

    - link: https://www.evite.com/security/update

    - link: https://www.solidot.org/story?sid=61356

    - link: https://www.bleepingcomputer.com/news/security/evite-invites-over-100-million-people-to-their-data-breach/

- **BlackSpigotMC** 遭遇数据泄露

    - 影响人数: 14万

    - 事件经过: 在2019年7月，黑客网站 BlackSpigotMC 遭遇了数据泄露。据称，基于 XenForo 论坛的网站遭到竞争对手黑客网站的攻击，导致 8.5GB 数据被泄露，包括数据库和网站本身。暴露的数据包括 140k 唯一的电子邮件地址，用户名，IP 地址，性别，地理位置和存储为 bcrypt 哈希的密码。

    - link: https://haveibeenpwned.com/PwnedWebsites#BlackSpigotMC

- **保加利亚国家税务局** 500 万公民数据被窃，占比全国 70%

    - 影响人数: 500万

    - 事件经过: 一位神秘黑客上周末入侵了保加利亚国家收入署，下载了其数据库，然后将下载链接发送给了本地新闻机构。保加利亚内政部已经证实了这起黑客入侵事件。根据黑客透露给当地媒体的信息，他窃取了超过 500 万保加利亚人的个人信息。保加利亚全国人口只有 700 万。黑客从国家收入署下载了 110 个数据库，容量接近 21 GB，黑客分享了 57 个数据库，容量约 11 GB。泄露的信息包括姓名、个人识别号码 ((PINs)、家庭住址和财务收入。大多数信息都是旧的，可上溯到 2007 年，但也发现了较新的数据库条目。在黑客论坛 Instakilla 分享的文件容量约 10.7 GB，包括了 57 个文件夹，与当地媒体收到的数据库一致。

    - link: https://www.zdnet.com/article/bulgarias-hacked-database-is-now-available-on-hacking-forums/

    - link: https://www.solidot.org/story?sid=61417

    - link: https://securityaffairs.co/wordpress/88477/data-breach/bulgarians-data-leak.html

- 黑客使用三星网站访问了数量不明的 **Sprint** 账户数据。

    - 影响人数: 未知

    - 泄露内容: 电话号码，设备类型，设备 ID，每月经常性费用，用户ID，帐号，帐户创建日期，升级资格，姓名，帐单地址和添加 - 关于服务。

    - 事件经过:

        美国电信公司 Sprint 在发送给客户的违规通知信中说，黑客设法使用 Samsung.com“Add A Line”网站作为其攻击的跳板，渗透到他们的账户。

        “6月22日，黑客通过 Samsung.com“Add A Line”网站使用您的帐户凭据获知未经授权访问您的 Sprint 帐户，”违规警报信中说。针对此事件，移动网络运营商于6月25日重置其用户的 PIN 码。美国电信公司没有透露受影响客户的数量。

    - link: https://www.bleepingcomputer.com/news/security/sprint-accounts-breached-by-hackers-using-samsung-site/

    - link: https://securityaffairs.co/wordpress/88514/data-breach/sprint-data-breach.html

- **招聘平台简历买卖产业链 (反正我无 fuck 说)**
    - [你的求职简历可能被卖了: 价格从0.3元到2.5元](https://www.thepaper.cn/newsDetail_forward_3903162)
    - [用智联招聘求职引来骚扰电话不断 记者亲测发现这些猫腻](https://www.cnbeta.com/articles/tech/866949.htm)
    - [智联招聘员工参与倒卖个人信息，16万个人简历被出售](https://tech.sina.com.cn/i/2019-07-08/doc-ihytcitm0576205.shtml)
    - [智联招聘回应16万份简历泄露: 积极协助公安机关进行调查](https://www.pingwest.com/w/190932)

- **中国江苏省公安厅** 开放的 ElasticSearch 服务器泄露超过 9000 万条记录

    - 影响人数: 9000万

    - 泄露内容: 个人身份信息（PII）名称，出生日期，性别，身份证号码，位置坐标，以及有关个人的city_relations，city_open_id 和 province_open_id 的信息。

    - 事件经过:

        中国江苏省公安厅拥有的一个可公开访问和无担保的 ElasticSearch 服务器 泄漏了两个数据库，其中包含超过9000万人和商业记录。这两个现在安全的数据库包含 26 GB 的数据，其形式包括个人身份信息（PII）名称，出生日期，性别，身份证号码，位置坐标，以及有关个人的 city_relations，city_open_id 和 province_open_id 的信息。对于企业，记录包括业务ID，业务类型，位置坐标，city_open_id 和用于跟踪业务所有者是否已知的备忘录。

        除了两个暴露的 ElasticSearch 数据库外，江苏省公安厅还有一个公安网络管理控制台，需要一个有效的用户/密码组合才能访问，以及在服务器上运行的可公开访问的Kibana安装，这将有助于浏览和使用基于 GUI 的界面分析存储的数据。

        但是，与暴露的 Kibana 安装的其他情况不同，这个没有完全配置，一旦加载到Web浏览器中，它将直接进入“创建索引模式页面”。

        虽然 Jain 和 BleepingComputer 在联系江苏省公安厅后没有收到任何回复，但 CNCERT / CC 响应迅速，并且有所帮助，立即联系数据库所有者并在周末将其取消。

    - link: https://www.bleepingcomputer.com/news/security/over-90-million-records-leaked-by-chinese-public-security-department/

- **美国土地产权协会 ALTA** 成员被网络钓鱼攻击

    - 泄露内容: 域名，IP 地址，用户名和密码

    - 事件经过:

        美国土地产权协会（ALTA）发布了一项警告，警告称数百家公司唱片的记录被认为是针对ALTA成员的网络钓鱼活动的一部分而被盗。

        ALTA 是美国的一个全国贸易协会，自 1907 年成立以来，它代表着 6,000 多家产权保险公司，产权和结算代理人，房地产律师和独立抽象人。

        “声称自己是道德黑客的人通过 Twitter 联系 ALTA 并提供包含大约 600 个数据条目的文件，包括域名，IP 地址，用户名和密码。这些数据还包含非标题公司的信息，”ALTA 警告说。

        ALTA 的 IT 部门仍在分析网络犯罪分子可能获得的高度敏感信息，如果找到与他们相关的任何连接，将联系受此行业违规影响的公司。

    - link: https://www.bleepingcomputer.com/news/security/industry-breach-alert-published-by-us-national-trade-association-alta/


- **美国马里兰州政府机构** 数据库遭到未经授权的访问

    - 影响人数: 7万

    - 泄露内容: 受影响的 LWIS 文件来自 2009 年，2010 年和 2014 年。这些文件可能包含名字，姓氏，社会安全号码，出生日期，城市或居住地，毕业日期和记录号。受失业保险服务数据库影响的文件来自 2013 年，可能包含名字，姓氏和社会安全号码。

    - 事件经过:

        马里兰州劳工部（Maryland DoL）今天发布了一份新闻稿，解释说，未经授权的一方可以访问大约 78,000 名客户的敏感信息，包括姓名和社会安全号码。

        马里兰州信息技术部（Maryland DoIT）目前正在调查数据泄露情况，该数据泄露信息存储在“扫盲工程信息系统和遗留失业保险服务数据库”中。

        到目前为止，马里兰州 DoIT 的调查没有发现任何证据表明“任何个人身份信息是从工作服务器下载或提取的”。

    - link: https://www.bleepingcomputer.com/news/security/maryland-govt-agency-breach-exposes-names-ssns-of-78k-people/

- **Orvibo** 旗下的一个可公开访问的 ElasticSearch 集群泄露了超过 20 亿条敏感数据

    - 泄露内容: 电子邮件地址、密码、帐户重置代码、精确的用户地理位置、IP 地址、用户名和用户 ID、姓氏和家庭 ID、设备名称和访问帐户的设备、通过智能相机记录的会话、计划信息

    - 事件经过:

        中国智能家居解决方案提供商 Orvibo 旗下的一个可公开访问的 ElasticSearch 集群泄露了超过 20 亿条用户日志，其中包含来自世界各国的客户敏感数据。

        Orvibo 为其客户提供智能解决方案，旨在通过智能系统帮助他们管理房屋，办公室和酒店客房，提供安全和能源管理，以及使用智能家居云平台进行远程控制和数据记录/分析。

        在 Orvibo 的智能家居解决方案允许其用户控制的设备中，该公司的云平台支持交互中心，智能照明，家庭安全，HVAC，能源管理和家庭娱乐设备。

        暴露的 Orvibo 数据库“包含超过 20 亿条日志，记录从用户名，电子邮件地址和密码到精确位置的所有内容”，并且由于公司未对6月16日联系的 vpnMentor 研究团队做出回应，因此仍然在线。

        正如研究人员还指出的那样，“只要数据库保持开放，每天的可用数据量就会持续增加，”来自世界各地的用户，包括中国，日本，泰国，美国，英国，墨西哥，法国，澳大利亚和巴西受到数据泄露的影响。

    - link: https://www.bleepingcomputer.com/news/security/billions-of-records-including-passwords-leaked-by-smart-home-vendor/

### 6月
- **Artvalue** 15万会员账号信息泄露

    - 影响人数: 15万

    - 泄露内容: 电子邮件地址，姓名，密码，称呼，用户名

    - 事件经过: 2019年6月，总部位于法国的艺术评估网站 Artvalue.com 将其 158,000 名会员用户群公开在其网站上的文本文件中公开。 公开的数据包括以 MD5 哈希值存储的名称，用户名，电子邮件地址和密码。 网站运营商在联系事件时没有回复，尽管随后删除了暴露的文件。

    - link: https://haveibeenpwned.com/PwnedWebsites#Artvalue

- **Attunity** 的 AWS S3 存储桶泄露 Netflix，福特，TD Bank 等数据

    影响目标: Netflix，福特，TD Bank、Attunity

    - 泄露内容: Netflix:认证字符串、D Bank:软件升级发票(谁能解释一下这个是啥?)、福特:项目文档、Attunity:IP地址、等

    - 事件经过:

        总部位于以色列的数据集成和大数据管理公司 Attunity 未能正确管理三个 Amazon S3 存储桶，暴露了多伦多道明银行（TD），福特和Netflix等财富100强客户的数据。

        Attunity 是一家目前与至少与一半财富100强公司合作的公司，根据其网站拥有超过2000名客户，该公司泄露了客户和自己的数据，UpGuard研究人员下载了超过1TB的信息进行分析。

        虽然 Upguard 发现的开放 S3 存储桶的总大小不确定，但其中包含的数据包括高度敏感的业务和个人信息，如“电子邮件通信，系统密码，销售和营销联系信息，项目规范等”。

        Upguard于5月13日发现了这些数据库，最初的上传时间是2014年9月，最近上传的文件的时间戳是被发现前几天。

    - link: https://www.bleepingcomputer.com/news/security/netflix-ford-td-bank-data-exposed-by-open-amazon-s3-buckets/

- **MedicareSupplement.com** 的 MongoDB 数据库泄露 500 万份个人记录

    - 泄露内容: 全名，邮政地址，电子邮件地址，出生日期，性别，电话号码和IP地址

    - 事件经过:

        一个属于健康保险营销网站 MedicareSupplement.com 的无担保 MongoDB 实例上个月在网上被发现，其中包含多达 500 万条记录。数据缓存包括个人信息和健康详细信息。

        MedicareSupplement.com 由 TZ Insurance Solutions 拥有并运营。其目的是帮助个人找到合适的 Medigap 保险计划，这是一种私人医疗保险，涵盖原始医疗保险没有的费用。根据其 Facebook 页面，该服务帮助超过40万人找到了合适的保险计划。

        5月13日，Compariteh 的研究人员与 Bob Diachenko 一起发现了公共数据库。

        研究人员指出，他们发现的 MongoDB 实例似乎是该网站营销线索数据库的一部分。，研究人员联系了 MedicareSupplement.com 以提醒他们接触，但网站代表没有回复。他们确实修改了 MongoDB 服务器的配置以保护数据库。

    - link: https://www.bleepingcomputer.com/news/security/open-marketing-database-exposes-5-million-personal-records/

- **SocialEngineered.net** 被黑客攻击，数据在黑客论坛上被共享

    - 影响人数: 5.5万

    - 泄露内容: 用户名、加盐MD5密码、电子邮件地址，IP地址和私人消息

    - 事件经过:

        大约两周前，一个专门讨论社会工程主题的论坛遭到泄露，数万名成员的数据在黑客攻击的同一天在网上泄露。

        社交网站SocialEngineered.net的一篇帖子周四宣布，该论坛被MyBB论坛软件的一个漏洞攻破。

        黑客成功利用 XSS 和文件写入，导致远程代码执行并完全接管目标站点。尽管MyBB前一天推出了一个补丁版本，但网站安装安全补丁的速度通常很慢，这给攻击者提供了一个浏览网页寻找目标并攻击他们的机会。

    - link: https://www.bleepingcomputer.com/news/security/social-engineering-forum-hacked-data-shared-on-leak-sites/

- **维也纳图书馆(Wiener Buchereien)** 发生数据泄露。

    - 影响人数: 22万

    - 泄露内容: 出生日期，电子邮件地址，姓名，电话号码，实际地址

    - 事件经过: 2019年6月，维也纳图书馆（WienerBüchereien）遭遇数据泄露。受损数据包括224k唯一的电子邮件地址，姓名，实际地址，电话号码和出生日期。随后，被指控的违规行为人将违规数据发布到推特上。

    - link: https://futurezone.at/digital-life/wiener-buechereien-gehackt-daten-von-77000-nutzern-im-netz/400524190

    - link: https://haveibeenpwned.com/PwnedWebsites#WienerBuchereien

- **WeTransfer** 发生安全事件，文件通过电子邮件发送给错误的人

    - 事件经过: WeTransfer 发布公告称，部分通过电子邮件通道传输的文件于6月16日和17日被发送到非预期的电子邮件地址。事件发生后，一些用户已退出帐户并重置密码。此外，该公司表示，它阻止了受影响的转移链接。WeTransfer 警告受影响的个人要留意任何“可疑或不寻常的电子邮件”。至少有一位安全专家推测 WeTransfer 可能已被黑客入侵。

    - link: https://www.freebuf.com/news/206785.html

    - link: https://www.securityweek.com/wetransfer-security-incident-file-transfer-emails-sent-wrong-people

- **NASA** 自曝遭入侵，黑客利用树莓派窃取500MB火星任务数据

    实际发生时间: 2018年4月

    - 事件经过: 根据一份49页的OIG报告，黑客通过入侵一个共享网络网关然后利用该入口深入JPL网络，之后进入了存有NASA JPL管理的火星任务信息的网络。NASA OIG表示: “攻击者从23个文件中窃取了大约500MB的数据，其中2个文件包含有跟火星科学实验室任务有关的国际武器管制信息。”调查人员表示，除了进入JPL的任务网络，2018年4月的入侵者还访问了JPL的DSN IT网络。由于担心攻击者可能也会转向他们的系统，NASA的其他几家机构在遭受入侵的同时切断了与JPL和DSN网络的连接。

    - link: https://threatpost.com/feds-hackers-mission-control-data-nasa-jpl/145842/

    - link: https://www.extremetech.com/internet/293563-a-rogue-raspberry-pi-let-hackers-into-nasas-jpl-network

    - link: https://www.freebuf.com/news/206651.html

- **Social Engineered** 遭遇数据泄露

    - 影响人数: 8.9万

    - 泄露内容: 电子邮件地址，IP地址，密码，私人消息，用户名

    - 事件经过: 2019年6月，“人类黑客艺术”网站 Social Engineered 遭遇数据泄露。其中包括论坛 55k 用户和数据库中其他表中的 89k 个唯一电子邮件地址。公开的数据还包括用户名，IP 地址，私人消息和加盐的 MD5 哈希的密码。

    - link: https://haveibeenpwned.com/PwnedWebsites#SocialEngineered

- **X Social Media** 泄露了美国退伍军人在战斗中受伤的数据

    - 影响人数: 15万

    - 泄露内容: 全名，电子邮件地址，家庭住址，电话号码以及与其案件相关的详细信息

    - 事件经过: 一家总部位于美国佛罗里达州的广告代理商在互联网上公开了一个数据库，该数据库泄露了过去广告活动的详细信息，包括有关医疗事故案件的信息以及美国退伍军人在战斗中受伤的敏感细节。研究人员表示，该数据库包含了填写表格的用户的150,000多条回复。这些表格中包含的数据通常包括全名、电子邮件地址、家庭住址、电话号码以及与其案件相关的详细信息——主要涉及医疗损伤。

    - link: https://www.zdnet.com/article/ad-agency-leaks-data-on-us-military-veterans-combat-injuries/#ftag=RSSbaffb68

    - link: https://www.freebuf.com/news/206411.html

- **美国俄勒冈州人力资源服务部门** 发生数据泄露，影响645000名客户

    - 影响人数: 64万

    - 实际泄露时间: 2019年1月8日

    - 泄露内容: 姓名，物理地址，出生日期，社会安全号码（SSN），病例号，受保护的健康信息（PHI）以及各种 DHS 计划中使用的其他详细信息

    - 事件经过: 美国俄勒冈州人力资源服务部门官员证实，该组织在今年1月发生了数据泄漏事件，645000名用户的个人详细信息和健康信息受影响。受数据泄露影响的个人参加了该部门的福利和针对儿童安全事件的服务计划。违规行为发生在1月8日针对该部门的电子邮件”网络钓鱼“攻击中，九名员工打开了该电子邮件，并点击了一个链接，让攻击者能够访问他们的电子邮件帐户，然后进一步访问数据。

    - link: https://securityaffairs.co/wordpress/87348/data-breach/oregon-department-of-human-services-data-breach.html

    - link: https://www.bleepingcomputer.com/news/security/phishing-attack-exposes-data-of-645-000-oregon-dhs-clients/

    - link: https://www.freebuf.com/news/206528.html

- **Desjardins** 发生数据泄露事件，290万会员受影响

    - 影响人数: 290万

    - 泄露内容: 姓名、出生日期、社会保险号码、地址、电话号码、电子邮件地址、及银行信息和 Desjardins 产品的详细信息,公司名称、公司地址、公司电话号码、所有者姓名和 AccèsDAffaires 帐户上的用户名称，以及与 AccèsDAffaires 帐户用户相关的一些个人信息

    - 事件经过:

        Desjardins 集团是北美最大的信用合作社协会，根据其官方推特账户，也是加拿大最大的合作金融集团。大约290万 Desjardins 集团成员的个人敏感信息在未经授权的访问中向公司外部人员泄露。泄露的个人会员信息包括: 姓名、出生日期、社会保险号码、地址、电话号码、电子邮件地址、及银行信息和 Desjardins 产品的详细信息。 对于商业会员，泄露的数据包括公司名称、公司地址、公司电话号码、所有者姓名和AccèsDAffaires帐户上的用户名称，以及与 AccèsDAffaires 帐户用户相关的一些个人信息。

        在发现数据泄漏后，Desjardins 通知了加拿大隐私专员办公室，魁北克信息委员会和 Autoritédesmarchés 金融家，并解雇了这名恶意雇员。

    - link: https://www.bleepingcomputer.com/news/security/desjardins-group-data-leak-exposes-info-of-29-million-members/

    - link: https://www.freebuf.com/news/206528.html

- 黑客窃取 **EatStreet Data Breach** 中的客户付款信息

    - 泄露内容: 姓名，地址，电话号码，电子邮件地址以及银行帐户等信息

    - 实际泄露时间: 2019年5月

    - 事件经过: EatStreet 表示，黑客能够在5月3日至5月17日检测到漏洞时访问其数据库，在2019年5月3日，未经授权的第三方访问了我们在2019年5月17日发现的数据库。未经授权的第三方能够获取2019年5月3日在我们数据库中的信息。但是我们能够，当我们发现事件时，立即终止对我们系统的未授权访问。

    - link: https://www.bleepingcomputer.com/news/security/hacker-steals-customer-payment-info-in-eatstreet-data-breach/

- **中国猎头公司 FMC Consulting** 配置错误的 ElasticSearch 集群造成数据泄露(据文章称涉事公司收到报告毫无反应，直到 CNCERT 出面才下线数据)

    - 泄露内容: 数百万份简历和公司记录，以及客户和员工的 PII 数据。

    - 事件经过:

        FMC Consulting（一家中国猎头公司）拥有一个配置错误且可公开访问的 ElasticSearch 集群，泄露了数百万份简历和公司记录，以及客户和员工的 PII 数据。

        包含数十万条客户记录，内部电子邮件以及员工日常任务的数据库以及他们在联系客户时所做的调用都没有受到保护，将所有数据暴露给知道在哪里以及如何查找它的人。

        根据该公司的 LinkedIn 简介，“FMC 成功地帮助我们的客户在中国充满活力的市场中放置了 10,000 多个竞争职位（截至2018年底）。这些职位包括专业职位，中层管理职位和区域业务负责人。“
        作为 GDI 基金会成员和独立安全研究员的 Sanyam Jain 发现了错误配置的ElasticSearch 集群，并联系了 BleepingComputer 以取消数据库。

    - link: https://www.bleepingcomputer.com/news/security/headhunting-firm-leaks-millions-of-resumes-client-private-data/

- **PayID** 遭网络攻击 十万客户信息泄露

    - 影响人数: 10万

    - 泄露内容: 不详

    - 事件经过: 西太平洋银行（Westpac）的实时支付平台 PayID 系统遭网络攻击，近10万客户的私人信息泄露。这次袭击行为还会影响到其它银行的客户。计算机安全专家警告，这些被窃取的私人信息可能会被用于欺诈。根据悉尼晨锋报获得的一份机密备忘录，西太平洋银行向澳洲银行业和金融业披露了有关这次网攻事件的信息。其中说: “2019年5月22日，西太平洋银行注意到，澳洲支付平台 PayID（NPPA PayID）的大量查询（约60万个）来自七个被泄露的西太平洋银行有效账户，约9.8万个查询成功解析了一个短名字，并暴露给了欺诈者。”

    - link: https://www.smh.com.au/business/banking-and-finance/australians-private-details-exposed-in-attack-on-westpac-s-payid-20190603-p51u2u.html

- **格雷斯兰大学** 未经授权的用户访问当前员工的电子邮件帐户

    - 泄露内容: 全名、社會安全號碼、出生日期、位址、電話號碼、電子郵件地址、父母/兒童、工資資訊、格雷斯蘭的註冊或可能註冊的財政援助資訊

    - 事件经过: 在6月14日发布的数据泄露通知中称，Graceland 已經意識到三個實例,即未經授權的使用者訪問當前員工的電子郵件帳戶,包括與這些帳戶相關的內容和附件。未經授權的使用者分別于 2019年3月29日以及 2019年4月1日至30日和2019年5月12日至5月1日訪問這些個人帳戶。這些帳戶現已得到保護,但是,已經確定,在過去幾年中與這些電子郵件帳戶交互的一些人的個人資訊在未經授權的使用者訪問期間可用。格雷斯蘭曾試圖使用檔案上的位址向這些人發送一封物理信件。

    - link: https://www.graceland.edu/notice-of-data-breach

    - link: https://www.bleepingcomputer.com/news/security/three-us-universities-disclose-data-breaches-over-two-day-span/

- **俄勒冈州立大学 (OSU)** 資料隱私事件

    - 事件经过:

        俄勒岡州立大學週五宣佈,5月初發生的資料隱私事件可能影響到636份包含個人識別資訊的學生記錄和家庭記錄。

        一名 OSU 員工的電子郵件帳戶被大學外的個人入侵,用於向全國發送網路釣魚電子郵件。OSU 和法醫專家進行的一項調查發現,在 OSU 員工電子郵件帳戶的收件匣中發現了幾份檔,這些檔包含 636 名學生和學生家庭成員的個人資訊。

        "OSU 正在繼續調查此事,並確定網路攻擊者是否用個人資訊查看或複製這些檔,"該大學負責大學關係和行銷的副校長史蒂夫·克拉克(Steve Clark)說。"雖然我們目前沒有跡象表明個人資訊已被查看或使用,但 OSU 已將這一事件通知了這些學生和家庭成員。我們還提供了有關現有支援服務的資訊,包括該大學將免費提供的 12 個月信用監控服務。

        克拉克說,OSU 正在審查許多保護程式和 IT 系統,該大學使用來保護其資訊系統,電子郵件帳戶,學生和家庭記錄。他說:"我們將繼續監控此類工作和系統,並採取進一步措施保護大學的資訊技術和敏感性資料。

    - link: https://today.oregonstate.edu/news/oregon-state-university-reports-it-security-incident

- **密蘇里州南部州立大學(MSSU)** 造網路釣魚攻擊，資料洩露

    - 泄露内容: 名字和姓氏，出生日期，家庭住址，电子邮件地址，电话号码和社会安全号码

    - 事件经过:

        它在发送给佛蒙特州司法部长办公室的数据泄露通知中表示，它已被警告1月9日网络钓鱼邮件可能引发网络攻击。

        网络钓鱼攻击使该大学的员工中有几名受害者提出了执法通知。事后，大学官员被告知要延迟通知受影响的个人，直到调查完成为止。

        MSSU 还聘请了一家领先的法证调查公司来调查安全事件并“阻止潜在的电子邮件利用，包括重置所有员工 Office 365 帐户的密码”。

        在分析受影响的 Office 365 帐户的内容后，MSSU 发现电子邮件包含在存储的“名字和姓氏，出生日期，家庭住址，电子邮件地址，电话号码和社会安全号码”中。

    - link: https://www.documentcloud.org/documents/6153866-Missouri-Southern-State-University-Notice-of.html

- **芝加哥大學** 超過150萬捐贈者的私人資訊暴露

    - 影响人数: 150万

    - 泄露内容: 全名、出生日期、完整地址、电话号码、电子邮件、性别、婚姻状况、财富信息和当前状态、通讯说明

    - 事件经过:

        超過160萬潛在和現有的芝加哥大學醫學捐贈者的個人資訊被一個配置錯誤和未受保護的彈性搜尋伺服器暴露在互聯網上沒有密碼。

        5月28日,安全發現研究員鮑勃·迪亞琴科(Bob Diachenko)發現了這個可公開訪問的 ElasticSearch 實例,一天前,連接互聯網的設備搜尋引擎Shodan將其添加到其公開伺服器索引中。

        在仔細查看公開的資料後,Diachenko 瞭解到,名為"data-ucmbsd2"的 34GB 大小彈性搜索群集包含 1,679,993 條記錄,任何知道在哪裡以及如何查找它的人都可以訪問這些記錄。

    - link: https://www.bleepingcomputer.com/news/security/private-info-of-over-15m-donors-exposed-by-uchicago-medicine/


- **复古遊戲網站 Emuparadise** 遭受 110 萬帳戶的資料洩露

    - 影响人数: 110萬

    - 泄露内容: 电子邮件地址，IP地址，用户名和密码

    - 事件经过: “在2018年4月，自称”地球上最大的复古游戏网站“，Emupardise 遭遇了数据泄露。受损的 vBulletin 论坛公开了110万个电子邮件地址，IP地址，用户名和密码存储为盐渍 MD5 哈希。数据提供通过 dehashed.com 到 HIBP。“

    - link: https://www.bleepingcomputer.com/news/security/gaming-site-emuparadise-suffered-data-breach-of-11m-accounts/

- **AMCA** 数据泄露1900万客户受影响

    - 影响人数: 1900万

    - 泄露内容: 银行账户数据和信用卡号，社会安全号码

    - 事件经过:

        正如美国证券交易委员会诊断的 SEC 通知中所述，AMCA 告知该公司“2019年8月1日至2019年3月30日期间，未经授权的用户可以访问 AMCA 的系统，该系统包含 AMCA 从各种实体收到的信息，包括 Quest Diagnostics，以及AMCA收集的信息。““截至2019年5月31日，AMCA 认为，其信息包含在 AMCA 受影响系统中的 Quest Diagnostics 患者人数约为1190万人，” 美国证券交易委员会的通知也表示。

        Quest Diagnostics 表示，它无法确认从 AMCA 收到的信息的准确性，并且没有实验室测试结果受到安全事件的影响，因为它们没有提供给 AMCA。

        诊断信息服务提供商补充说，它“非常重视此事，致力于保护患者的个人，医疗和财务信息的隐私和安全。”

        AMCA 告诉 Quest Diagnostics 他们“已就此事件与执法部门联系”，但尚未提供有关违规行为的“详细或完整信息”。

    - link: https://www.bleepingcomputer.com/news/security/billing-details-for-119m-quest-diagnostics-clients-exposed/

    - link: https://www.bleepingcomputer.com/news/security/quest-labcorp-amca-sued-for-breach-impacting-over-19-million/

    - link: https://www.bleepingcomputer.com/news/security/over-400-000-opko-health-clients-impacted-by-amca-data-breach/

### 5月
- **上海交大** 泄漏 8.4TB 邮件元数据 (你知道shodan搜这种未授权访问的业务有多容易吗？我来告诉你)[点击看看](https://www.shodan.io/search?query=port%3A%229200%22+all%3A%22elastic+indices%22)

    - 泄露内容: 8.4 TB 电子邮件元数据、发送电子邮件的人的IP地址和用户代理，设备类型等

    - 事件经过: 安全研究员通过搜索 Shodan，发现了一个没有任何身份验证的 ElasticSearch 数据库。该数据库属于上海交大，包含了 8.4TB 邮件元数据，但不包含邮件正文内容。数据库包含了 95 亿行数据，5 月 23 日数据库容量只有 7TB，24 日就增加到了 8.4 TB。交大安全团队在收到报告之后就在当天关闭了开放访问。元数据包括了发送方，接收方，IP 地址、检查邮件时的用户代理，以及设备类型等。

    - link: https://rainbowtabl.es/2019/06/09/shanghai-jiao-tong-university-email-metadata-leak/

    - link: https://www.solidot.org/story?sid=60937

- **三星** 多个项目代码泄露 包括 SmartThings 源代码和密钥

    - 泄露内容: 多个内部项目，包括三星 SmartThings 敏感的源代码、证书和密钥。

    - 事件经过: 三星数十个自主编码项目出现在旗下 Vandev Lab 的 GitLab 实例中。该实例被三星员工用于分享并贡献各种应用、服务和项目的代码。由于这些项目被设置为“公开”，同时没有受到密码的保护，因此任何人都可以查看项目，获取并下载源代码。迪拜信息安全公司 SpiderSilk 的安全研究员莫撒布·胡赛因（Mossab Hussein）发现了这些泄露的文件。他表示，某个项目包含的证书允许访问正在使用的整个 AWS 帐号，包括100多个 S3 存储单元，其中保存了日志和分析数据。

    - link: http://hackernews.cc/archives/25425

- **Ladders** Database Exposed 13M User Records

    - 影响人数: 1300万

    - 影响对象: Ladders User

    - link: https://securityaffairs.co/wordpress/84861/data-breach/ladders-data-leak.html

- **Instagram** 4900万条数据曝光，影响人数达数百万

    - 影响人数: 4900万条记录

    - 影响对象: Instagram 用户

    - 泄露内容: 用户资料、图片、粉丝数据、以及验证过的国家/地区、私人联系信息（包括电话、电子邮件等），甚至还有用户已删除信息内容。

    - 事件经过: 据 TechCrunch 网站报道，Instagram 的一个大型数据库由于在 AWS 存储桶上没有受到保护，导致任何人都可以在没有身份验证的情况下访问它。该数据库首先由安全研究人员 Anurag Sen 发现，并立即报告给了 TechCrunch 网站。

    - link: https://securityaffairs.co/wordpress/85905/data-breach/instagram-data-leak.html

- **Hindustan** 大量员工和商业信息公开暴露

    - 影响对象: Hindustan 雇员、应聘者

    - 大致时间: 2019年5月

    - 泄露内容: 包括新雇员的个人信息和明文密码、客户基础设施安装报告以及管理人员的 Web 应用程序,应聘者的 ID、姓名，手机号码、加入日期、加入地点、招聘人员 SAP 代码、招聘人员姓名、创建日期、用户名、明文密码、BGV 状态、已接受的 offer 以及应聘申请表的链接。超过2,800名员工的名称和 SAP 代码,可以使用 SAP 代码和名称查找和’停用’员工”的界面,使用 SmartManage 报告系统管理的客户安装报告和项目数据,一份内部分析报告数据库，包含5700条事件记录、每周客户报告（约18,000个条目）以及可追溯到2016年的安装报告

    link:https://www.freebuf.com/news/204276.html

- **优衣库** 遭到黑客攻击，超过46万用户数据泄漏

    - 影响人数: 46万用户

    - 影响对象: 用户

    - 大致时间: 2019年5月

    - 泄露内容: 个人信息、电子邮件、地址以及部分信用卡资料

    - 事件经过: 日本最大的服装零售商迅销集团发布消息称，旗下优衣库以及 GU 品牌的在线商城遭到黑客攻击，约46万用户的数据泄漏，包括用户个人信息、电子邮件、地址以及部分信用卡资料等。迅销称，此事件仅限于日本网站，发生在4月23日至5月10日期间，是一次基于列表的攻击。当客户在多个网站上使用相同的用户名和密码组合时，可能会遭受此类攻击，建议用户更改密码。

    - link: https://www.freebuf.com/news/203923.html

- **OGUsers** 论坛遭遇了数据泄露,被竞争对手脱裤

    - 影响人数: 16万

    - 大致时间: 2019年5月19日

    - 泄露内容: Email addresses, IP addresses, Passwords, Private messages, Usernames

    - 事件经过: In May 2019, the account hijacking and SIM swapping forum OGusers suffered a data breach. The breach exposed a database backup from December 2018 which was published on a rival hacking forum. There were 161k unique email addresses spread across 113k forum users and other tables in the database. The exposed data also included usernames, IP addresses, private messages and passwords stored as salted MD5 hashes.

    - link: https://haveibeenpwned.com/PwnedWebsites#OGUsers

- **Canva** 1.39 亿用户数据泄露

    - 影响人数: 1.39 亿

    - 影响对象: Canva 用户

    - 泄露内容: 用户名字、真名 、电邮地址、城市国家信息 、哈希密码、Google 令牌 、Gmail 地址

    - 事件经过: 自称 GnosticPlayers 的黑客声称窃取了澳大利亚网站 Canva 的 1.39 亿用户数据。Canva 是一个非常受欢迎的平面设计服务，Alexa 排名在 200 以内。黑客窃取的数据包括了用户名字、真名 、电邮地址、城市国家信息，其中 6100 万用户有哈希密码，其他用户的信息还有用于登陆的 Google 令牌。有 7800 万用户使用了 Gmail 地址。Canva 证实它的数据库遭到非法访问，表示尚未发现账号被入侵，出于谨慎考虑它已经鼓励用户更改密码。

    - link: https://www.zdnet.com/article/australian-tech-unicorn-canva-suffers-security-breach/

- **Ordine Avvocati di Roma** 遭到一个自称意大利匿名者的组织的数据泄露。

    - 影响人数: 41,960

    - 影响对象: 罗马律师

    - 泄露内容: Email addresses, Email messages, Geographic locations, Passwords, Phone numbers

    - 事件经过: In May 2019, the Lawyers Order of Rome suffered a data breach by a group claiming to be Anonymous Italy. Data on tens of thousands of Roman lawyers was taken from the breached system and redistributed online. The data included contact information, email addresses and email messages themselves encompassing tens of thousands of unique email addresses. A total of 42k unique addresses appeared in the breach.

    - link: https://haveibeenpwned.com/PwnedWebsites#OrdineAvvocatiDiRoma

- **Flipboard** 遭黑客攻击，用户名密码等信息泄露

    - 影响人数: 未知

    - 影响对象: Flipboard 用户

    - 泄露内容: 用户名、姓名、电子邮件地址和密码,Flipboard 连接到第三方服务，例如Twitter和Facebook的数字令牌

    - 事件经过: 本周，新闻聚合应用 Flipboard 就此前发生的信息泄露事件向用户发送电子邮件进行告知。在这次事件中，黑客获得了用户的用户名、电子邮件地址和受保护的密码。从2018年6月2日至2019年4月22日，Flipboard 的数据库发生了“未经授权的访问”，导致用户的帐号信息泄露。Flipboard 表示，黑客“有可能获得了”一些数据库的拷贝，但尚未透露有多少帐号被入侵等细节。

    - link: https://tech.sina.com.cn/i/2019-05-30/doc-ihvhiqay2380994.shtml

- **Perceptics** 车牌识别公司遭黑客入侵，敏感数据被盗

    - 泄露内容: 内部文件，文件名和附带目录总数量近65000，包括商业计划、财务数据和个人信息。数百GB，Microsoft Exchange 和 Access 数据库、ERP 数据库、HR 记录、Microsoft SQL Server 数据存储等

    - 事件经过: 据外媒5月24日报道，Perceptics 公司是一家提供车牌识别器、车牌识别系统和车辆识别产品的公司。该公司遭到黑客入侵，内部文件被窃取，文件名和附带目录总数量近65000，包括商业计划、财务数据和个人信息。被盗文件达数百GB，包括 Microsoft Exchange 和 Access 数据库、ERP 数据库、HR 记录、Microsoft SQL Server 数据存储等。该公司业务涉及边境安全数据采集、商用车检查、电子收费和道路监控，因此拥有大量敏感数据。该公司表示已发现其网络遭到入侵，正在对事件进行调查。

    - link: https://www.leiphone.com/news/201905/44M2ZJusnWhYY89Z.html

- **Pyramid Hotel Group** 85GB 的安全日志暴露于公网

    - 泄露内容: 安全审计日志

    - 事件经过: 近日，研究人员发现了一个公开的数据库，内容包含了万豪在内的众多连锁酒店的安全日志，其中还包括潜在的安全漏洞。该团队于2019年5月27日发现故障服务器，经过检测发现该服务器连接了酒店和度假村管理公司 Pyramid Hotel Group，该公司是美国、夏威夷、英国、爱尔兰等地包括万豪、喜来登、希尔顿等19个酒店及物业的管理方。故障服务器可通过9200端口关联到 Elasticsearch 数据库，并可不受限制的访问由开源入侵检测系统Wazuh生成的安全审计日志。该数据库的暴露直接公开了酒店的大量敏感数据，虽然数据库中每个记录都没有明确的名称，但 Tarrytown House Estate、Carton House Luxury Hotel、Aloft Hltels、Temple Bar Hotel 这些关键词都是可以直接识别的。据统计，暴露的安全审计日志内容一共达到了 85.4GB。

    - link: https://www.zdnet.com/article/unsecured-database-exposes-security-logs-of-major-hotel-chains/#ftag=RSSbaffb68

- **EatStreet** 遭遇数据泄露

    - 影响人数: 640万

    - 泄露内容: 姓名，电话号码，地址，部分信用卡数据和存储为bcrypt哈希的密码

    - 事件经过: 2019年5月，在线食品订购服务公司 EatStreet 遭遇数据泄露，影响了640万客户。黑客获得了大量的个人数据，包括姓名，电话号码，地址，部分信用卡数据和存储为 bcrypt 哈希的密码。

    - link: https://haveibeenpwned.com/PwnedWebsites#EatStreet

### 4月
- **Bilibili** 网站后台工程源代码被上传至[Github](https://github.com/openbilibili)(ikun 大胜利?),官方回应:较老版本，已报案

    - 影响对象: bilibili

    - 泄露内容: 网站后台工程源代码

    - 大致时间: 2019年4月22

    - 事件经过: 大家好，我是练习时长两年半的灭霸，爱好是唱跳 rap 篮球 music~

- **Docker Hub** 未经授权的访问者访问了 Docker Hub 的数据库，可能导致泄露19万用户敏感数据

    - 影响人数: 19万

    - 影响对象: Docker Hub 用户

    - 大致时间: 2019年4月

    - 事件经过:

        官方发送的安全通知，Docker 于2019年4月25日发现有未经授权的访问者访问了Docker Hub的数据库。

        在进行调查之后，确定该数据库包含大约190000个用户的敏感信息。这些信息包括用于 Docker 自动编译的 GitHub 和 Bitbucket 存储库的访问令牌以及一小部分用户的用户名和密码哈希值。

- **京东** 疑似泄露5千万用户数据,官方回应:谣传

    - 影响人数: 5000万

    - 影响对象: 京东用户

    - 大致时间: 2019年4月

- **领英** 某 AWS 开放数据库泄露 6000 万条领英用户信息记录,官方回应:不是我们的数据库

    - 影响人数: 6000万

    - 影响对象: 领英用户

    - 泄露内容: 数据中包含领英个人资料信息，包括 ID、个人资料网址、工作经历、教育经历、住址、技能、其他社交个人资料以及个人资料上次更新的时间。

    - 大致时间: 2019年4月

    - 事件经过: 近日，研究人员发现了八个不安全的数据库泄露了约 6000 万条领英用户信息记录。虽然大多数信息是公开的，但数据库中包含领英用户的电子邮件地址。

- **Facebook** 再被指泄漏用户数据，至少5.4亿用户资料任由下载(厉害了，又是你facebook)

    - 影响人数: 至少5.4亿名用户

    - 影响对象: Facebook 用户

    - 大致时间: 2019年4月

    - 事件经过: 据《彭博社》报导，网络保安公司 UpGuard 在亚马逊云端数据库上发现大量 Facebook 用户的个人资料，涉及至少5.4亿名用户，且数据开放予任何人下载。报导指出，墨西哥城媒体公司 Cultura Colectiva 的数据库储存了5.4亿名 Facebook 用户的个人资料，包括身份证号码、帐号称谓、网上评论及回应记录等。Cultura Colectiva 专门发布拉丁美洲娱乐及文化消息，在 Facebook、Instagram、Twitter、YouTube 等开设专页，拥有逾4500万用户追踪。《彭博社》向 Facebook 查询，Facebook 随后通报亚马逊，相关数据库已被封锁。Facebook 发言人表示，公司政策禁止将用户资料储存于公开数据库，此次发现事件后即时通知亚马逊处理；发言人称，公司致力与平台开发商合作保障用户私隐。

### 3月
- **纽约市消防局** 丢失载有员工医疗记录和社会保险号的硬盘

    - 泄露内容: 社会保险号码、医疗记录

    - 事件经过: 纽约市消防局（FDNY）披露了2019年3月发生的“数据泄露”。与其他数据泄露事件（通常涉及未经授权的一方利用易受攻击的网络）不同，FDNY 的问题是由于一枚可移动硬盘丢失造成的。根据纽约市官员发布的声明，这一驱动器属于一名被授权访问该信息的员工。

    - link: https://www.cnbeta.com/articles/tech/877453.htm

- **Citrix** 遭到未经授权访问内部网络

    - 泄露内容: 商业文档和文件

    - 事件经过: 攻击者在2018年10月13日至2019年3月8日期间间歇性地访问了 Citrix 的基础设施。通知称，他们主要从一个用于存储当前和历史业务文档的公司共享网络驱动器，以及一个与我们咨询业务中使用的基于 web 的工具相关联的驱动器中窃取业务文档和文件。

    - link: https://www.citrix.com/blogs/2019/03/08/citrix-investigating-unauthorized-access-to-internal-network/

    - link: https://www.citrix.com/blogs/2019/05/20/citrix-updates-on-unauthorized-internal-network-access/

    - link: https://www.citrix.com/blogs/2019/07/19/citrix-concludes-investigation-of-unauthorized-internal-network-access/

- **MindJolt** 遭遇数据泄露

    - 影响人数: 2836万

    - 泄露内容: 出生日期，电子邮件地址，姓名

    - 事件经过: 在2019年3月，在线游戏网站 MindJolt 遭遇数据泄露，暴露了 28M 独特的电子邮件地址。 同样受影响的还有姓名和出生日期，但没有密码。

    - link: https://haveibeenpwned.com/PwnedWebsites#MindJolt

- **丰田** 已经证实，在日本经销商遭到袭击之后，多达310万份丰田和雷克萨斯客户数据可能遭到窃取。

    - 影响人数: 310万

    - 事件经过:

        该公司表示，黑客窃取了其 IT 系统并访问了属于多个销售子公司的数据。

        该名单包括丰田东京销售控股，东京东京汽车，东京 Toyopet，丰田东京卡罗拉，Nets丰田东京，雷克萨斯 Koishikawa 销售，Jamil Shoji（雷克萨斯练马）和丰田西东京卡罗拉。

        丰田表示，黑客访问的服务器存储了多达310万客户的销售信息。该汽车制造商表示正在进行调查，以确定黑客是否泄露了他们可以访问的任何数据。

        丰田表示，客户财务细节并未存储在黑客服务器上。但是，该公司没有透露黑客可能访问过什么类型的信息。

    - link: https://www.zdnet.com/article/toyota-announces-second-security-breach-in-the-last-five-weeks/

    - link: https://www.forbes.com/sites/daveywinder/2019/03/30/toyota-and-lexus-dealerships-hacked-leaving-customers-at-risk-what-you-need-to-do-now/#3362feee5092

- **SkyMed** Database Exposes Medical Info, PII Data of 137k People in U.S.

    - 影响人数: 13万

    - 影响对象: SkyMed members

    - 泄露内容: full names, addresses, dates of birth, email addresses, phone numbers

    - link: https://www.bleepingcomputer.com/news/security/database-exposes-medical-info-pii-data-of-137k-people-in-us/


- **北京机到网络科技有限公司** 3300万份国人简历泄露

    - 影响人数: 3300万

    - 泄露内容: 求职者的用户名，性别，年龄，当前城市，家庭住址，电子邮件地址，电话号码，婚姻状况，工作经历，教育历史和工资历史

    - 事件经过:

        A large database with approximately 33 million profiles for people seeking jobs in China has been fully accessible and unprotected online. This information included sensitive information that could have been used for scammers and identity theft.

        The database was discovered by Sanyam Jain, a security researcher and member of GDI.Foundation, who found the database using the Shodan search engine.

    - link: https://www.bleepingcomputer.com/news/security/unsecured-database-exposed-33-million-job-profiles-in-china/

### 2月
- **YouNow** 的数据在暗网市场上出现

    - 泄露内容: 电子邮件地址，IP地址，名称，社交媒体档案，用户名

    - 事件经过: 2019年2月，来自直播服务 YouNow 的数据出现在一个黑暗的网络市场上出售。虽然不清楚实际违规发生的日期，但受影响的数据包括1800万个唯一的电子邮件地址、知识产权地址、姓名、用户名和社交媒体档案链接。由于身份验证是通过社交提供商进行的，因此没有密码被泄露。许多记录没有关联的电子邮件地址，因此唯一的号码低于报告的帐户总数。

    - link: https://haveibeenpwned.com/PwnedWebsites#YouNow

- **抖音** 上百万账号遭撞库攻击

    - 事件经过:

        今年2月，海淀公安分局双榆树派出所接到辖区北京字节跳动公司报案，称其公司旗下抖音APP遭人恶意撞库达上千万账户密码，其中上百万账户密码被黑客撞出。为防止黑客利用撞出账户实施不法行为，公司通过安全系统对所有疑似被盗账号设置了二次登录验证。

        接到报警后，警方立刻展开侦查，并迅速锁定了一名湖北籍男子汪某。5月22日，民警远赴湖北将汪某抓获归案，并起获了其作案时使用的笔记本电脑。

        经讯问，汪某交代，毕业后一直无业，便利用掌握的计算机技术，编写了大量撞库代码，对目前网络上比较热门的社交平台进行撞库，然后控制撞库获取的账户，在网上承接点赞刷量、发布广告等业务牟利，短短两个月的时间获利上百万元。

    - link: https://www.secrss.com/articles/11524

- **丰田** 澳大利亚经销商遭到网络攻击，公司发言人表示黑客没有访问私人员工或客户的数据

    - 事件经过:

        公司发言人周四在一份声明中表示，“丰田澳大利亚公司可以证实它已成为网络攻击企图的受害者”。“在这个阶段，我们认为没有访问私人员工或客户数据。”

        该发言人表示，该公司正在与国际网络安全专家合作，尽快让其系统恢复正常运行。
        “我们对造成的不便深表歉意，并感谢客户的耐心等待。”

    - link: https://www.theguardian.com/business/2019/feb/21/toyota-australia-says-no-customer-data-taken-in-attempted-cyber-attack

    - link: https://www.toyota.com.au/news/toyota-australia-statement-re-attempted-cyber-attack

- **CafePress** 遭遇数据泄露

    - 泄露内容: 电子邮件地址，姓名，密码，电话号码，物理地址

    - 事件经过: 据 HIBP 称，CafePress 于2019年2月遭到黑客入侵，并公开了 23,205,290 名用户的个人信息。此外公开数据包括电子邮件地址，名称，密码，电话号码和物理地址。

    - link: https://securityaffairs.co/wordpress/89495/data-breach/cafepress-data-breach.html

    - link: https://www.bleepingcomputer.com/news/security/cafepress-data-breach-exposes-personal-info-of-23-million-users/

    - link: https://haveibeenpwned.com/PwnedWebsites#CafePress

### 1月
- **德国政界** 数百德国政客个人数据泄露

    - 影响对象: 除极右翼民主党以外的所有其他政党，其中还包括一些名人和记者。

    - 泄露内容: 电子邮件地址、手机号码、身份证照片以及相当一部分聊天记录

    - 事件经过: 据 BBC、路透社等多家海外媒体报道，所有泄露的信息都是通过一个名为“G0d”的 Twitter 帐户在之前的数周内放出的，账户信息显示，该账户目前有粉丝约17000人，地址位于汉堡，并使用了“安全研究”、“艺术家”、“讽刺与反讽”等标签形容自己。

- **华硕** 内网密码在 GitHub 上泄露

    - 泄露内容: 企业内网密码

    - 事件经过: 北京时间3月28日早间消息，据美国科技媒体 TechCrunch 报道，一名信息安全研究员两个月前向华硕发出警告称，有华硕员工在 GitHub 代码库中错误地发布了密码。这些密码可以被用于访问该公司的企业内网。其中一个密码出现在一名员工分享的代码库中。通过该密码，研究员可以访问内部开发者和工程师使用的电子邮件帐号，从而与计算机的使用者分享夜间构建的应用、驱动和工具。有问题的代码库来自华硕的一名工程师，他将电子邮件帐号密码公开已有至少一年时间。目前，尽管 GitHub 帐号仍然存在，但这个代码库已被清理。

    - link: http://hackernews.cc/archives/25173

---

## 2018🤷‍

### 12月
- **Quora** 1亿用户数据因为第三方黑客恶意攻击而遭到泄露

    - 影响人数: 1亿

    - 影响对象: Quora 用户

    - 泄露内容: 姓名、电子邮箱、加密密码、个人资料

    - 大致时间: 公开于2018年12月3日

    - 事件经过: 12月3日，美国知名问答社区 Quora 发公告称，1亿用户数据因为第三方黑客恶意攻击而遭到泄露，其中包括用户的邮箱、姓名和被加密的密码，以及他们在网站上分享的内容。

    - link: http://hackernews.cc/archives/24547

- **Roll20** 遭遇数据泄露

    - 影响人数: 400万

    - 泄露内容: 电子邮件和IP地址、姓名、密码、信用卡的最后4位数字

    - 事件经过: 2018年12月，桌面角色扮演游戏网站 Roll20 遭遇数据泄露。近400万客户受到此次攻击的影响，他们的电子邮件和 IP 地址、姓名、密码的 bcrypt 散列和信用卡的最后4位数字都被暴露。

    - link: https://haveibeenpwned.com/PwnedWebsites#Roll20

### 11月
- **Amazon** 部分用户信息被泄露: 包括姓名和邮件地址

    - 影响人数: 不详

    - 影响对象: Amazon 用户

    - 泄露内容: 姓名、邮件地址

    - 事件经过: 北京时间11月22日早间消息，据美国财经媒体 CNBC 报道，亚马逊向给用户发邮件称，由于出现技术问题，一些用户的姓名和邮件地址被泄露。目前已经有一些人在网上发布他们收到的邮件截图。这些邮件中说，用户没有必要因此次事故而修改密码。但 CNBC 指出，有了名字和邮件地址，黑客仍然可以借此重设用户帐号，或利用邮件发起“钓鱼攻击”。

    - link: http://hackernews.cc/archives/24486

### 10月
- **国泰航空** 数据泄露，940万乘客受影响

    - 影响人数: 940万

    - 影响对象: 国泰航空乘客

    - 泄露内容: 乘客姓名；国籍；出生日期；电话号码；电邮地址；地址；护照号码；身份证号码；飞行常客计划的会员号码；顾客服务备注；及过往的飞行记录信息。

    - 事情经过: 根据国泰航空的说法，他们于今年3月在系统中发现可疑活动后立即与网络安全公司合作进行调查，确定攻击者如何获得系统访问权限以及如何修复漏洞。调查进行至5月，国泰航空发现攻击者能够访问包含多达940万条乘客个人数据的系统。

    - link: https://news.cathaypacific.com/%E5%9C%8B%E6%B3%B0%E8%88%AA%E7%A9%BA%E5%85%AC%E4%BD%88%E6%B6%89%E5%8F%8A%E4%B9%98%E5%AE%A2%E8%B3%87%E6%96%99%E7%9A%84%E8%B3%87%E6%96%99%E5%AE%89%E5%85%A8%E4%BA%8B%E4%BB%B6#

    - link: https://www.solidot.org/story?sid=58359

### 9月
- **喜达屋酒店** 5亿条个人信息泄露

    - 影响人数: 5亿

    - 影响对象: 喜达屋酒店消费者

    - 泄露内容: 姓名、电子邮箱、邮寄地址、电话号码、护照号码、帐户信息、出生日期、性别、旅行信息、住宿信息、信用卡信息等。

    - 大致时间: 2018年9月10日，但泄露真正发生时间可追溯到2014年。

    - 事件经过: 与很多其它官方违规声明一样，这家万豪旗下的连锁酒店发布了一份称其服务器遭受“未授权访问”的声明，一个顾客预订数据库被黑客入侵，可能有约5亿顾客的信息泄露。该消息公布后，万豪国际酒店股价在当天盘前交易中一度下跌逾 5%。

### 8月
- **华住酒店** 被曝5亿条个人信息泄露在暗网兜售
    - 影响人数: 5亿

    - 泄露内容: 身份证号、手机号

    - 事件经过: 今年8月份，网曝华住酒店集团旗下酒店用户信息在“暗网”售卖，售卖者称数据已在8月14日脱库。身份证号、手机号，一应俱全，共涉及5亿条公民信息。此次泄露的全部数据信息被卖家打包以8比特币出售（当时约合人民币38万元）。卖家还称，以上数据信息的截止时间为2018年8月14日。

- **Newegg** 5000万信用卡账号支付信息泄露

    - 影响人数: 5000万

    - 影响对象: Newegg在线消费者

    - 泄露内容: 信用卡账号

    - 大致时间: 2018年8月14日-9月18日

    - 事件经过: 网络犯罪团伙 Magecart 在 Newegg 网站上注入了信用卡略读代码。每当消费者在线购买东西时，支付信息会直接发送到 Magecart 的 C＆C（命令和控制服务器）上。

### 7月
- **Stronghold Kingdoms** 遭遇数据泄露

    - 影响人数: 518万

    - 泄露内容: 电子邮件地址，用户名，密码

    - 事件经过: 2018年7月，大型多人在线游戏 Stronghold Kingdoms 遭遇数据泄露。这次入侵暴露了近520万个帐户，电子邮件地址，用户名和密码存储为 salted SHA-1 哈希值。

- **Animoto** 遭遇数据泄露

    - 泄露内容: 出生日期，电子邮件地址，地理位置，姓名，密码

    - 事件经过: 2018年7月，基于云计算的视频制作服务 Animoto 遭遇数据泄露。这次入侵暴露了2200万个独特的电子邮件地址，以及姓名、出生日期、原产国和加盐的密码哈希。

    - link: https://haveibeenpwned.com/PwnedWebsites#Animoto

- **Netlog** 遭遇数据泄露

    - 影响人数: 4903万

    - 泄露内容: 电子邮件地址，密码

    - 事件经过: 2018年7月，比利时社交网站 Netlog 发现可追溯到2012年11月的系统数据遭到窃取（PDF）。 尽管该服务于2015年停止使用，但数据泄露仍然影响了4900万用户，其电子邮件地址和纯文本密码被暴露。

    - link: https://haveibeenpwned.com/PwnedWebsites#Netlog

- **汽车供应商 Level One** 数据泄露导致一百多家汽车厂商机密数据曝光

    - 影响对象: 在全球 100 多家合作伙伴

    - 泄露内容: 与 Level One 合作的多家汽车制造厂商（包括特斯拉、通用、福特、大众等）的装配线、工厂原理图、保密协议；机器人的配置、规格、动画；蓝图；ID 凭证和VPN 访问请求表；客户联系信息等。涉及厂商超过 100 家。

    - 事件经过: 据多家外媒报道，7 月初，来自 UpGuard 安全团队的研究员 Chris Vickery 在网上发现了汽车供应商 Level One 的不安全数据库，数据库包括将近 47000 份文件，涵盖汽车制造厂商近十年的详细蓝图、工厂原理图、客户材料（如合同、发票、工作计划等），以及各种保密协议文件，甚至连员工的驾驶证和护照扫描件等隐私信息也包含在内。整个数据库的数据总量达 157 GB。Chris Vickery 表示，通过 Level One 的文件传输协议 rsync，可以不需要密码，直接访问他发现的这个数据库。

- **500px**

    - 影响人数: 1486万

    - 泄露内容: 出生日期，电子邮件地址，性别，地理位置，姓名，密码，用户名

    - 大致时间: 2018年7月5日

    - 事件经过: In mid-2018, the online photography community 500px suffered a data breach. The incident exposed almost 15 million unique email addresses alongside names, usernames, genders, dates of birth and either an MD5 or bcrypt password hash. In 2019, the data appeared listed for sale on a dark web marketplace (along with several other large breaches) and subsequently began circulating more broadly. The data was provided to HIBP by a source who requested it to be attributed to "BenjaminBlue@exploit.im".

    - link: https://haveibeenpwned.com/PwnedWebsites#500px

### 6月
- **SHEIN** 遭遇数据泄露

    - 影响人数: 3908万

    - 泄露内容: 电子邮件地址，密码

    - 事件经过: 2018年6月，在线时尚零售商 SHEIN 遭遇数据泄露。该公司在8月份的8月后发现了这次违规事件，然后又在另一个月后披露了该事件。在 MD5 密码哈希中，共发现了3900万个唯一的电子邮件地址。

    - link: https://haveibeenpwned.com/PwnedWebsites#SHEIN

- **A站** 官方宣传近千万条用户数据外泄(把用户数报高一点好让快手爸爸多给钱?)

    - 影响人数: 官方宣传近千万条用户

    - 事件经过: 北京时间 6 月 13 日凌晨，AcFun 发布公告称网站遭遇黑客攻击，近千万条用户数据外泄。呼吁 2017 年 7 月 7 日之后从未登陆过的用户以及密码强度低的用户及时更改密码。如果在其他网站使用与 A 站相同的密码，也应及时修改。

- **Exactis** 3.4亿人口总数据泄露

    - 影响人数: 3.4亿（2.3亿消费者数据，1.1亿企业数据）

    - 影响对象: 互联网个人和企业用户

    - 泄露内容: 数据种类超过400类，包括电话号码、电子邮箱、邮寄地址、兴趣爱好、年龄、宗教信仰、宠物情况等。

    - 事件经过: 美国市场营销公司 Exactis 采集了大约3.4亿条记录，大小约2TB，可能涵盖了2.3亿人的个人数据，几乎是全美的上网人口。Exactis 此次的信息泄露并不是黑客撞库引起或者其它恶意攻击，而是他们自己的服务器没有防火墙加密，直接暴露在公共的数据库查找范围内。

- **MyHeritage** 9200万用户数据泄露

    - 影响人数: 9200万

    - 影响对象: MyHeritage用户

    - 泄露内容: 邮箱地址、加密密码

    - 事件经过: 网络安全研究人员于2018年6月对 MyHeritage 发出安全警告，发现外部服务器上存有敏感的 MyHeritage 信息。该公司确认信息真实性后立即发布通告，提醒用户立即更改密码，所有在2017年10月26日之前注册的帐户都存在泄露风险。

### 5月
- **Linux Forums** 遭遇数据泄露，导致276k电子邮件地址泄露。

    - 影响人数: 27万

    - 影响对象: Linux Forums用户

    - 泄露内容: Email addresses, IP addresses, Passwords, Usernames

    - 事件经过: In May 2018, the Linux Forums website suffered a data breach which resulted in the disclosure of 276k unique email addresses. Running on an old version of vBulletin, the breach also disclosed usernames, IP addresses and salted MD5 password hashes. Linux Forums did not respond to multiple attempts to contact them about the breach.

    - link: https://haveibeenpwned.com/PwnedWebsites#LinuxForums

### 4月
- **Panera** 3700万用户数据泄露

    - 影响人数: 3700万

    - 影响对象: Panera用户

    - 泄露内容: 姓名、邮箱、地址、生日、信用卡账号后四位

- **TrueMove H** 遭遇数据泄露

    - 影响人数: 46000人

    - 泄露内容: 驾驶执照和护照

    - 事件经过: 运营商向在线客户公开存储在亚马逊 AWS S3 存储桶中的个人数据。泄露的数据还包括身份证件的扫描，数据一直保留至4月12日，当时该公司限制访问。
    安全研究人员 Niall Merrigan 发现了大量数据，试图将此问题告知 TrueMove H，但运营商没有回应。Merrigan 透露，该 AWS 存储桶包含总计 32GB 的 46,000 条记录。

- **Chegg** 遭遇数据泄露

    - 影响人数:3972万

    - 泄露内容: 电子邮件地址、姓名、密码、用户名

    - 事件经过: 2018年4月，教科书租赁服务 Chegg 遭遇数据泄露，影响了 4000 万用户。 暴露的数据包括存储为未加盐的 MD5 哈希值的电子邮件地址，用户名，名称和密码。

    - link: https://haveibeenpwned.com/PwnedWebsites#Chegg

### 3月
- **Facebook** 用户数据泄露，影响美国大选(小扎你看你就像个外星人)

    - 影响人数: 8700万

    - 影响对象: Facebook用户

    - 泄露内容: 个人资料、政治倾向、好友信息、私人消息

    - 大致时间: 2018年3月

    - 事件经过:

        事件起源于 Facebook 与剑桥分析公司的合作，剑桥分析公司为了学术研究，在脸书上创建了一个应用预测用户性格喜好的 APP 用来测试，可是剑桥分析公司不仅收集了用户的测试结果，还在未经允许地情况下顺道收集了 5000 万用户在 Facebook 上的个人信息。

        剑桥分析公司获得了 5000 万活跃用户数据后，建立起用户画像，通过计算机对每个用户的兴趣爱好、性格和行为特点进行精确分析，预测他们的政治倾向。然后定向向用户推送新闻，借助 Facebook 的广告投放系统，影响用户的投票行为。于是，Facebook 对美国大选产生了难以推脱的影响。

### 2月
- **MyFitnessPal** 1.5亿用户数据泄露

    - 影响人数: 1.5亿

    - 影响对象: MyFitnessPal用户

    - 泄露内容: 姓名、电子邮箱、加密密码

    - 大致时间: 2018年2月下旬

    - 事件经过: 美国著名运动装备品牌 Under Armour 称有 1.5 亿 MyFitnessPal 用户数据被泄露了，MyFitnessPal 是一款在苹果和谷歌应用商店中很受欢迎的应用，跟踪用户每天消耗的卡路里、设置运动目标、集成来自其它运动设备的数据，还可以分享运动成果到类似 Facebook 这样的社交平台上。此次关于用户数据泄露的声明使得该公司的股票价格盘后下跌了 2.4%。

---

## 2017🙎‍
### 12月
- **piZap** 遭遇数据泄露

    - 影响人数: 4181万

    - 泄露内容: 电子邮件地址，性别，地理位置，姓名，密码，社交媒体资料，用户名，网站活动

    - 事件经过: 2017年12月左右，在线图片编辑网站 piZap 遭遇数据泄露。 这些数据后来在一个黑暗的网络市场上出售，并在2019年2月发布了一系列其他数据泄露事件。总共有4200万个独特的电子邮件地址、姓名、性别和到 Facebook 个人资料的链接被泄露。当在不使用 Facebook 进行身份验证的情况下直接在 piZap 上创建帐户时，存储为 SHA-1 散列的密码也会暴露出来。

    - link: https://haveibeenpwned.com/PwnedWebsites#piZap

### 10月
- **Disqus** 宣布他们遭受了数据泄露

    - 影响人数: 17,551,044

    - 泄露内容: Email addresses, Passwords, Usernames

    - 事件经过: In October 2017, the blog commenting service Disqus announced they'd suffered a data breach. The breach dated back to July 2012 but wasn't identified until years later when the data finally surfaced. The breach contained over 17.5 million unique email addresses and usernames. Users who created logins on Disqus had salted SHA1 hashes of passwords whilst users who logged in via social providers only had references to those accounts.

    - link: https://haveibeenpwned.com/PwnedWebsites#Disqus

### 9月
- **Equifax** 一亿四千三百万美国人数据泄露

    - 影响人数: 一亿四千三百万

    - 影响对象: 基本上包括了美国的每一个成年人

    - 泄露内容: 姓名、社会保险号码、生日、地址，驾照号码，信用卡号码，信用报告纠纷相关文件。
    - 事件经过: 2017年9月 Equifax 发现5月至7月期间遭到黑客攻击导致1.43亿用户的个人信息遭到泄露将近一半美国人的隐私信息暴露在风险中包括姓名、社安号美国身份证号、地址、驾照号、社保账号等还包括20.9万人的信用卡号码18.2万人的个人税收信用文件是当时有史以来规模最大、破坏性最强的数据泄露事件之一。Equifax 股价在事件公布一天内暴跌近14%两周内下跌了31%且面临 4.39 亿美元的法律、补救、保险和调查成本。Equifax 的 CEO、CSO 首席安全官、CIO 首席信息官在事发后立即宣布退休。

    - 大致时间: 公开于2018年12月3日

### 8月
- **Aadhaar印度国家身份认证系统** 11亿用户数据泄露(印度国家身份认证系统将公民信息卖给了乡村企业家?)

    - 影响对象: 印度公民

    - 泄露内容: Aadhaar 号码、姓名、电子邮箱、住址、电话号码以及照片

    - 大致时间: 2017年8月—2018年1月

    - 事件经过: 2018年1月4日，印度乡村企业家 Bharat Bhushan Gupta爆料说，有人在移动社交工具 WhatsApp 上向他推销 Aadhaar 数据库，购买之后，Aadhaar 数据库确实为他提供了大量意想不到的用户信息。

- **Coinmama** 泄露超过 479k 用户数据

    - 泄露内容: 电子邮件地址，用户名和密码

    - 事件经过: 在 2017 年八月，加密硬币经纪服务 Coinmama 遭受了超过 479k 用户数据泄露。 该缺口是在2019年2月发现了暴露的数据，包括存储为 MD5 哈希 WordPress 的电子邮件地址，用户名和密码。

    - link: https://haveibeenpwned.com/PwnedWebsites#Coinmama

---

## 2016🙇‍

### 12月
- **优酷** 遭遇数据泄露，暴露了9200万个唯一用户帐户和相应的MD5密码散列

    - 影响人数: 918万

    - 影响对象: 优酷用户

    - 泄露内容: Email addresses, Passwords

    - link: https://haveibeenpwned.com/PwnedWebsites#Youku

- **Uber** 被黑客盗取用户信息

    - 影响人数: 5760万

    - 影响对象: 用户和司机

    - 泄露内容: 电话号码电子邮箱、姓名,司机的驾照号

    - 事件经过: 2016 年底黑客通过窃取 Uber 公司的 AWS 实例凭证获得了数千万 Uber 用户和司机的个人数据。5700 万人的个人身份信息被窃取包括电话号码电子邮箱、姓名等此外 60.7 万名司机的驾照号被盗。最终 Uber 支付了 1.48 亿美元的法律诉讼和解费。

- **Yahoo!** 两起数据泄露事件

    - 影响人数: 5亿、10亿

    - 影响对象: Yahoo用户

    - 泄露内容: 用户名、电子邮箱、电话、生日、密码以及安全问答等

    - 事件经过: 2016年 Yahoo! 公布了2起数据泄露事件——一起是在9月这一事件危害5亿以上的账户持有人另一起是在12月这一事件影响了超过10亿的账户持有人。泄露的信息于2014年至2016年12月期间收集黑客窃取的信息包括用户名、电子邮箱、电话、生日、密码以及安全问答等。Yahoo! 在事后补救和法律费用上花费超过9500万美元因未及时向投资者披露黑客行为被额外罚款 3500 万美元。由于违规行为 Verizon 收购 Yahoo! 比原报价少了 3.5 亿美元。

### 11月
- **xHamster** 数十万色情账号有消息称黑客正在交易(要命)

    - 影响人数: 377,377

    - 影响对象: xHamster用户

    - 泄露内容: Email addresses, Passwords, Usernames

    - 事件经过: In November 2016, news broke that hackers were trading hundreds of thousands of xHamster porn account details. In total, the data contained almost 380k unique user records including email addresses, usernames and unsalted MD5 password hashes.

    - link: https://haveibeenpwned.com/PwnedWebsites#xHamster

### 9月
- **爱拍** 包含约650万个账户的数据在网上被泄露

    - 影响人数: 649万

    - 影响对象: 爱拍用户

    - 泄露内容: Email addresses, Passwords

    - link: https://haveibeenpwned.com/PwnedWebsites#Aipai

### 8月
- **Epic Games** 252k账户被曝光

    - 影响人数: 25万

    - 影响对象: Epic Games用户

    - 泄露内容: Email addresses, IP addresses, Names, Passwords, Payment histories, Phone numbers, Physical addresses, Usernames, Website activity

    - link: https://haveibeenpwned.com/PwnedWebsites#EpicGames

- **Cross Fire** 俄罗斯游戏论坛被黑客入侵 (战斗民族的枪战梦想?)

    - 影响人数: 1286万

    - 泄露内容: Email addresses, Passwords, Usernames

    - 事件经过: In August 2016, the Russian gaming forum known as Cross Fire (or cfire.mail.ru) was hacked along with a number of other forums on the Russian mail provider, mail.ru. The vBulletin forum contained 12.8 million accounts including usernames, email addresses and passwords stored as salted MD5 hashes.

    - link: https://haveibeenpwned.com/PwnedWebsites#CrossFire

### 7月
- **Clash of Kings** 的论坛遭遇数据泄露

    - 泄露内容: 电子邮件地址，IP 地址，密码，用户名

    - 事件经过: 2016 年 7 月，“国王冲突”游戏论坛遭遇数据泄露，影响了 160 万用户。 受影响的数据包括用户名，IP 和电子邮件地址以及存储为 MD5 哈希值的密码。

    - link: https://haveibeenpwned.com/PwnedWebsites#ClashOfKings

### 3月
- **CD Projekt RED** 论坛遭遇数据泄露

    - 影响人数: 187万

    - 影响对象: CD Projekt RED论坛用户

    - 泄露内容: Email addresses, Passwords, Usernames

    - 事件经过: In March 2016, Polish game developer CD Projekt RED suffered a data breach. The hack of their forum led to the exposure of almost 1.9 million accounts along with usernames, email addresses and salted SHA1 passwords.

    - link: https://haveibeenpwned.com/PwnedWebsites#CDProjektRed

### 2月
- **Linux Mint** 遭到黑客攻击，ISO受到后门的感染

    - 影响人数: 14万

    - 泄露内容: Avatars, Dates of birth, Email addresses, Geographic locations, IP addresses, Passwords, Time zones, Website activity

    - 事件经过: In February 2016, the website for the Linux distro known as Linux Mint was hacked and the ISO infected with a backdoor. The site also ran a phpBB forum which was subsequently put up for sale complete with almost 145k email addresses, passwords and other personal subscriber information.

    - link: https://haveibeenpwned.com/PwnedWebsites#LinuxMint

### 1月
- **EpicNPC** 遭遇数据泄露

    - 泄露内容: 电子邮件地址，IP 地址，密码，用户名

    - 事件经过: 2016 年 1 月，被黑客入侵的账户经销商 EpicNPC 遭遇数据泄露，影响了 40.9 万用户。 受影响的数据包括用户名，IP 和电子邮件地址以及存储为 salted MD5 哈希值的密码。

    - link: https://haveibeenpwned.com/PwnedWebsites#EpicNPC

- **Anime-Planet** 遭遇数据泄露

    - 泄露内容: 出生日期，电子邮件地址，IP 地址，密码，用户名

    - 事件经过: 在大约 2016 年，动漫网站 Anime-Planet 遭遇数据泄露，影响了 369,000 名订阅者。 暴露的数据包括用户名，IP 和电子邮件地址，出生日期和密码存储为无保留的 MD5 哈希值，以及较新的帐户，bcrypt 哈希值。

    - link: https://haveibeenpwned.com/PwnedWebsites#AnimePlanet

- **BitTorrent** 的论坛遭到黑客攻击

    - 影响人数: 3万

    - 影响对象: BitTorrent用户

    - 泄露内容: Email addresses, IP addresses, Passwords, Usernames

    - 事件经过: In January 2016, the forum for the popular torrent software BitTorrent was hacked. The IP.Board based forum stored passwords as weak SHA1 salted hashes and the breached data also included usernames, email and IP addresses.

    - link: https://haveibeenpwned.com/PwnedWebsites#BitTorrent

- **uTorrent** 遭遇数据泄露

    - 影响人数: 39万

    - 泄露内容: Email addresses, Passwords, Usernames

    - 事件经过: In early 2016, the forum for the uTorrent BitTorrent client suffered a data breach which came to light later in the year. The database from the IP.Board based forum contained 395k accounts including usernames, email addresses and MD5 password hashes without a salt.

    - link: https://haveibeenpwned.com/PwnedWebsites#uTorrent

---

## 2015🙃

### 10月
- **Patreon** 被黑，超过16GB资料流落网络

    - 影响对象: Patreon 用户

    - 泄露内容: 注册名称、电子邮件位址、张贴内容、送货地址，以及2014年以前的某些帐单地址，Patreon 网站的原始码

    - 事件经过: 音乐众筹网站 Patreon 遭骇客入侵，并有超过16GB的资料在网路上流窜， Patreon 也已证实此事。Patreon是由音乐家Jack Conte及开发人员Sam Yam在2013年创立的众筹网站，主要是替音乐或影片的作者筹募创作基金。Hunt指出，黑客公布了超过16GB的 Patreon 资料，其中包含14GB的资料库纪录，还有逾230万个电子邮件位址与数百万封的讯息，甚至还有 Patreon 网站的原始码。

    - link: http://www.ijiandao.com/safe/it/16278.html

### 9月
- 内蒙古19万考生信息泄露

    - 影响人数: 19万

    - 影响对象: 内蒙古19万名高考考生

    - 泄露内容: 姓名、身份证号码及其父母姓名、电话

    - 事件经过: 据新华社电内蒙古自治区教育招生考试中心透露，内蒙古19万名高考考生信息近日遭泄露。9月2日上午得知此事后，教育招生考试中心立即组织人员进行研判，并确认网传信息基本属实。随后，该单位立即报警，希望警方进行彻查。这些信息中包括考生的姓名、身份证号码及其父母姓名、电话，名单覆盖了内蒙古自治区的12个盟市，数量最多的地方达4万多条。

    - link: https://news.ifeng.com/a/20150908/44601584_0.shtml

- **TalkTalk** 400万人信息泄漏

    - 影响人数: 400万

    - 影响对象: TalkTalk用户

    - 泄露内容: 姓名、地址、生日、电话号码、电邮地址、账户详细情况、信用卡详细情况等

    - 事件经过: 今年9月英国宽带服务提供商 TalkTalk 表示，该公司网站日前所遭受的网络攻击可能导致其400多万客户的个人数据被盗，这可能是英国史上最大规模的数据泄漏事件之一。该公司表示很客户的姓名、地址、生日、电话号码、电邮地址、账户详细情况、信用卡详细情况等数据很有可能都被窃取了。这是 TalkTalk 今年第三次遭受网络攻击，计算机安全专家格雷汉姆·克鲁利(Graham Cluley)指出: “他们的品牌将受损，他们的客户可能已经忍无可忍了。”

    - link: http://news.mydrivers.com/1/453/453003.htm

### 8月
- **大麦网** 600多万用户账号密码泄露 数据已被售卖

    - 影响人数: 600万

    - 影响对象: 大麦网用户

    - 泄露内容: 用户注册信息数据库

    - 事件经过: 8月27日，乌云漏洞报告平台发布报告显示，线上票务营销平台大麦网再次被发现存在安全漏洞，600余万用户账户密码遭到泄露。起初发现有大麦网用户数据库在黑产论坛被公开售卖，于是对泄露的用户数据进行验证，发现相邻账号的用户ID也是连续的，并均可登录。因此，丛技术的角度可以初步证明本次大麦网的数据泄露有被拖库嫌疑(网站用户注册信息数据库被黑客窃取)。

    - link: http://tech.sina.com.cn/i/2015-08-27/doc-ifxhkafa9342416.shtml

### 2月
- **Uber** 5万名优步司机信息遭泄露

    - 影响人数: 5万

    - 影响对象: 优步司机

    - 泄露内容: 司机的个人信息

    - 事件经过: 2月28日，大约5万名优步(Uber)司机的个人信息被不知名的第三方人士获取，成为该公司遭遇的最大规模的数据泄露事件。去年9月Uber系统中出现一个漏洞，能让外人在未经授权的情况下，获取部分司机的姓名和驾照号码。虽然Uber声称已堵上这一漏洞，但随后的调查显示，去年5月，相关数据曾遭遇“一次未授权的访问“。

    - link: http://tech.huanqiu.com/original/2015-02/5777913.html

- **Slack** 遭黑客攻击

    - 泄露内容: 用户名、电子邮箱地址、加密的密码，以及用户选择添加到帐号的其他个人信息（如手机号码、Skype ID 等）

    - 事件经过: 大概在今年 2 月份的时候，黑客对 Slack 中央数据库进行了持续四天的攻击。未经授权的用户可以访问其基础设施，包括包含散列密码的数据库。攻击者还注入了一个脚本，当用户登录到他们的工作区时，这些脚本将以纯文本形式捕获密码。

    - link: https://slackhq.com/the-regrettable-reason-why-sso-users-have-to-be-forcibly-signed-out-on-mobile

    - link: https://www.bleepingcomputer.com/news/security/slack-resets-account-passwords-compromised-during-2015-hack/

### 1月
- **机锋论坛** 包括用户名、邮箱、加密密码的2300万用户信息泄漏

    - 影响人数: 2300万

    - 影响对象: 机锋用户

    - 泄露内容: 用户名、注册邮箱、加密后的密码等信息

    - 事件经过: 机锋科技旗下机锋论坛被曝出存在高危漏洞，多达2300万用户的信息遭遇安全威胁。这也成为2015年国内第一起网络信息泄露事件。据知情人士称，机锋论坛泄露的2300万用户数据包括用户名、注册邮箱、加密后的密码等信息，由于机构数据库对用户密码仅使用了简单的MD5（计算机安全领域广泛使用的一种散列函数）加密，黑客能够快速破解出绝大部分明文密码。

    - link: http://tech.sina.com.cn/it/2015-01-06/01199932312.shtml

---

## 2014🙅‍

### 12月
- **12306**大量用户资料泄露

    - 影响人数: 13万

    - 影响对象: 12306用户

    - 泄露内容: 用户帐号、明文密码、身份证邮箱等信息

    - 事件经过: 12月25日，国内漏洞报告平台乌云官网爆出，大量12306用户数据在互联网疯传包括用户帐号、明文密码、身份证邮箱等信息。关于此次12306用户数据泄露事件，国内某安全研究团队方面验证了该消息的准确性，并获取到了该文中提到的样本数据，文件标题为《12306 邮箱-密码-姓名-身份证-手机(售后群: 31109xxxx).txt》，共计131653条记录、文件大小14M。随机抽取了一批帐号(约50个)均成功登陆12306，证明了该批数据是准确的，对于里面出现的明文用户密码，该团队初步推测是利用现有用户数据进行“撞库”。针对用户信息泄露一事，12306官方网站随后发布公告称，经过调查，此次泄露信息全部含有用户的明文密码，并称12306网站数据库所有用户密码均为多次加密的非明文转换码，同时暗示用户的明文密码为第三方抢票软件泄漏。

    - link: https://www.williamlong.info/archives/4089.html

### 11月
- **Warframe**

    - 影响人数: 81万

    - 影响对象: Warframe论坛玩家

    - 泄露内容: Email addresses, Usernames, Website activity

    - 事件经过: In November 2014, the online game Warframe was hacked and 819k unique email addresses were exposed. Allegedly due to a SQL injection flaw in Drupal, the attack exposed usernames, email addresses and data in a "pass" column which adheres to the salted SHA12 password hashing pattern used by Drupal 7. Digital Extremes (the developers of Warframe), asserts the salted hashes are of "alias names" rather than passwords.

    - link: https://haveibeenpwned.com/PwnedWebsites#Warframe

### 9月
- **Yandex** 的大量账户泄露的消息被曝光。

    - 影响人数: 118万

    - 泄露内容: Email addresses, Passwords

    - 事件经过: In September 2014, news broke of a massive leak of accounts from Yandex, the Russian search engine giants who also provides email services. The purported million "breached" accounts were disclosed at the same time as nearly 5M mail.ru accounts with both companies claiming the credentials were acquired via phishing scams rather than being obtained as a result of direct attacks against their services.

    - link: https://haveibeenpwned.com/PwnedWebsites#Yandex

### 5月
- **Avast** 论坛被黑，423k会员数据被曝光

    - 影响人数: 42万

    - 影响对象: Avast论坛用户

    - 泄露内容: Email addresses, Passwords, Usernames

    - link: https://haveibeenpwned.com/PwnedWebsites#Avast

- **小米论坛** 用户数据遭泄漏

    - 影响人数: 800万

    - 影响对象: 小米论坛用户

    - 泄露内容: 用户名、密码、邮箱、注册IP以及密码盐

    据国内安全问题反馈平台乌云网昨晚公布信息显示，小米论坛存在用户资料泄露，涉及800万小米论坛注册用户，疑似小米手机论坛的用户数据库已经在黑客界传播，小米用户需要即时修改密码。乌云网称，泄漏的数据包含用户名、密码、邮箱、注册IP以及密码盐（salt），由于小米账户的特殊性（云存储），如果帐号密码被破解，很可能影响到用户的个人数据安全，比如，通讯录、短信、照片、GPS位置信息甚至远程擦除手机数据（格式化）。

    - link: https://www.williamlong.info/archives/3853.html

### 1月
- **Snapchat** 暴露了460万个用户名和电话号码

    - 影响人数: 460万

    - 泄露内容: Geographic locations, Phone numbers, Usernames

    - 事件经过: In January 2014 just one week after Gibson Security detailed vulnerabilities in the service, Snapchat had 4.6 million usernames and phone number exposed. The attack involved brute force enumeration of a large number of phone numbers against the Snapchat API in what appears to be a response to Snapchat's assertion that such an attack was "theoretical". Consequently, the breach enabled individual usernames (which are often used across other services) to be resolved to phone numbers which users usually wish to keep private.s

    - link: https://haveibeenpwned.com/PwnedWebsites#Snapchat

---

## 2013😢

### 10月
- **Adobe** 1.53亿账号泄露

    - 影响人数: 1.53亿

    - 影响对象: Adobe用户

    - 泄露内容: Email addresses, Password hints, Passwords, Usernames

    - link: https://haveibeenpwned.com/PwnedWebsites#Adobe

### 9月
- **imgur** 遭遇数据泄露

    - 影响人数: 174万

    - 泄露内容: Email addresses, Passwords

    - 事件经过: In September 2013, the online image sharing community imgur suffered a data breach. A selection of the data containing 1.7 million email addresses and passwords surfaced more than 4 years later in November 2017. Although imgur stored passwords as SHA-256 hashes, the data in the breach contained plain text passwords suggesting that many of the original hashes had been cracked. imgur advises that they rolled over to bcrypt hashes in 2016.

    - link: https://haveibeenpwned.com/PwnedWebsites#imgur

### 2月
- **tumblr** 遭遇数据泄露，导致超过6500万个账户被曝光。

    - 影响人数: 6546万

    - 泄露内容: Email addresses, Passwords

    - 事件经过: In early 2013, tumblr suffered a data breach which resulted in the exposure of over 65 million accounts. The data was later put up for sale on a dark market website and included email addresses and passwords stored as salted SHA1 hashes.

    - link: https://haveibeenpwned.com/PwnedWebsites#Tumblr

## 2012👀

### 8月
- 疑似 **小米论坛** 用户数据泄露

    - 影响人数: 708万

    - 泄露内容: 电子邮件地址，IP地址，密码，用户名

    - 事件经过: 2012年8月，小米用户论坛网站遭遇数据泄露。总共有700万个电子邮件地址被入侵，尽管其中很大一部分是 bbs_ml_as_uid.xiaomi.com 域中的数字别名。 用户名、IP 地址和存储为加盐 MD5 哈希的密码也被暴露。

    - link: https://haveibeenpwned.com/PwnedWebsites#Xiaomi

### 7月
- **Dropbox** 遭遇了数据泄露，暴露了数千万客户的存储凭据。

    - 影响人数: 6864万

    - 泄露内容: Email addresses, Passwords

    - 事件经过: In mid-2012, Dropbox suffered a data breach which exposed the stored credentials of tens of millions of their customers. In August 2016, they forced password resets for customers they believed may be at risk. A large volume of data totalling over 68 million records was subsequently traded online and included email addresses and salted hashes of passwords (half of them SHA1, half of them bcrypt).

    - link: https://haveibeenpwned.com/PwnedWebsites#Dropbox

### 5月
- **LinkedIn** 遭遇了数据泄露

    - 影响人数: 1.6亿

    - 泄露内容: Email addresses, Passwords

    - 事件经过: 2016年一名俄罗斯黑客 Peace 在暗网出售 LinkedIn 的用户资料总资料多达1.67亿笔当中达1.17亿笔包含了账号密码售价为5个比特币当时约合2200美元。黑客 Peace 表示这些资料源自2012年的一次攻击,当时 Peace 就黑掉了 LinkedIn 并曾在网上出售 LinkedIn 超过600万条的账户信息。

    - link: https://haveibeenpwned.com/PwnedWebsites#LinkedIn

### 1月
- **VK** 遭到黑客攻击，近1亿个账户被曝光。

    - 影响人数: 9333万

    - 泄露内容: Email addresses, Names, Passwords, Phone numbers

    - 事件经过: In approximately 2012, the Russian social media site known as VK was hacked and almost 100 million accounts were exposed. The data emerged in June 2016 where it was being sold via a dark market website and included names, phone numbers email addresses and plain text passwords.

    - link: https://haveibeenpwned.com/PwnedWebsites#VK

## 2011🤔

### 12月
- 2011年底，中国发生的一系列数据泄露事件影响了1亿用户，其中包括来自 **17173游戏网站** 的750万用户。

    - 影响人数: 750万

    - 影响对象: 17173用户

    - 泄露内容: Email addresses, Passwords, Usernames

    - link: https://haveibeenpwned.com/PwnedWebsites#17173

- **CSDN** 用户数据库泄露事件

    - 影响人数: 600万

    - 影响对象: CSDN用户

    - 泄露内容: Email addresses, Passwords, Usernames

    - 事件经过: 2011年12月21日，黑客在网上公开了知名程序员网站 CSDN 的用户数据库，高达600多万个明文的注册邮箱账号和密码遭到曝光和外泄，成为中国互联网历史上一次具有深远意义的网络安全事故。

    - link: https://www.williamlong.info/archives/2933.html

- **天涯社区** 4000万用户资料泄露

    - 影响人数: 4000万

    - 影响对象: 天涯用户

    - 泄露内容: Email addresses, Passwords, Usernames

    - 事件经过: 据天涯网新浪微博上的介绍，由于历史原因，天涯社区早期使用过明文密码，2010年之后改成了加密密码。此次遭到黑客泄漏的用户便是2009年保存的备份数据。该份高达 386M 的泄漏文件“天涯数据.kz”经过下载验证，里面保存了天涯的用户名、密码、邮箱三个数据，根据泄漏的天涯用户名和密码测试，大部分都可以可直接登录到天涯社区。从密码的构成看，泄密的密码很多并非是弱密码，而是8位以上的强密码，因此可以认为天涯的确是以明文方式保存的用户密码。

    - link: https://www.williamlong.info/archives/2939.html

### 6月
- **当当** 遭遇数据泄露

    - 影响人数: 480万

    - 影响对象: 天涯用户

    - 泄露内容: Email addresses

    - 事件经过: In 2011, the Chinese e-commerce site Dangdang suffered a data breach. The incident exposed over 4.8 million unique email addresses which were subsequently traded online over the ensuing years.

    - link: https://haveibeenpwned.com/PwnedWebsites#Dangdang

- **Sony** 多业务被攻击

    - 影响人数: 3.7万

    - 泄露内容: Dates of birth, Email addresses, Genders, Names, Passwords, Phone numbers, Physical addresses, Usernames

    - 事件经过: In 2011, Sony suffered breach after breach after breach — it was a very bad year for them. The breaches spanned various areas of the business ranging from the PlayStation network all the way through to the motion picture arm, Sony Pictures. A SQL Injection vulnerability in sonypictures.com lead to tens of thousands of accounts across multiple systems being exposed complete with plain text passwords.

    - link: https://haveibeenpwned.com/PwnedWebsites#Sony

---

# 供应链攻击
## 2019

### 9月

- **phpstudy** 后门植入事件

    - 事件经过:

        近日，杭州公安报道了一起重大安全事件杭州警方通报打击涉网违法犯罪暨“净网2019”专项行动战果，其中详细说明了一起供应链攻击事件，以下为事件描述：

        2018年12月4日，西湖区公安分局网警大队接报案称，某公司发现公司内有20余台计算机被执行危险命令，疑似远程控制抓取账号密码等计算机数据回传大量敏感信息。据专家组确认，专案组经过缜密侦查，周全布置，于2019年1月4日至5日，兵分四路，分别在海南陵水、四川成都、重庆、广东广州抓获马某、杨某、谭某、周某某等7名犯罪嫌疑人，现场缴获大量涉案物品，并在嫌疑人的电子设备中找到了直接的犯罪证据。据统计，截止抓获时间，犯罪嫌疑人共非法控制计算机67万余台，非法获取账号密码类、聊天数据类、设备码类等数据10万余组。

        据主要犯罪嫌疑人马某供述，其于2016年编写了“后门”，使用黑客手段非法侵入了PhpStudy软件官网，篡改了软件安装包内容。该“后门”无法被杀毒软件扫描删除，并且藏匿于软件某功能性代码中，极难被发现。

        在专案组的侦查过程中，同时发现马某等人通过分析“盗取”的数据，得到了多个境外网站的管理后台账号密码，并通过修改服务器数据的方式实施诈骗，非法牟利共计600余万元。

        目前，官方发通告称，被篡改的软件版本为PhpStudy2016版本中的php5.4版本，如果你是从其它下载站获取的该版本，请自行检查并删除其中的php5.4版本。

    - link: https://www.venustech.com.cn/article/1/10137.html

    - link: https://mp.weixin.qq.com/s/9kqvLPTwVktGmxrgyvUZZA

### 8月

- 恶意程序包 bb-builder 已从 **npm** 存储库中删除

    - 事件经过:

        今天早些时候，npm 从存储库中取出了包“bb-builder”，标记为恶意并具有严重的严重性。
        该通报警告说，安装或运行此软件包的计算机应被视为“完全受损”，因为它为Windows操作系统部署了一个可执行文件，将敏感信息发送到远程服务器。

        “存储在该计算机上的所有机密和密钥应立即从另一台计算机上旋转，” npm建议道。

        npm 收到了来自 ReversingLabs 的联合创始人兼首席软件架构师 Tomislav Pericin 的提示，该公司提供自动静态分析和文件信誉服务。研究人员告诉BleepingComputer 他在扫描整个 npm 存储库以查找危险条目后发现了坏包 - 大约有900万个包转换为35TB的解压缩数据。在基于扫描结果收集和索引的1.6TB元数据中，存在用于 Windows 的可执行代码。

        Pericin 告诉我们，在破坏帐户所有者的凭据后，“bb-builder”已被添加到npm。它一年未被发现。该项目的1.0.1版是第一个包含密码恢复工具的项目。“bb-builder”的每次新迭代都添加了新功能，例如将凭据提交给作者的Web服务器，更改被盗数据的存储位置，修复错误或在发送到远程计算机后删除它。

    - link: https://www.bleepingcomputer.com/news/security/npm-pulls-malicious-package-that-stole-login-passwords/

- 11个 **Ruby** 库被植入挖矿后门代码 删除前已被下载3584次

    - 事件经过: RubyGems 工作人员表示，他们已经移除了 18 个包含后门机制的恶意版本 Ruby 库。自 7 月 8 日以来，其已被下载 3584 次。如剔除同一库的不同版本，则有 11 个 Ruby 库被污染。这些 Ruby 库被软件包存储库的恶意维护者破解并植入了后门代码，可在其他人启用的 Ruby 项目中开展隐匿的加密货币挖掘任务。

    - link: https://www.cnbeta.com/articles/tech/880767.htm

    - link: https://securityaffairs.co/wordpress/90146/hacking/ruby-libraries-backdoor.html

    - link: https://github.com/rubygems/rubygems.org/issues/2097

### 7月
- **npm** 的 **PureScript** 包被污染

    - 事件经过:

        上周，许多开发人员报告了安装程序的几个问题，PureScript 贡献者 Harry Garrood 在其 npm 安装程序中发现了恶意代码。

        通过在命令行中键入 `npm i -g purescript` 启动安装程序，可以安装软件包，这是一个广泛的库集合，每周有 2000 次安装。

        安装程序最初是由日本开发人员 Shinnosuke Watanabe 开发和维护的，后来该项目的维护人员要求他将安装程序的控制权交给他们。开发商接受了请求，但对此决定感到失望。

        @shinnn 声称，攻击者侵入了这些包装机的 npm 账户。好消息是添加的恶意代码的唯一目的是破坏，它会破坏 Purescript npm 安装程序。恶意代码由项目的维护者识别并删除，这些维护者也放弃了 Watanabe 的依赖项。

    - link: https://securityaffairs.co/wordpress/88433/hacking/npm-installer-purescript-compromised.html

- **PyPI** 软件仓库发现三个后门库

    - 事件经过: 安全公司 ReversingLabs 扫描了 Python Package Index (PyPI) 内的一百多万个库，发现三个后门库。这三个库 libpeshnx、libpesh 和 libari 都来自同一位作者、用户名 ruri12，上传时间是 2017 年 11 月，至今接近两年时间。PyPI 团队在收到通知后就移除了这三个库。三个库都没有描述，其用途难以区别。PyPI 的统计数据显示它们每个月有数十次安装。它的后门机制只在库安装到 Linux 系统后激活，后门允许攻击者向安装这三个库的计算机发送和执行指令。三个库中只有 libpeshnx 的后门是活跃的，其余两个恶意功能的代码是空的。

    - link: https://www.zdnet.com/article/malicious-python-libraries-targeting-linux-servers-removed-from-pypi

    - link: https://www.solidot.org/story?sid=61422

- **Canonical** GitHub 账号被入侵，未观察到修改源代码

    - 事件经过: Canonical 在 GitHub 的账号周六被入侵。Ubuntu 安全团队在一份声明中称，入侵者使用该账号创建了库和问题等活动，但没有观察到任何修改源代码的指示。该账号已经移除，Canonical 正在调查入侵的范围，它切断了用于构建和维护 Ubuntu 发行版的 Launchpad 基础设施与 GitHub 之间的连接。安全团队表示它将在事故调查完成之后发布新的更新报告。在入侵期间，攻击者创建了 11 个空的库。

    - link: https://www.zdnet.com/article/canonical-github-account-hacked-ubuntu-source-code-safe/

    - link: https://www.solidot.org/story?sid=61262

- **Rubygem** Strong_password 被劫持

    - 事件经过: 一个流行的 Ruby 密码强度检查程序遭到劫持，攻击者将 strong_password 的版本从 v0.0.6 升级到 v0.0.7，嵌入了一个可编辑的 Pastebin 网址。整合 strong_password 的应用会下载和执行 Pastebin 网址中的代码，这意味着攻击者可以根据需要执行任意代码。strong_password v0.0.6 合法下载量有 3.7 万次，不清楚有多少人下载了恶意版本。 RubyGems 已经将恶意版本移除。

    - link: https://withatwist.dev/strong-password-rubygem-hijacked.html

    - link: https://www.solidot.org/story?sid=61268


- **Pale Moon** 存档服务器被入侵和感染木马

    - 事件经过: Firefox 开源分支 Pale Moon 披露它的存档服务器 archive.palemoon.org 遭到入侵，而入侵时间很有可能发生在两年前，入侵者运行脚本感染了所有存档的 Pale Moon 可执行文件。根据文件修改的时间戳，感染发生在 2017 年 12 月 27 日下午 3 点半，入侵细节已经难以判断，原因是服务器在今年 5 月发生过一次数据损坏故障，导致系统日志丢失。受影响的存档是 Pale Moon 27.6.2 以及之前的版本，如果用户从未在存档服务器下载文件，那么应该没有感染恶意程序，如果下载并执行了修改版的文件，那么最好使用杀毒软件进行一次全盘扫描。

    - link: https://forum.palemoon.org/viewtopic.php?f=17&t=22526

    - link: https://www.solidot.org/story?sid=61333

### 6月
- **Triada** 恶意程序被预装在数百万台设备上

    - 事件经过: Google 本月初披露了一起 Android 供应链攻击，称一家供应商在数百万台设备上预装了 Triada 恶意程序去展示广告。那么 Triada 是谁开发的呢？Google 称供应商使用了野火（Yehuo 或 Blazefire）这个名字。Krebsonsecurity 对这个名字以及相关域名，域名注册邮箱进行了一番跟踪，认为 Triada 与上海野火网络科技有限公司有关，该公司的 CEO 叫楚达。公司域名 blazefire.com 的注册邮箱是 tosaka1027@gmail.com，同一邮箱被用于注册了至少 24 个域名，至少 7 个域名被用于传播 Android 恶意程序，其中两个域名被用于传播 Triada，另外五个被用于传播 Hummer 木马。Brian Krebs 称 Google 拒绝置评，而野火网络则没有回应。

    - link: https://security.googleblog.com/2019/06/pha-family-highlights-triada.html

    - link: https://www.solidot.org/story?sid=61139

## 2018

### 12月
- **驱动人生** 供应链攻击事件

    - 事件经过:

        2018年12月14日下午，腾讯安全御见威胁情报中心监测到一款通过“驱动人生”系列软件升级通道传播的木马突然爆发，仅2个小时受攻击用户就高达10万。该病毒会通过云控下发恶意代码，包括收集用户信息、挖矿等，同时利用“永恒之蓝”高危漏洞进行扩散。腾讯御见威胁情报中心立即对该病毒疫情对外通报，并发布详细的技术分析报告。

        2018年12月14日晚，驱动人生公司接到腾讯御见威胁中心的事件预警后，对该事件高度重视，第一时间与腾讯安全御见威胁情报中心进行联系，告知在木马爆发时，驱动人生公司相关技术人员正在国外旅游团建，因此高度怀疑该事件是驱动人生公司的升级服务器被黑客攻击导致，并请求腾讯企业安全应急响应中心一起协助追查事故原因。同时，驱动人生公司对该事件向深圳警方报警，并对外发布了紧急声明和采取相应的应对措施。

    - link: https://www.freebuf.com/articles/system/192194.html

    - link: https://www.anquanke.com/post/id/169683

### 5月
- **Python** 官方库SSH-Decorator被植入后门

    - 事件经过: 据 Reddit 用户报告，在 Python 库的SSH-Decorator 软件包中发现了窃取用户 SSH 私钥及帐号密码的后门，目前该库已被Python官方移除。SSH-Decorator 为以色列开发人员Uri Goren开发，主要用途为解决用户从Python代码中发起的SSH通信连接。

    - link: https://www.reddit.com/r/Python/comments/8hvzja/backdoor_in_sshdecorator_package/
    - link: http://www.arkteam.net/?p=3601

### 4月
- 攻击者试图在 **Mailparser** 中植入后门

    - 事件经过: 在4月底，NPM包管理团队（Node Package Manager）发现，有攻击者意欲想在流行的JavaScript软件包Mailparser中植入后门。

    - link: http://blog.npmjs.org/post/173526807575/reported-malicious-module-getcookies

## 2017

### 12月
- **Wordpress** Keylogger事件

    - 事件经过:

        Catalin Cimpanu 发现几起针对 WordPress 站点的攻击，主要通过加载恶意脚本进行键盘记录，挖矿或者挂载广告。并且有证据表明，这种攻击从4月份活跃至今。起因是 WordPress 被注入了一个混淆的 js 脚本，从主题的 function.php 文件进行植入。加载的 js 脚本为:
        ```
        <script type='text/javascript' src='hxxp://cloudflare[.]solutions/ajax/libs/reconnecting-websocket/1.0.0/reconnecting-websocket.js'></script>
        <script type='text/javascript' src='hxxp://cloudflare[.]solutions/ajax/libs/cors/cors.js'></script>
        ```
        其中 reconnecting-websocket.js 用作 websocket 通信，cors.js 中包含后门。Cors.js 更改前端页面，释放 javascript 脚本进行输入监听，之后将数据发送给攻击者。

    - link: https://www.bleepingcomputer.com/news/security/keylogger-found-on-nearly-5-500-infected-wordpress-sites/
    - link: https://www.anquanke.com/post/id/89941

### 10月
- **Elmedia Player** 软件攻击事件

    - 事件经过: Elmedia Player 是一款专门为 Mac OS X 打造的免费媒体播放器，通过它可播放和管理 Mac 上的 Flash 影片、电影视频等等。2017年10月19日 ESET 注意到 Elmedia Player 软件的制造商 Eltima 正在其官方网站上发布一个被植入 OSX/Proton 恶意软件的应用程序。ESET 联系 Eltima 之后2017年10月20日 Eltima 官方发布安全公告，公告称旗下 macOS 平台下的 Folx 和 Elmedia Player 两款软件的 DMG 因为官网被入侵而被篡改并被植入了恶意代码，具体影响到了2017年10月19日在官网下载该两款软件的用户。该软件用户数大约在100万左右。这是今年既 XshellGhost 和 CCleaner 之后又一起严重的针对供应链攻击的事件。

    - link: https://www.anquanke.com/post/id/87063

### 9月
- **PyPI** 上发现十余个恶意Python库

    - 事件经过: 2017年，斯洛伐克国家安全办公室发现，在 PyPI 库中存在十余款恶意的 Python 软件包，之后，这些软件包被 Python 官方迅速移除。

    - link: https://www.bleepingcomputer.com/news/security/ten-malicious-libraries-found-on-pypi-python-package-index/

- **CCleaner** 被植入恶意代码

    - 事件经过: 近日，有安全研究团队表示，著名的系统优化工具 CCleaner 被发现植入恶意代码。大量使用该工具的用户恐将面临泄密风险。这是继 Xshell 后门事件后，又一起严重的软件供应链来源攻击事件。据研究人员估算全球2000万用户受到感染，但 CCleaner 官方称只有227万用户受到影响。

    - link: http://it.rising.com.cn/dongtai/18995.html

- **Chrome 插件 User–Agent Switcher** 供应链攻击事件

    - 事件经过: 在此处事件中 User-Agent Switcher 为广大的攻击者提供了一种新型的供应链攻击模式—从大分发机构出发,对交付这一过程进行攻击,作者通过混淆自己的恶意代码进入图片接着在插件运行的时候再从图片中解密出恶意代码进行运行,从而绕过了 Chrome 商店的严格审查机制,成功的堂而皇之的登录到了 Chrome 应用商店,然而对用户而言,官方的应用商店无疑是代表着官方的认证,以及质量和安全,时至今日已经 Chrome 商店的统计数据显示:累计有 458,450 的用户已经安装了该插件,可以看到 Chrome 商店在这之中扮演着重要的角色,交付这一环节上,就让 chrome 成功收录了自己的应用,然后利用 chrome 应用商店这个更为广大的品台吸引到更多的用户进行下载使用,从而造成更大的危害。

    - link: https://www.anquanke.com/post/id/86892

### 8月
- **NetSarang** 旗下多款软件的关键模块被植入了高级后门

    - 事件经过:

        2017年7月17日，NetSarang 公司发布旗下多款产品的新版软件，更新修复多处bug和增强了会话加密能力，用于对抗 CIA 木马“BothanSpy”的密码劫持功能。

        2017年8月7日，NetSarang 与卡巴斯基发布联合声明，声称7月18日发现软件存在安全漏洞被攻击。

        2017年8月15日，NetSarang 与卡巴斯基更新联合声明，发现在香港利用该软件漏洞的案例。

        NetSarang 系列软件的关键网络通信组件 nssock2.dll 被植入了恶意代码，厂商在发布软件时并未发现恶意代码，并给感染组件打上了合法的数字签名随新版软件包一起发布，用户机器一旦启动软件，将会加载组件中的恶意代码，将主机的用户信息通过特定 DGA(域名生成算法)产生的 DNS 域名传送至黑客的远程命令控制服务器，同时黑客的服务器会动态下发任意的恶意代码至用户机器执行。

    - link: https://www.freebuf.com/articles/terminal/144842.html

    - link: https://slab.qq.com/news/tech/1637.html

- **假冒“老毛桃”工具** 推广木马

    - 事件经过: 2017年8月，360安全中心接到多起网友反馈，称电脑中所有浏览器的主页都被篡改，而且强制锁定为 http://dh936.com/?00804 推广页面。据360安全专家分析，这是一款假冒“老毛桃”PE 盘制作工具的推广木马在恶意作祟。下载该制作工具后，其捆绑的“净网管家”软件会释放木马驱动篡改首页。当发现中招者试图安装安全软件时，还会弹出“阻止安装”提示，诱导中招者停止安装。专家进一步分析后发现，该驱动还设置了不少保护措施逃避安全软件查杀，如禁止自身文件和注册表的浏览和读取等。

    - link: http://bobao.360.cn/interref/detail/207.html

- **WireX Android Botnet** 污染 Google Play 应用市场

    - 事件经过:

        2017年8月17日，名为 WireX BotNet 的僵尸网络通过伪装普通安卓应用的方式大量感染安卓设备并发动了较大规模的 DDoS 攻击，此举引起了部分 CDN 提供商的注意，此后来自 Akamai, Cloudflare, Flashpoint, Google, Oracle Dyn, RiskIQ, Team Cymru 等组织联合对该事件进行分析，并于8月28日发布了该事件的安全报告。

        报告发现大约有300种不同的移动应用程序分散在 Google Play 商店中，WireX 引发的 DDoS 事件源自至少7万个独立IP地址，8月17日攻击数据的分析显示，来自100多个国家的设备感染了 WireX BotNet。

    - link: https://blog.cloudflare.com/the-wirex-botnet/?utm_content=buffer9e1c5

    - link:  https://slab.qq.com/news/kuaixun/1641.html

- **Arris** 为AT&T家庭用户定制版调制解调器内置后门事件

    - 事件经过: 2017年8月，安全研究人员发现知名电信设备制造商 Arris 生产的调制解调器存在5个安全漏洞，其中有3个是硬编码后门账号漏洞。攻击者利用三个后门账号均可控制设备，提升至 ROOT 权限、安装新固件，乃至于架设僵尸网络等。有问题的调制解调器型号为 Arris NVG589、Arris NVG599，主要在美国宽带运营商 AT&T 的网络里使用，但在 Arris 官网找不到信息（停产产品？）。Nomotion 研究人员推测，它们可能是专为 AT&T 家庭用户定制的入网设备。研究人员认为易受漏洞攻击调制解调器至少有22万台。

    - link: https://www.4hou.com/info/news/7522.html

### 7月
- **基于域名 bjftzt.cdn.powercdn.com** 的软件升级劫持攻击

    - 事件经过: 360安全卫士在2017年7月5日披露，有多款软件用户密集反映360“误报了软件的升级程序”，但事实上，这些软件的升级程序已经被不法分子恶意替换。这次事件其实是基于域名 bjftzt.cdn.powercdn.com 的一组大规模软件升级劫持事件。用户尝试升级若干知名软件客户端时，运营商将HTTP请求重定向至恶意软件并执行。恶意软件会在表面上正常安装知名软件客户端的同时，另外在后台偷偷下载安装推广其他软件。山东、山西、福建、浙江等多省的软件升级劫持达到空前规模，360安全卫士对此类攻击的单日拦截量突破40万次。

    - link: http://www.mottoin.com/detail/1324.html

### 5月
- **惠普** 笔记本音频驱动内置键盘记录后门事件

    - 事件经过: 2017年5月，来自瑞士安全公司 Modzero 的研究人员在检查 Windows Active Domain 的基础设施时发现惠普音频驱动中存在一个内置键盘记录器监控用户的所有按键输入。研究人员指出，惠普的缺陷代码（CVE-2017-8360）不但会抓取特殊键，而且还会记录每次按键并将其存储在人类可读取的文件中。这个记录文件位于公用文件夹 C:\Users\Public\MicTray.log 中，包含很多敏感信息如用户登录数据和密码，其他用户或第三方应用程序都可访问。因此安装到计算机上的恶意软件甚至是能物理接近计算机的人都能够复制日志文件并访问所有的用户按键、提取敏感数据如银行详情、密码、聊天日志和源代码。2015年，这个按键记录功能以新的诊断功能身份在惠普音频驱动版本1.0.0.46中推出，并自此有近30款惠普计算机都内置有这种功能。

    - link: https://www.anquanke.com/post/id/86085

### 2月
- **百度** 旗下网站暗藏恶意代码,官方回应:外包团队干的,已报案

    - 事件经过: 经火绒安全实验室截获、分析、追踪并验证，当用户从百度旗下的http://www.skycn.net/和 http://soft.hao123.com/这两个网站下载任何软件时，都会被植入恶意代码。该恶意代码进入电脑后，会通过加载驱动等各种手段防止被卸载，进而长期潜伏，并随时可以被“云端”远程操控，用来劫持导航站、电商网站、广告联盟等各种流量。

    - link: https://www.huorong.cn/info/148826116759.html

## 2016

### 10月
- **索尼** 80款监控摄像头被曝存在后门,索尼拒绝回复

    - 事件经过:

        2016年10月，安全公司 SEC Consult 曝出了索尼安防摄像头的后门漏洞，竟然影响了高达80款索尼“IPELA ENGINE”的网络摄像头产品。
        在就在最新固件中，SEC 发现了两大后门——

        1、Hardcoded 密码和 root 账户 学过编程应该知道，Hardcoded 也就是硬编码，并非变量，是写死的固定内容，SEC 开发的工具软件 IoT 侵入者于是便通过穷举法来获取到密码内容。同时，SEC 还发现了隐藏的 root 口令，达到让所有人以超级管理员身份登录。

        2、两个Debugging账户索尼挖的坑还不止于此。索尼为固件修复留了两个 debug 调试账户，一个用户名“primana”密码“primana”，还有一个用户名“debug”密码“popeyeConnection”。debug 账户因为可以远程访问，所以危险系数更高，比如被不法分子用集群服务器攻击。SEC 已经将报告递交索尼，后者也在新固件对上述问题进行了修复。至于为什么要留后门以及到底用来干什么，索尼拒绝回复。

    - link: https://news.mydrivers.com/1/510/510837.htm

<p align="center">
    <img src=".//assets/img/sony.jpg">
</p>

## 2015

### 12月
- **Juniper** VPN 后门事件

    - 事件经过: 2015年12月15日著名网络设备厂商 Juniper 公司发出风险声明，其防火墙、VPN 设备使用的操作系统具有重大安全风险，建议尽快升级相关版本。根据声明，设备的 SSH 登录系统在输入任意用户名的情况下，使用超级密码就可以最高权限登录系统，设备的 VPN 安全通道上传递的数据可以被攻击人解密、篡改和注入。全球上万 NetScreen 设备被攻击。

    - link: https://www.anquanke.com/post/id/83148

### 10月
- **百度** 旗下应用开发 SDK Moplus 被曝其中内含后门

    - 事件经过: 2015年11月百度 moplus SDK 的一个被称为虫洞（Wormhole）的漏洞被漏洞报告平台 wooyun.org 所披露，研究人员发现 Moplus SDK 具有后门功能，但这不一定是由于漏洞或跟漏洞相关，之所以称之为漏洞是基于 Moplus SDK 的访问权限控制以及应该如何限制这种访问的角度。因此，它虽然具有漏洞相关的概念而实际上是一个后门程序，如推送钓鱼网页，插入任意联系人，发送伪造短信，上传本地文件到远程服务器，未经用户授权安装任意应用到 Android 设备。而执行这些行为唯一的要求是该设备首先需要连接互联网。由于 Moplus SDK 已经被集成到众多的 Android 应用程序中，这就意味着有上亿的 Android 用户受到了影响。研究结果还表明，已经有恶意软件在利用 Moplus SDK 的漏洞，它被植入到14000款 app 当中，这些 app 有接近4000个都是由百度出品的。经统计有2846个 app 包含后门库，苹果设备感染量未知。

    - link: https://www.leiphone.com/news/201511/N9FR2E1434teyADU.html

### 9月
- **XcodeGhost** 事件

    - 事件经过: 2015年9月，XcodeGhost 事件爆发，超过4000个不同版本的苹果应用被感染，影响了中国近一亿苹果手机用户。Xcode 是由苹果公司发布的运行在操作系统Mac OS X上的集成开发工具（IDE），是开发OS X 和 iOS 应用程序的最主流工具。2015年9月14日起，一例Xcode非官方版本恶意代码污染事件被披露，多数分析者将这一事件称为“XcodeGhost”。攻击者通过向非官方版本的 Xcode 注入病毒 Xcode Ghost，它的初始传播途径主要是通过非官方下载的 Xcode 传播，通过 CoreService 库文件进行感染。当应用开发者使用带毒的 Xcode 工作时，编译出的 App 都将被注入病毒代码，从而产生众多携带病毒的APP。至少692种 APP 受污染，过亿用户受影响，受影响的包括了微信、滴滴、网易云音乐等著名应用。

    - link: https://unit42.paloaltonetworks.com/novel-malware-xcodeghost-modifies-xcode-infects-apple-ios-apps-and-hits-app-store/

    - link: https://security.tencent.com/index.php/blog/msg/96

- **幽灵推Ghost Push**

    - 事件经过: 2015年8月，酷派大神手机用户在安装官方提供的系统升级包后，手机便被预安装了 MonkeyTest 和 TimeService 等未知软件。截止到9月18日，该类病毒的每日感染量已经扩大到了最高70万台/天，有上万种机型收到了 Ghost Push 的影响，典型的有酷派、三星、MOTO 等等。

    - link: https://www.freebuf.com/articles/terminal/78781.html

### 2月
- **方程式组织** 硬盘固件程序攻击

    - 事件经过: 卡巴斯基安全实验室在2015年2月16日起发布系列报告披露了一个网络攻击组织: “方程式”组织（Equation Group）。该组织拥有一套用于植入恶意代码的超级信息武器库（在卡巴的报告中披露了其中6个），其中包括两个可以对数十种常见品牌的硬盘固件重编程的恶意模块，这可能是该组织掌握的最具特色的攻击武器，同时也是首个已知的能够感染硬盘固件的恶意代码。而通过相关安全公司分析的结论可以看出，在此次硬盘固件程序攻击事件中可以做到如此有针对性（特定目标、行业），部分攻击方式极有可能属于物流链劫持，即在特定目标采购、返修主机或硬盘的过程中修改了硬盘固件。

    - link: https://www.freebuf.com/news/59185.html

## 2014

### 8月
- **磊科(NetCore)** 全系列路由器中的“疑似后门”程序

    - 事件经过: 磊科(NetCore)路由器中内置了一个叫做 IGDMPTD 的程序，按照它的描述应该是 IGD MPT Interface daemon 1.0。该程序会随路由器启动，并在公网上开放端口，攻击者可以执行任意系统命令、上传下载文件，控制路由器。一切的开始源自于今年8月份买了一个磊科(NetCore)家用路由器。随后发现 IGDMPTD，并做了测试工具验证。Google 后发现在今年8月25日，趋势科技的研究员 Tim Yeh 发表文章描述了这个”疑似后门”的IGDMPTD，并报告厂商。随后在今年10月3日 Tim Yeh 再次发表文章，指出磊科官方并未完全删掉这个”后门程序”。

    - link: http://blog.trendmicro.com/trendlabs-security-intelligence/netis-routers-leave-wide-open-backdoor/

    - link: http://blog.trendmicro.com/trendlabs-security-intelligence/netis-router-backdoor-patched-but-not-really/

### 4月
- **Joomla** 插件后门

    - link: https://blog.sucuri.net/2014/04/joomla-plugin-constructor-backdoor.html

### 3月
- **WordPress** 的盗版插件后门程序

    - 事件经过: 2011年，WordPress 团队发现目前在 WordPress 流行的一些插件存在安全隐患，插件被恶意插入后门程序，以便获取用户的数据，主要是用户的管理员密码。这些恶意后台并非是插件作者有意作为，而是第三方的人在破解了插件作者的管理信息之后插入后门信息的。

    - link: https://blog.sucuri.net/2014/03/unmasking-free-premium-wordpress-plugins.html

## 2013

### 12月
- **NetGear** 多款路由器存在后门

    - 事件经过: NetGear 生产的多款路由器存在后门。该后门为厂商设置的超级用户和口令，攻击者可以利用后门，在相邻网络内可获取到路由器的 root 权限，进而植入木马完全控制用户的路由器。后续可发起 dns 劫持攻击。

    - link: https://www.cnvd.org.cn/flaw/show/CNVD-2013-15013

### 10月
- **腾达Tenda** 路由器后门

    - 事件经过: 在友讯科技（D-Link）路由器发现后门之后，安全研究员又在另一家路由器制造商腾达（Tenda）的产品中发现了后门。安全研究人员分析了腾达路由器W302R的最新固件， 发现了名叫 MfgThread 的独立线程，捆绑了7329端口，接收 UDP 数据包，会对含有特殊字符的指令作出反应，这些特殊字符包括了e、1和X——对于e，会返回一个预定义的字符串，基本上是一个 ping 测试；对于 1，它将允许你运执行iwpriv命令， iwpriv 命令可用于配置路由器网络端口；对于X，它给予你root权限，可以执行任何命令。作者认为，这个后门可能最早是在腾达的 W302R 路由器上 实现的，存在于 W330R 路由器和 Medialink 的路由器 MWN-WAPR150N 中。

    - link: http://www.devttys0.com/2013/10/from-china-with-love/

    - link: https://www.freebuf.com/articles/terminal/14425.html

### 6月
- **美国** "棱镜门"事件

    - 事件经过: 棱镜计划（PRISM）是一项由美国国家安全局（NSA）自2007年起开始实施的绝密电子监听计划，该计划的正式名号为“US-984XN”，直接进入美国网际网路公司的中心服务器里挖掘数据、收集情报，包括微软、雅虎、谷歌、苹果等在内的9家国际网络巨头皆参与其中。其中以思科公司为代表的科技巨头利用其占有的市场优势在科技产品中隐藏“后门”，协助美国政府对世界各国实施大规模信息监控，随时获取各国最新动态。思科公司多款主流路由器产品被曝出在VPN隧道通讯和加密模块存在预置式“后门”，即技术人员在源码编写过程中已经将“后门”放置在产品中，利用“后门”可以获取密钥等核心敏感数据。

- **DLink** 存在管理后门

    - 事件经过: 当攻击者请求中的User Agent（Http 请求包中用于标识浏览器的字段）包含特殊的字符串“xmlset_roodkcableoj28840ybtide”，该用户可以绕过路由器的帐号密码验证直接访问其 Web 管理界面。

    - link: http://blog.jobbole.com/49959/

    - link: https://bbs.pediy.com/thread-182012.htm

## 2012

### 9月

- **phpMyAdmin** 官方镜像被发现植入后门

    - 事件经过:

        开源 PHP 管理工具 phpMyAdmin 软件包的官方镜像被发现植入了后门，开发者已经向用户发出了警告。开发者称，SourceForge.net 镜像之一的 cdnetworks-kr-1 被用于传播了一个植入后门的 phpMyAdmin 软件包，后门位于 server_sync.php 文件中，允许攻击者远程执行 PHP 代码，另一个文件 js/cross_framing_protection.js 也被修改。

        文件的修改日期是2012年8月12日，但研究人员推测日期系伪造，SourceForge 认为入侵发生在9月22日左右，日志显示大约有400人下载了修改版软件。镜像服务器位于韩国，服务器供应商已经证实了入侵。

    - link: https://www.phpmyadmin.net/security/PMASA-2012-5/

### 6月
- **F5** BIG-IP 内置 SSH 私钥

    - 事件经过: F5 公司是应用交付网络(ADN)领域全球领导者.提供应用安全,数据中心防火墙,负载均衡,数据存储,广域网优化,虚拟化及云计算解决方案。2012年6月，安全研究人员发现 F5 多个产品（F5 BIG-IP）存在一个未明配置错误，允许未身份验证的用户以“root”账户登录设备。问题原因是 SSH private key 对应的公钥内置于漏洞设备中，使得用户可以绕过验证直接登录 F5 设备。

    - link: https://www.trustmatta.com/advisories/MATTA-2012-002.txt

    - link: https://www.trustmatta.com/advisories/matta-disclosure-policy-01.txt

### 1月
- **中文版putty等** SSH 远程管理工具被曝存在后门

    - 事件经过: 2012年1月，中文版 putty 等 SSH 远程管理工具被曝存在后门，窃取用户名与口令发送至指定服务器上。

    - link: https://www.cnbeta.com/articles/tech/171116.htm

## 2010

### 11月
- **ProFTPD** 镜像服务器被入侵

    - 事件经过: 流行的开源 FTP 服务器 ProFTPD 在2010年发现被人在代码中放了一个后门。 在安装了包含有后门的 ProFTPD 服务器版本后，攻击者可以获得系统控制权限，攻击者的 IP 地址来自沙特阿拉伯地区。在该版本中，输入命令“HELP ACIDBITCHEZ”会出现一个 root shell。攻击者利用了一个尚未修复的 0day 漏洞。受影响的版本是从11月28日到2日在官方镜像下载的 ProFTPD 1.3.3c。

    - link: https://www.exploit-db.com/exploits/15662

    - link: http://www.h-online.com/security/news/item/Back-door-in-ProFTPD-FTP-server-1146592.html

## 2003

### 11月
- **Linux内核** 后门

    - 事件经过: 早在2003年，有人试图向 Linux 内核插入一个微妙后门源代码。该代码被写入到给一个后门，没有外在标志，被托管的服务器入侵与 Linux 源相连的其他电脑。只有两行代码被更改， 并有可能轻轻松松瞒过大多数的眼睛。幸运的是，后门代码审计人员发现了。关于谁应该对此负责的猜测仍然很多。也许某个要求 Linus Torvalds 向 Linux 添加后门程序的三个字母的机构可能知道。

    - link: https://freedom-to-tinker.com/2013/10/09/the-linux-backdoor-attempt-of-2003/

    - link: https://lwn.net/Articles/57135/

## 2001

### 1月
- **Borland** 的数据库软件后门

    - 事件经过: Borland 公司的 InterBase 数据库软件中的一个“后门”使得任何拥有适当口令的人都可以对数据库和运行数据库的计算机系统实施严重的破坏行为。计算机紧急反应小组在当地时间星期三发表的咨询报告中称，这一“后门”可以使黑客改变存储在数据库中的信息，甚至在计算机中运行造成更大破坏的程序。用户名和口令写在程序里，很容易被发现，而且不能通过改变设置清除掉。Borland 公司承认存在这样一个“后门”，并且已经开始发布补丁，并通知用户和合作伙伴将于本周推出修改后的版本，这一漏洞存在于4、5、6版的InterBase中。

    - link: https://www.kb.cert.org/vuls/id/247371/

---

`“我想，你们这帮家伙应该考虑比这大得多的问题。”`