markdown
# Crypto Project

## 项目简介
这是一个简单的文件加密和解密工具，使用异或（XOR）算法对文件进行加密和解密。该工具包含两个主要函数：`encrypt_file`和`decrypt_file`，它们都使用相同的异或算法来实现加密和解密功能。

## 使用说明
要使用这个工具，您需要在命令行中提供以下参数：
- `<mode>`：模式选择，1 代表加密，2 代表解密。
- `<input_file>`：输入文件的路径。
- `<output_file>`：输出文件的路径。
- `<key>`：用于加密和解密的密钥。

使用方法示例：
```bash
./your_program_name 1 input.txt output.txt 123
这将使用密钥123对input.txt文件进行加密，并将加密后的内容保存到output.txt文件中。

作者信息
姓名：[刘润祥]
学号：[0235238]
邮箱：[212366099@qq.com]
GitHub：[lrxby]
