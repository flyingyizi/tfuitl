# 隐马尔科夫模型(HMM)

refer: HMM算法见《统计学习方法 李航》书籍的第十章

- hmm模型文件
    见‘HMM struct’说明，下面为一个持久化的模型文件内容
    ```json
    {
        "N": 3,
        "M": 2,
        "A": [
            0.333,        0.333,        0.333,
            0.333,        0.333,        0.333,
            0.333,        0.333,        0.333
        ],
        "B": [
            0.5,        0.5,
            0.75,        0.25,
            0.25,        0.75
        ],
        "pi": [    0.333,        0.333,        0.333    ]
    }
    ```
- HMM 基本问题模拟
    见hmm/tools目录中几个可执行程序模拟