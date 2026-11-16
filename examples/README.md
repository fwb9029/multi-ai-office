# 合成示例

本目录全部为手写虚构数据，没有派给任何 AI，不包含真实用户任务，也不是执行证据。

- [plan.example.json](plan.example.json)：先豆包写文本，再由 WorkBuddy 整理文件。title / requirement / steps 及 worker / title / instruction 对应原型计划的外层结构；本仓库没有运行器，阅读不代表执行。
- [result.example.json](result.example.json)：解释“已收回，尚未内容验收”。这是概念结构，不是原型结果文件的完整格式。
- [status.example.json](status.example.json)：解释交稿、待验收和空闲。它不是原型状态接口契约，不能替换实际后台。

步骤间传递上一步实际收回的正文或经过范围校验的文件，不能只传一句“已完成”。在真实环境执行前，需要实现连接、获得必要授权，并创建新的任务标识和输出目录。

示例不含 Harness 收费步骤；复制示例或读取文档不会产生消费授权。
