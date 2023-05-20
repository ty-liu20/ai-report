## 基本信息

*  **样本编码：202305010001**
*  姓名：张三
*  性别:  男
*  年龄：56
*  手机（登录账户名）:  18812345678
*  采样点：北京
*  采样日期:  2023.05.01.
*  接收日期:  2023.05.01.
*  报告日期:  2023.05.12.


## 项目流程

癌症检测项目的实验流程如下图所示。为了保证检测结果准确可靠，我们建立了严格的质量控制体系，分别在血液样本，RNA文库和测序数据三个关键节点上都设立了质量检查点。



![](pipeline.webp)


## 质控报告

您本次检测项目的综合质量评估结果为  **合格**
<br> 具体请参见下表：



<table class="table table-bordered table-responsive no-page-break" id="table1"><thead><tr><th scope="col">质控阶段</th><th scope="col">质控参数</th><th scope="col">质控结果</th><th scope="col">质控标准</th></tr></thead><tbody><tr><th rowspan="3" scope="row">样本质控</th><td>RNA 含量(Cq)</td><td><input type="text" value="27" fdprocessedid="bru1g7"></td><td>&lt;32</td></tr><tr><td>DNA 污染(Cq)</td><td><input type="text" value="40" fdprocessedid="4viqal"></td><td>&gt;35</td></tr><tr><td>微生物污染(ΔCq)</td><td><input type="text" value="-5" fdprocessedid="vgtdu"></td><td>&lt;5</td></tr><tr><th rowspan="3" scope="row">文库质控</th><td>片段大小(bp)</td><td><input type="text" value="250" fdprocessedid="rymfe9"></td><td>200~500</td></tr><tr><td>文库浓度(ng/μl)</td><td><input type="text" value="0" fdprocessedid="s94s4i"></td><td>&gt;1</td></tr><tr><td>接头二聚体(%)</td><td><input type="text" value="0" fdprocessedid="nyzopxbj"></td><td>&lt;5</td></tr><tr><th rowspan="6" scope="row">数据质控</th><td>原始数据(M)</td><td><input type="text" value="10" fdprocessedid="xo9ren"></td><td>&gt;4</td></tr><tr><td>有效数据(M)</td><td><input type="text" value="9.8" fdprocessedid="ogfni"></td><td>&gt; 3.8</td></tr><tr><td>核糖体数据(%)</td><td><input type="text" value="5" fdprocessedid="vrp8wj"></td><td>&lt; 20</td></tr><tr><td>线粒体数据(%)</td><td><input type="text" value="5" fdprocessedid="fbayz"></td><td>&lt; 20</td></tr><tr><td>基因组数据(M)</td><td><input type="text" value="6" fdprocessedid="3zpm14"></td><td>&gt; 2</td></tr><tr><td>去重后数据(M)</td><td><input type="text" value="1" fdprocessedid="4ab2av"></td><td>&gt; 0.1</td></tr><tr><th scope="row">综合评估</th><td colspan="3"><div class="form-check form-check-inline"><label class="form-check-label" for="passCheckBox1">合格<input class="form-check-input" type="checkbox" id="passCheckBox1" disabled=""></label></div><div class="form-check form-check-inline"><label class="form-check-label" for="passCheckBox2">不合格<input class="form-check-input" type="checkbox" id="passCheckBox2" disabled=""></label></div></td></tr></tbody></table>

**注：**

1. DNA污染(Cq)：使用RT-qPCR对样本中的DNA污染进行定量的结果。
2. 微生物污染(ΔCq)：使用RT-qPCR对样本中的细菌核酸污染进行定量的结果。
3. 有效数据(M)：去除低质量测序数据并剪切掉接头序列后得到的测序数据量。
4. 去重后数据(M)：使用分子标签去除重复序列之后得到的测序数据量。

