# Token 與文字預測

> 狀態：教學初稿，待人工確認

## 一、基本定義

Token 是語言模型處理文字時使用的基本單位，可能是一個字、單字、部分單字或其他文字片段。

## 二、原理說明

語言模型會利用上下文估計下一個 Token 出現的可能性，再逐步產生文字。實際切分方式會依 Tokenizer 而不同。

## 三、生活化例子

例如，輸入「今天的天氣很」，模型可能接續產生「好」、「冷」等文字。這是文字預測的簡化示意。

## 四、重要英文術語

- Token
- Tokenizer
- Prediction

## 五、資料來源

- [SRC-01] [Introduction to Large Language Models](https://developers.google.com/machine-learning/crash-course/llm)

## 六、Wiki 檢索依據

- SRC-01-C001 （SRC-01）
- SRC-01-C002 （SRC-01）
- SRC-01-C003 （SRC-01）

> 注意：以上為檢索候選依據，尚需人工核對是否支持各段中文敘述。
