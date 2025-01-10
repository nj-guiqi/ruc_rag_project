# 人工评分

## 评分标准

见rag/data/corpus/rating_standard.md

## 评分源数据

见rag/data/corpus/custom_conversations_20250109_result.json

## 评分结果

见rag/evaluater_manual/scores.json

## requirements

```shell
pip install streamlit pyyaml
```

## 运行

```shell
streamlit run rag/evaluater_manual/evaluater.py
```