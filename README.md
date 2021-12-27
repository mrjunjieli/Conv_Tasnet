# Conv_Tasnet
语音信号处理秋季本科生课程2020 语音增强部分代码

## Requirement 
- librosa
- pytorch


## 步骤
### 数据准备
1、下载数据onedrive https://1drv.ms/u/s!AtdlrbUuaZUHm2R1yJQkgKoCEIBg?e=SFOyCj

2、将数据路径写到createDataPath.py中 并设置好数据文件的输出路径

3、

```shell
python3 createDataPath.py 
```
### Training
- **支持GPU训练**
- **支持模型保存和读取**
由于数据有限 模型训练过程中测试集和验证集保持相同

1、更改对应的数据路径

2、设置好训练参数 然后运行

```shell
python3 main.py 
```
### test

```shell
python3 separate.py 
```

