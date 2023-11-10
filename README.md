# hello-world
my first repository is to learn how to build fithub repository.

# 处理数据成
wav.scp
text
# 提前计算好cmvn，存储的格式是：
aishell_cmvn
计算脚本：
utils/compute_cmvn.sh

# 准备字典
字典前三位：<blank> <s> </s>
三个特殊的字符，其余的字典如果是char就是把数据中的char都放到字典中。
zh_token_list 是根据aishell 制作的纯中文字典

