# 开源软件许可合规测试作业（homework）

- **作业**：利用软件许可测试工具，对一个开源项目进行技术测试，生成测试报告
- **测试对象**：Apache Commons Lang 3.21.0（Apache 软件基金会，Apache-2.0）
- **测试工具**：ScanCode Toolkit 32.5.0
- **测试环境**：Windows 11 + Python 3.14.7

## 目录

| 路径 | 说明 |
| --- | --- |
| 25080124-潘睿祺-Apache Commons Lang-软件许可测试报告.docx | 测试报告（封面 + 4 页正文） |
| 测试输出/scancode-report.html | ScanCode 生成的 HTML 检测报告（原始输出） |
| 测试输出/scancode-result.json | ScanCode 生成的 JSON 明细（原始输出） |

## 关键结果

- 扫描 706 个文件（70 个目录），耗时 193.8 秒（4 进程）
- 695 个文件检出许可证（98.4%），632 个源码文件中 631 个检出（99.8%）
- 701 次检出中 697 次为 apache-2.0，平均置信度 99.9，许可证清晰度评分 100/100
- 人工复核发现 2 处误报（apache-1.1 的 URL 片段误匹配、generic-cla 关键词误命中）与 1 处真实缺口（download_lang.cgi 无许可证头）