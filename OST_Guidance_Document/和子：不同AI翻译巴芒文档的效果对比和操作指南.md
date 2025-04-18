基本信息：

- 撰写时间：2025-04-05
- 作者：和子


# 2024年伯克希尔致股东信翻译对比与大模型翻译能力评估报告

## 摘要

*沃伦·巴菲特的伯克希尔·哈撒韦公司致股东信内容独特，语言风格坦诚、专业且风趣。尽管主流 AI 都能解决最基本的翻译需求，但究竟哪类模型能同时做到信达雅，还需要进一步分析。因此，我们对比了多种大型语言模型（LLM）的英译中翻译结果，评估它们在准确性、术语掌握、风格还原以及语义一致性等方面的表现差异。最终，我们认为当前时点（20250405），不考虑提示词的作用，在各个维度下，GPT4.5-Deep Research几乎都是翻译的最佳选择（plus会员即可使用）。如果条件不具备，建议使用Deepseek-V3生成翻译底稿（行文稳健、语义忠实），随后结合Deepseek-R1润色语言。*

## 操作指南：如何获得最佳翻译效果

基于本次评估结果，我们推荐以下操作流程，以获得最佳的财经文本翻译效果：

1. **首选翻译模型**：**GPT-4.5-Deep Research** > GPT-4.5 > GPT-o1 Pro
2. **翻译流程**：
   - 使用GPT-4.5-DR生成基础翻译版本
   - 通过人工对照英文原文进行校对
   - 重点关注专业术语、俚语表达和巴菲特特有的幽默语气
3. **备选方案**：如无法使用首选模型，Deepseek系列（特别是V3）可作为替代，但需注意其译文偏向文雅正式

## 模型翻译表现综述

总体来看，各模型都能完成高质量英语财经文本翻译，但各有侧重：

- **GPT-4.5系列**：全面平衡忠实和润色，既准确保真又自然顺畅，细节和风格把控最佳，语义一致性突出
- **Claude-3.7/Gemini-2.5**：忠实准确但略显刻板，基本逐句直译，对俚语和语气把握不足
- **Deepseek-R1/V3**：本地化表达优秀，译文优美凝练，但有时过于正式文雅，偏离巴菲特朴实风格

## 各模型表现对比

| 模型 | 准确性 | 术语与语义一致性 | 风格与语气还原 | 典型特点 |
|------|--------|-----------------|--------------|----------|
| Claude-3.7 | 很高 | 专业术语准确，无遗漏 | 正确但直译味重，较正式 | 忠实严谨，隐喻处理欠自然 |
| Deepseek-R1 | 很高 | 术语准确，偶有意译 | 风格庄重优雅，较原文更正式 | 用词考究，善用成语，有润色 |
| Deepseek-V3 | 很高 | 术语准确，语义忠实 | 风格正式通顺，贴近书面语 | 行文稳健，忠实中有优化 |
| Gemini-2.5 | 很高 | 术语准确，无明显错译 | 直译为主，语气中性 | 强调忠实，偶尔缺少灵活 |
| GPT-4.5 | 极高 | 细节到位，语义一致 | 自然亲切，贴近原作者语气 | 翻译流畅，适度解释隐喻 |
| GPT-o1 Pro | 极高 | 细节准确，前后一致 | 平实准确，口吻拿捏得当 | 平衡直译与意译，注重读者体验 |
| GPT-4.5-DR | 极高 | 严谨忠实，语义连贯 | 正式中性，符合原文基调 | 术语精确，注释隐喻，专业稳健 |

> "准确性"指基本信息和数据无误程度；"术语与语义一致性"指专业词汇翻译和前后用词是否统一且不偏离原意；"风格与语气还原"指是否传达出原文类似的语气、幽默和态度。

## 翻译能力差异分析

各模型在基本准确性上已相当高，财经术语翻译没有明显错误。但在风格细节上差异显著：

1. **直译派**（Claude/Gemini）：拘泥直译，未能传达巴菲特幽默坦诚的语调
2. **润色派**（Deepseek系列）：中文表达优美但有时过度润色，失去原文率真
3. **平衡派**（GPT-4.5系列）：在忠实原意的同时提供自然流畅、风格贴切的译文

## 模型特点详细分析

### GPT-4.5系列
- **GPT-4.5-DR**：质量出色，用词简洁专业，风格稍正式但不生硬。细节诠释和整体连贯性突出，提供**专业级**译文。
- **GPT-4.5**：综合表现出色，英文细节理解深刻，中文表达到位。如将俗语"praise by name, criticize by category"译得地道。会为隐喻添加解释，增加信息量。
- **GPT-o1 Pro**：准确流畅，恰当本地化处理。如对"batting average"的翻译既保留比喻又确保理解。语气正式中带适度口语感。

### Claude-3.7-Sonnet
整体翻译准确忠实，术语处理正确，但倾向直译，隐喻处理不够本土化。如将"thumb-sucking"仅译为"拇指吮吸"，未解释其喻指"拖延不决"。语气正式中规中矩，略显生硬。

### Deepseek系列
- **R1**：译文流畅本土化，用词考究，善用成语。如将"At 94, it won't be long..."译为"九十四载春秋将尽..."。有时超出原文口吻，将简练语句润色得过于正式。
- **V3**：与R1相近但润色程度较低，术语准确，适度加入中文常用表达，风格庄重流畅。

### Gemini-2.5-Pro
与Claude相似，倾向直译且忠实，术语理解准确，但对文化隐喻处理较死板。风格平实保守，胜在信息准确无误。

---

# 附录：主流模型翻译效果对比样例

以下是各模型对2024年伯克希尔致股东信部分内容的翻译对比。

## 开场白

**原文**

To the Shareholders of Berkshire Hathaway Inc.:

This letter comes to you as part of Berkshire's annual *report*. As a public company, we are required to periodically tell you many specific facts and figures.

"Report," however, implies a greater responsibility. In addition to the mandated data, we believe we owe you additional commentary about what you own and how we think. Our goal is to communicate with you in a manner that we would wish you to use if our positions were reversed – that is, if you were Berkshire's CEO while I and my family were passive investors, trusting *you* with our savings.

This approach leads us to an annual recitation of both good and bad developments at the many businesses you indirectly own through your Berkshire shares. When discussing problems at specific subsidiaries, we do, however, try to follow the advice Tom Murphy gave to me 60 years ago: "praise by name, criticize by category."

**Claude-3.7-Sonnet**

致伯克希尔哈撒韦公司股东：

这封信是伯克希尔年度*报告*的一部分。作为一家上市公司，我们需要定期向您提供许多具体的事实和数据。

然而，"报告"意味着更大的责任。除了必须提供的数据外，我们相信我们还应当为您提供关于您所拥有的资产以及我们思考方式的额外评述。我们的目标是以这样一种方式与您沟通：假如我们的角色互换——即您是伯克希尔的CEO，而我和我的家人是被动投资者，将*我们*的积蓄托付给您——我们希望您采用的方式。

这种方法使我们每年都会详述您通过伯克希尔股份间接拥有的众多企业的好坏发展。不过，在讨论特定子公司的问题时，我们尽量遵循60年前汤姆·墨菲给我的建议："表扬要指名道姓，批评要笼统而言。"

**Deepseek-R1**

致伯克希尔·哈撒韦公司全体股东：

本函件作为伯克希尔年报的核心组成部分，承载着超越法定披露义务的使命。作为上市公司，我们固然需要定期向各位股东报告诸多具体数据和事实。

但"年报"二字意味着更重的责任。除法定披露内容外，我们认为有必要向您进一步阐释所持资产的内涵与管理哲学。我们始终秉持换位思考的原则——若诸位是执掌伯克希尔的首席执行官，而我与家族成员仅是委托诸位管理毕生积蓄的被动投资者，我们期待获得怎样的信息沟通。

基于这一理念，我们年复一年地向您如实禀报旗下各业务板块的得失进退。不过在讨论子公司具体问题时，我们始终遵循汤姆·墨菲六十年前的箴言："褒扬指名道姓，批评对事不对人。"

**Deepseek-V3**

致伯克希尔·哈撒韦全体股东：

这封致股东信是本公司年报的组成部分。作为上市公司，我们被要求定期向各位披露大量具体数据和事实。

但"报告"二字意味着更深重的责任。除法定披露内容外，我们认为有义务向各位股东额外说明你们所拥有的资产状况及我们的经营理念。我们始终以角色互换的标准来要求这份沟通——假设诸位是伯克希尔CEO，而我和家人只是将积蓄托付给你们的被动投资者。

基于此理念，我们每年都会如实汇报通过伯克希尔股票间接持有的众多企业所经历的得失成败。不过在讨论子公司具体问题时，我们始终遵循六十年前汤姆·墨菲给我的忠告："表扬要点名，批评讲类别。"

**Gemini-2.5-Pro**

致伯克希尔哈撒韦公司股东：

这封信是伯克希尔年度*报告*的一部分。作为一家上市公司，我们需要定期向您提供许多具体的事实和数据。

然而，"报告"意味着更大的责任。除了必须提供的数据外，我们相信我们还应当为您提供关于您所拥有的资产以及我们思考方式的额外评述。我们的目标是以这样一种方式与您沟通：假如我们的角色互换——即您是伯克希尔的CEO，而我和我的家人是被动投资者，将*我们*的积蓄托付给您——我们希望您采用的方式。

这种方法使我们每年都会详述您通过伯克希尔股份间接拥有的众多企业的好坏发展。不过，在讨论特定子公司的问题时，我们尽量遵循60年前汤姆·墨菲给我的建议："表扬要指名道姓，批评要笼统而言。"

**GPT-4.5**

您收到的这封信，是伯克希尔每年一次的报告的一部分。作为一家上市公司，我们必须定期向各位提供诸多具体的事实与数据。

但"报告"一词，蕴含着更大的责任。除了强制披露的数据之外，我们认为还应向股东提供额外的说明，让您清楚地知道自己拥有什么，以及我们在如何思考。我们的目标是用一种换位思考的方式与您沟通——设想一下，如果角色颠倒过来，您是伯克希尔的CEO，而我与我的家人是被动的投资者，将我们一生的积蓄托付给您管理，那时，我们希望您怎么与我们交流？

正因如此，我们每年都会向您坦率地汇报那些您通过持有伯克希尔股票间接拥有的许多企业所取得的成功与遭遇的挫折。当然，当我们谈到某些具体子公司遇到的问题时，我们总会努力遵循60年前汤姆·墨菲（Tom Murphy）给我的忠告："表扬要指名道姓，批评则点到为止。"

**GPT-o1 Pro**

您收到的这封信，是伯克希尔每年一次的报告的一部分。作为一家上市公司，我们必须定期向各位提供诸多具体的事实与数据。

不过，"报告"意味着更大的责任。除了法律要求披露的数字之外，我们还相信，自己有义务额外向你们说明：你所拥有的究竟是什么，以及我们的思考方式。我们的目标是把信息传递给你——就好比要是我们的角色互换：若你是伯克希尔的首席执行官，而我和我的家人只是被动投资者，信任你来打理我们的储蓄，那么我们希望你会如何与我们沟通。

正因如此，每年我们都会向你们汇报，在你们透过持有伯克希尔股份而间接拥有的众多业务中，哪些方面发展顺利、哪些方面出现了问题。若要具体提及某家子公司的挑战，我们会努力遵循汤姆·墨菲在 60 年前给我的建议："表扬要指名道姓，批评则概括而论。"

**GPT-4.5-Deep Research**

这封信是伯克希尔年度报告的一部分。作为一家上市公司，我们有义务定期向您披露许多具体的事实和数据。

然而，"报告"二字蕴含更大的责任。除了法定披露内容，我们还将进一步阐明更多关于您投资的现状以及我们的思考。我们力求以将心比心的方式坦诚地与你沟通——如果您是伯克希尔的 CEO，而我和我的家人是信任您管理我们积蓄的被动投资者——我们希望您也能以同样的方式与我们沟通。

这种理念促使我们每年都如实报告您通过伯克希尔股权所间接拥有的众多企业各种好或坏的进展。不过，在讨论特定子公司的问题时，我们将恪守 60 年前汤姆·墨菲给我的建议："点名表扬，分类批评。"

## 关于错误部分

**原文**

##### Mistakes – Yes, We Make Them at Berkshire

Sometimes I've made mistakes in assessing the future economics of a business I've purchased for Berkshire – each a case of capital allocation gone wrong. That happens with both judgments about marketable equities – we view these as *partial* ownership of businesses – and the 100% acquisitions of companies.

At other times, I've made mistakes when assessing the abilities or fidelity of the managers Berkshire is hiring. The fidelity disappointments can hurt beyond their financial impact, a pain that can approach that of a failed marriage.

A decent batting average in personnel decisions is all that can be hoped for. The cardinal sin is delaying the correction of mistakes or what Charlie Munger called "thumb-sucking." Problems, he would tell me, cannot be wished away. They require action, however uncomfortable that may be.

**Claude-3.7-Sonnet**

##### 错误——是的，我们在伯克希尔也会犯错

有时，我在评估我为伯克希尔购买的企业未来经济状况时犯了错误——每一次都是资本配置出了问题。这种情况在可交易股权（我们将其视为对企业的*部分*所有权）和全资收购公司时都会发生。

其他时候，我在评估伯克希尔雇佣的管理者的能力或忠诚度时犯了错误。忠诚度方面的失望可能会造成超出财务影响的伤害，这种痛苦近似于婚姻的失败。

在人事决策上能有一个不错的命中率已经是万幸。最大的罪过是拖延纠正错误，或者如查理·芒格所说的"拇指吮吸"。问题无法通过祈祷消失，芒格会告诉我，它们需要行动来解决，无论这行动多么让人不舒服。

**Deepseek-R1**

##### 关于失误——伯克希尔并非完美

在评估企业未来经济价值方面，我确曾有过误判——无论是作为部分股权投资的上市公司，还是全资收购的企业，这些资本配置的偏差时有发生。

在人才甄选方面，我也曾出现双重误判：既看错过管理者的能力上限，也错信过其职业操守。后者带来的伤害远超财务损失，其痛楚堪比婚姻破裂。

人事决策能达到七成胜率已属难得。真正的罪过在于对错误的拖延修正，正如查理·芒格所警示的"吮拇指式拖延"。他常提醒我：问题不会因回避而消失，唯有行动方能破局，纵使过程令人不适。

**Deepseek-V3**

##### 错误——是的，伯克希尔也会犯错

在评估收购企业的未来经济价值时，我曾多次犯错——每次都是资本配置的失误。这种误判既发生在对流通股（我们始终将其视为企业部分所有权）的投资决策中，也出现在百分百收购企业的案例里。

还有些时候，我在评估管理层能力或诚信方面栽了跟头。诚信缺失带来的伤害往往远超财务损失，这种痛苦堪比婚姻破裂。

人事决策能保持尚可的胜率就属万幸。最不可饶恕的是拖延纠正错误，正如查理·芒格所说的"吮拇指式逃避"。他总告诫我：问题不会凭空消失，必须采取行动，无论这个过程多么令人不适。

**Gemini-2.5-Pro**

##### 错误——是的，我们在伯克希尔也会犯错

有时，我在评估我为伯克希尔购买的企业未来经济状况时犯了错误——每一次都是资本配置出了问题。这种情况在可交易股权（我们将其视为对企业的*部分*所有权）和全资收购公司时都会发生。

其他时候，我在评估伯克希尔雇佣的管理者的能力或忠诚度时犯了错误。忠诚度方面的失望可能会造成超出财务影响的伤害，这种痛苦近似于婚姻的失败。

在人事决策上能有一个不错的命中率已经是万幸。最大的罪过是拖延纠正错误，或者如查理·芒格所说的"拇指吮吸"。问题无法通过祈祷消失，芒格会告诉我，它们需要行动来解决，无论这行动多么让人不舒服。

**GPT-4.5**

##### 关于犯错——是的，在伯克希尔我们也会犯错

有时候，我对一家收购来的公司未来经营状况判断失误，导致资本配置失败。这类失误，可能出现在我们购买可交易的股票时（我们把这些股票视作对企业的部分拥有权），也可能出现在对企业的100%收购时。

还有一些时候，我对伯克希尔所聘请的管理者的能力或忠诚度产生了误判。如果是忠诚度的问题，带来的失望远不止经济上的损失，那种感觉甚至接近于一次失败婚姻带来的痛苦。

在人事决策上，能做到大部分决策正确就已经很不错了。真正的"大忌"是拖延修正错误，或正如查理·芒格（Charlie Munger）所称之为"吮拇指"（thumb-sucking，意指犹豫不决、装傻发呆）。查理常提醒我："问题不是你光靠希望就能消失的，你必须采取行动，即便那样做会让你感到不舒服。"

**GPT-o1 Pro**

##### 错误——在伯克希尔，我们确实会犯错

有时，我在评估伯克希尔所收购企业的未来经济前景时会出差错——这就是资本配置出现了问题。这样的情况既可能出现在我们把股票投资视作对企业的部分所有权时，也可能出现在我们对企业进行百分之百的收购时。

还有时候，我会在评估伯克希尔所聘用管理者的能力或忠诚度方面出现错误。对忠诚度的失望，有时比金钱上的损失还要令人难受，那种痛苦不亚于一段婚姻破裂。

在人事决策方面，能保持一个尚可的"打击率"（指正确判断的比率）就已经值得欣慰了。但最严重的错误在于对于错误决策的拖延，或者用查理·芒格的话来说，就是"吮手指不作为"。他提醒我，遇到问题不能靠祈祷去解决，必须要付诸行动，无论多么艰难。

**GPT-4.5-Deep Research**

##### 错误——是的，伯克希尔也会犯错

有时，我在评估伯克希尔收购企业的未来经济前景时会犯错——每一次都是资本的错误配置。这种情况既发生在对流通股的判断上——我们将其视为企业的部分所有权——也发生在全资收购公司时。

还有些时候，我在评估伯克希尔所聘经理人的能力或忠诚度时会看走眼。忠诚上的失望所带来的伤害可能超越财务影响，痛苦堪比婚姻破裂。

在人事决策上，我们只能期望有尚可的成功率。最大的错误在于拖延纠正错误，就像查理·芒格所说的"吮手指"（比喻因迟疑而拖延）一样：麻烦不会凭空消失，需要立即行动，不论多么让人不适。

## 关于使用"错误"这个词的讨论

**原文**

During the 2019-23 period, I have used the words "mistake" or "error" 16 times in my letters to you. Many other huge companies have *never* used either word over that span. Amazon, I should acknowledge, made some brutally candid observations in its 2021 letter. Elsewhere, it has generally been happy talk and pictures.

I have also been a director of large public companies at which "mistake" or "wrong" were forbidden words at board meetings or analyst calls. That taboo, implying managerial perfection, always made me nervous (though, at times, there could be legal issues that make limited discussion advisable. We live in a very litigious society.)

**Claude-3.7-Sonnet**

在2019-23年期间，我在致股东信中使用了"错误"或"失误"这两个词共16次。许多其他大公司在这段时间内*从未*使用过这两个词。我应当承认，亚马逊在其2021年信中做出了一些极其坦率的观察。而在其他地方，通常都是愉快的交谈和图片。

我也曾是大型上市公司的董事，在那些公司的董事会会议或分析师电话会议上，"错误"或"错"是被禁止使用的词汇。这种禁忌，暗示着管理层的完美无缺，总是让我感到不安（尽管有时，可能会有法律问题使有限的讨论变得明智。我们生活在一个非常好讼的社会。）

**Deepseek-R1**

2019至2023年间，我在致股东信中累计使用"错误"一词达十六次。同期许多行业巨头在年报中却对此讳莫如深。值得称道的是，亚马逊在2021年致股东信中展现了难得的坦诚，但纵观商界，粉饰太平者仍居多数。

我曾在数家上市公司担任董事，亲历过董事会与分析师会议上对"错误"二字的禁忌。这种强求完美的管理姿态总令我如坐针毡（当然，某些情形下基于法律风险考虑确有保留必要，毕竟我们身处诉讼频发的时代）。

**Deepseek-V3**

2019至2023年间，我在致股东信中累计16次使用"错误"或"失误"这类表述。同期许多巨头企业在公开文件中从未提及这些词汇。需要说明的是，亚马逊在2021年致股东信中曾有过犀利坦诚的反思，但多数企业仍沉溺于歌舞升平的宣传话术。

我曾担任多家上市公司董事，这些企业的董事会和分析师会议上，"错误"与"过失"都是禁忌词汇。这种标榜管理层永不犯错的做法总令我如坐针毡（尽管有时考虑到法律风险，适度保留确有必要。我们毕竟生活在好讼的社会）。

**Gemini-2.5-Pro**

在2019-23年期间，我在致股东信中使用了"错误"或"失误"这两个词共16次。许多其他大公司在这段时间内*从未*使用过这两个词。我应当承认，亚马逊在其2021年信中做出了一些极其坦率的观察。而在其他地方，通常都是愉快的交谈和图片。

我也曾是大型上市公司的董事，在那些公司的董事会会议或分析师电话会议上，"错误"或"错"是被禁止使用的词汇。这种禁忌，暗示着管理层的完美无缺，总是让我感到不安（尽管有时，可能会有法律问题使有限的讨论变得明智。我们生活在一个非常好讼的社会。）

**GPT-4.5**

在2019至2023年期间，我在给股东的信中总共使用了16次"错误"（mistake）或"失误"（error）这两个词。相比之下，很多其他巨型公司在相同期间却一次也没有使用过这类字眼。不过，我得承认，亚马逊在2021年致股东的信中倒是有一些异常直白的反思。但除此之外，更多见的是乐观的套话与漂亮的图片。

过去我也曾担任过一些大型上市公司的董事，这些公司在董事会会议或分析师电话会议上明令禁止使用"错误"或"失误"这类词汇。这种禁忌，似乎暗示着管理层不可能犯错，总让我觉得坐立难安。（当然，在某些特定情形下，由于可能存在的法律风险，管理层的确也不便过多讨论错误——毕竟我们生活在一个诉讼无处不在的社会。）

**GPT-o1 Pro**

在 2019-2023 年期间，我在写给你们的信中用了 16 次"mistake"（错误）或 "error"（失误）这个词。而许多其他规模庞大的公司，在这段时间里从未使用过这类词。我应当承认，亚马逊在 2021 年的股东信中倒是做了一些非常直言不讳的自我检讨。至于其他公司，往往都是溢美之辞和照片一片欢腾。

我本人也曾在一些大型上市公司的董事会任职，在那里，"mistake"或"wrong"是被禁止出现在董事会议或分析师电话会议中的。这样的讳言——仿佛管理层永远不会犯错——总是让我颇感不安（当然，某些时候出于法律风险的考量，限制言辞也可理解。我们的社会确实非常热衷诉讼）。

**GPT-4.5-Deep Research**

2019-2023 年间，我在致您的信中使用了 16 次"错误"或"失误"这样的词。许多其他大公司在这段时间内从未使用过这些字眼。我应该指出，亚马逊在 2021 年的股东信中做出过极为坦率的评论。而在其他地方，通常都是报喜不报忧。

我也曾担任过一些大型上市公司的董事，在那些公司的董事会会议或分析师电话会议上，"疏忽"或"错误"都是禁词。这种暗示管理层完美无缺的禁忌总让我感到不安（当然，有时出于潜在法律问题的考虑，减少讨论是明智的——我们生活在一个诉讼高发的社会）。

## 关于接班人的讨论

**原文**

At 94, it won't be long before Greg Abel replaces me as CEO and will be writing the annual letters. Greg shares the Berkshire creed that a "report" is what a Berkshire CEO annually owes to owners. And he also understands that if you start fooling your shareholders, you will soon believe your own baloney and be fooling yourself as well.

**Claude-3.7-Sonnet**

94岁的我，不久之后格雷格·阿贝尔将取代我担任CEO，并撰写年度信函。格雷格秉承伯克希尔的信条，即"报告"是伯克希尔CEO每年对所有者的责任。他也明白，如果你开始欺骗你的股东，你很快就会相信自己的胡言乱语，最终欺骗了你自己。

**Deepseek-R1**

九十四载春秋将尽，格雷格·阿贝尔接任首席执行官并执笔年报的时刻即将来临。他深谙伯克希尔的信条——向股东如实禀报乃首席执行官的天职，更明白欺瞒投资者的恶果：自欺者终将沦为谎言的囚徒。

**Deepseek-V3**

九十四岁的我即将把CEO职位交给格雷格·阿贝尔，由他执笔未来的股东信。格雷格深谙伯克希尔信条：年报是CEO对股东的神圣承诺。他也明白，当你开始愚弄股东之时，很快就会沉溺于自欺欺人的把戏。

**Gemini-2.5-Pro**

如今我已94岁高龄，格雷格·阿贝尔接替我出任首席执行官并执笔年度股东信的日子，已为时不远。格雷格与我一样，信奉伯克希尔的信条：一份"报告"，是伯克希尔首席执行官每年对所有股东应尽的责任。他也深知，倘若你开始糊弄你的股东，那么用不了多久，你便会沉溺于自己编织的谎言，最终也欺骗了自己。

**GPT-4.5**

今年我94岁了，很快格雷格·阿贝尔（Greg Abel）将会接替我担任伯克希尔CEO，由他负责撰写这封年度股东信。格雷格和我一样，相信"报告"才是伯克希尔CEO每年真正欠股东的东西。他也深知，一旦你开始糊弄股东，那么很快你就会相信自己编织的那些鬼话，到头来，你骗到的只能是自己。

**GPT-o1 Pro**

如今我已 94 岁，距离格雷格·阿贝尔（Greg Abel）接任我的首席执行官一职、并由他执笔年度信，也不会太久了。格雷格非常认同伯克希尔的信条：所谓"报告"，就是伯克希尔的首席执行官每年对股东应尽的责任。他也深谙，如果你开始糊弄股东，最后就会对自己的"胡话"深信不疑，进而把自己也给蒙蔽了。

**GPT-4.5-Deep Research**

我今年 94 岁，离格雷格·阿贝尔接替我出任 CEO 并执笔年度信的日子已不远。格雷格认同伯克希尔的信条，即"报告"是伯克希尔 CEO 每年对股东应尽的义务。他也明白，一旦你开始愚弄股东，这些胡言乱语最终也会让自己信以为真，愚弄了自己。