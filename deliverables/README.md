# 课程报告交付文件

## 公式编号版（当前推荐下载）

- [医用抗菌水凝胶_课程报告_公式编号版.docx](医用抗菌水凝胶_课程报告_公式编号版.docx)：56,908字节。
- [医用抗菌水凝胶_课程报告_公式编号版.pdf](医用抗菌水凝胶_课程报告_公式编号版.pdf)：14页，709,756字节。

参考[word-formula-omml skill](https://github.com/handpeng/word-formula-omml/blob/main/SKILL.md)，保留16处原生可编辑OMML，统一为Cambria Math、12 pt；4个独立公式居中，编号（1）—（4）右对齐。编号为普通文本，增删公式后需调整。

仅修改DOCX内的word/document.xml；原文件、正文、文献、表格及数学内容保留。skill审计、OOXML校验及LibreOffice读取和PDF预览通过。该skill要求Microsoft Word原生检查；当前环境没有Microsoft Word，此项未执行，不能宣称已通过Word原生验收。详情见`公式格式检查.json`。

- [医用抗菌水凝胶_课程报告.docx](医用抗菌水凝胶_课程报告.docx)：可编辑Word文件，56,050字节。
- [医用抗菌水凝胶_课程报告.pdf](医用抗菌水凝胶_课程报告.pdf)：同一DOCX转换的PDF，14页，708,450字节。
- `manifest.json`：文件大小、SHA-256及检查记录。

本版在上一版基础上局部调整摘要、建议式结尾及部分段落结构，没有重写全文。补充一维扩散时间尺度、幂律流变和混合与成胶时间尺度比三处化工分析，说明假设、变量、SI单位及适用条件。扩散距离加倍对应时间约四倍是模型尺度推论，不是实验数据；未虚设扩散系数、流变参数或成胶时间。公式源稿采用LaTeX，DOCX中转为可编辑的Office Math。正文汉字约7,600字，保留原有21项参考文献、两张表格、已核对数值及必要更正说明。此前语言编辑参考[Humanizer-zh](https://github.com/op7418/Humanizer-zh)。

DOCX为Office Open XML文件，通过ZIP完整性校验，并已由LibreOffice成功读取和转换。引用顺序、课程排版要求及PDF文本边界检查通过。

PDF生成环境没有宋体，采用Noto Serif CJK替代；DOCX声明宋体。在安装宋体的Microsoft Word中，分页可能略有变化。

下载时请在GitHub文件页面选择Download raw file，或下载仓库ZIP。
