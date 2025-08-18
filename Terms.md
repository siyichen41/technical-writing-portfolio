# Multiterms and Oxygen 

---

Trados Studio​ 和 ​Oxygen XML Author​ 可以非常有效地结合使用，是处理 XML 内容本地化的推荐工作流程

1. 术语库和翻译库的建立和维护，例如：

|CHS|EN|来源|
|---|---|---|
|一体式云台相机|Gimbal and Cameral|Mavic 4 Pro|
|补光灯|Auxiliary Light|Mavic 4 Pro|
|电池卡扣|Battery Buckles|Mavic 4 Pro|

2. 两个工具软件之间的文档转化：
   Oxygen创建xliff文档---提取内容，保留标签对属性---在trados中打开对应文档进行翻译或审校---保存xllif文档，回到Oxygen

**优点:**
* ​保护结构完整性：​​ 这是最大的优点。XML 标签和结构在翻译过程中被“锁定”，译员无需接触也不会破坏它们。Oxygen 负责精确的导出和重建。
* ​提高译员效率：​​ Trados Studio 为译员提供了熟悉的、专业的翻译环境，利用翻译记忆库、术语库、机器翻译预翻译等功能，专注于文本翻译本身。确保上下文准确：​​ Oxygen 生成的 XLIFF 通常会包含更多上下文信息（如元素属性值 conref, href, id 等），帮助译员理解文本来源和关联。
​* 保持文档一致性：​​ 对于像 DITA 这种重用内容（conref）的情况，在 Oxygen 管理的上下文中导出/合并 XLIFF 比在纯文本编辑器处理更可靠。
* ​支持复杂 XML 格式：​​ Oxygen 对多种行业标准 XML 框架（DITA, S1000D, DocBook）有深度支持，正确处理它们特定的本地化需求（如元素属性的可译性设置）。



