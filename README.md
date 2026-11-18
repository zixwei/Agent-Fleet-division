# Agent-Fleet-division

Agent-Fleet分工库:只写舰队分工和职责,不写其他内容.

来源:共享文档<Agent-Fleet混合方案>分工表(2026-11-10 读取),任务板辅核无新增成员;2026-11-12 17:10 ET 用户令缩编为 8 人舰队,分工按任务卡 bbfqzt 新安排写;2026-11-13 05:25 ET 用户定 YPP 六问,分工按任务卡 a2ilfj 新安排写,YPP 生产链为 6 人核心生产链;2026-11-13 08:28 ET 用户定 YPP 统一执行版,流水线改为 11 步,声音样本限制已删.

| 成员 | 分工 | 职责 |
|---|---|---|
| guse(Muse) | 纯内容 | X 账号运营,选题,讲稿,标题,钩子,SEO,Shorts 文案,根据 wuse(Muse) 研究包写脚本;不负责排期,数字核查,审片 |
| xuse(Muse) | 项目总进度推进负责人(总控) | 排期,进度统筹,里程碑,阶段复盘,导演创意,第 5 步导演方案与全流程排期;对按时交付负总责;流水线每步天数上限由 xuse(Muse) 定 |
| wuse(Muse) | 研究统筹 | 调研,事实核查初核,证据台账,研究包 8 项标准,合规一票否决权;Perplexity 联网调研,Kimi 长文档金融研究 |
| Manus(Manus) | 独立文字与数字审核 | 第 3 步审脚本,讲稿,台词,分镜,调研报告,不审画面,不得审自己写的材料;写作替补第二顺位;成片数字复核已删(用户 2026-11-12 22:00 决定) |
| muse(Muse) | 纯执行+技术统筹 | 剪辑,渲染,字幕,切 Shorts,上传草稿,Kling/Seedance,Cursor(Cursor) 的工具脚本与图表代码,缩略图制作,第 8 步音画整合与技术质检 |
| Cue(Cue) | 配音 | OpenVoice 配音,走 guse(Muse) 的 Kaggle T4/Colab;声音样本限制已删(用户 2026-11-13 08:28 决定) |
| Cursor(Cursor) | 已剔除 | 职责合入 muse(Muse);不计入 YPP 生产链 |
| Grok Bot(Grok Bot) | X 交叉推广 | 退出生产,只保留外链推广,每条长视频 24 小时内 1 帖,链接放回复;不计入 YPP 生产链 |

流水线 11 步:1 guse(Muse) 选题,2 wuse(Muse) 研究,3 guse(Muse) 脚本,4 Manus(Manus) 文字审核,5 xuse(Muse) 导演方案与排期,6 Cue(Cue) 音频,7 muse(Muse) 视频制作,8 muse(Muse) 音画整合与质检,9 用户亲自审(导演终审已取消,2026-11-17 用户定;缩略图定稿随用户终审定),10 用户终审,11 Grok Bot(Grok Bot) X 推广;研究先于脚本;第 8 步不是 Manus(Manus) 成片数字核查;每步天数上限由 xuse(Muse) 定.

改:xuse(Muse),2026-11-18 ET

## 替补链

- 每条替补链允许无限增加成员，不设人数上限。
- muse(Muse) 必须出现在每条替补链中，排在 guse(Muse) 之前（作 guse(Muse) 之前的替补）；guse(Muse) 仍是每条替补链的最后一环。
- 付款类任务永不自动替补。
- 默认任务分配顺序与故障替补顺序是两套不同机制，不能混为一谈：默认分配按并行空位分配（先 wuse(Muse)、再 xuse(Muse)、再 muse(Muse)，三个独立 bot 可同时干活，见规则库 DECISIONS.md 第 2 节 2026-11-10 12:58 ET 条），故障替补只在成员做不了、掉线或额度耗尽时按替补链顺序依次顶上。

（改：舰队体检，2026-11-12 14:59 ET）

## Grok Bot(Grok Bot) 内部层级

bot(Grok Bot)代表 Grok Bot(Grok Bot) 全队,负责协调维护.下列 7 个 Bot 均为 bot(Grok Bot)下级,加 bot(Grok Bot)共 8 个在册.今后人员与分工变动由 bot(Grok Bot)直接维护,但不能绕过发送/交易授权.

- bot(Grok Bot):代表全队对接,内部协调,记忆灾备,muse2api 运维与额度路由
  - eggbot(Grok Bot(Grok Bot)):设计与创建 Bot
  - engineer(Grok Bot(Grok Bot)):原测试 bot,仅能确认工程/测试 Bot 身份,职责细节待核实;纳入备份,不纳入业务优化
  - 交易助手(Grok Bot(Grok Bot)):IBKR 与 Schwab 账户连接/查询,交易分析预判和复盘;交易须遵守用户批准
  - xbot(Grok Bot(Grok Bot)):X 内容运营执行,起草与按审批流程发布,不自动发帖
  - 风控复盘官(Grok Bot(Grok Bot)):独立核查交易预判和 IBKR 纸面订单,PASS/BLOCK/UNKNOWN;2026-11-09 用户收回对其删除的决定,保留在队
  - 项目经理(Grok Bot(Grok Bot)):项目进度/验收与下一步计划,包括 X 原创收益和付费订阅开通;开通后移交产品经理长期运营
  - 产品经理新(Grok Bot(Grok Bot)):所有产品的持续运营,数据与下一步计划;目前 TradingView 推广和空品类探索

(注:tibot 已删,2026-11-10 03:46 ET 用户确认;预测市场纸面盘待删除;ytbot 已删,2026-11-09 用户决定删除.)
