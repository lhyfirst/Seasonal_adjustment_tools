******************************************************************************************************************
                                          前言


1、本软件采用X12-ARIMIMA模型进行季节性调整，季节性调整方法请参考《X-12-ARIMA季节调整——原理和方法》，中国人民银行调差统计局著，中国金融出版社。

2、本软件移动假日因素仅考虑春节因素。

3、针对流量数据，默认春节前20个自然日、春节期间、春节后20个自然日受到春节因素影响。

4、针对存量数据，默认春节前15个自然日、春节期间、春节后20个自然日受到春节因素影响，默认统计数据时点为月末。

5、本软件仅供参考，不做商业用途。

6、如需使用或其他疑问请联系：lhyfirst@126.com。
                                  


                                          使用说明


1、将需要季调的数据在文件<待调整数据.xlsx>中更改。需要注意：不能调整EXCEL名称。

2、将需要季调的数据防止在该excel文件的表格<原数据>中，数据格式为月度或者季度。

3、本软件分为存量模型和流量模型。在<数据类型>表格中更改待调整数据的数据类型（流量或者存量，不可为其他选项），若未在<数据类型>表格中指定数据类型，则默认为流量数据。

4、可同时放不同数据进行批量季节性调整。需要注意：首列为时间，其余列为数据，首行为数据列名，第二行开始为数据，不可为其他英文或中文字符，可以为空值。

5、季节性调整的结果在输出文件夹下。

6、为确保正常使用，请不要调整本软件自带的任何文件或文件名。

7、如果存在报错，可能为数据格式问题。

8、秘钥存放于文件夹中的 秘钥.txt文件中，请删除多余的回车符号。文件中存储的文件为模型试用秘钥。需要正式秘钥，请联系lhyfirst@126.com或者微信号xiaoniuer1928购买。



************************************************************************************************************************
