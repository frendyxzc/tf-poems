# tf-poems

参考 [char-rnn-tensorflow](https://github.com/sherjilozair/char-rnn-tensorflow) 实现

### 1. 训练

```
python3 trainer.py
```

### 2. 生成诗歌

2.1 随机生成：
```
python3 generator.py
```

2.2 藏头诗：
```
python3 generator.py --prime 执子之手
```

![image](/screenshot/001.png)