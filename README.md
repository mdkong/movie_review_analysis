# Sentiment Analysis of Movie Reviews with mecab, sentencepiece and HashingVectorizer.

네이버 영화리뷰 감성분석 및 비교 


# Summary

## 1. mecab 와 sentencepiece 형태소 분석기를 사용하여 네이버 영화리뷰 내용을 분석 (codes 참고)

## 2. 각각의 모델 성능을 ROC 커브를 계산하여 비교
- ## mecab: area = 0.932
- ## sentencepiece area = 0.878

|sentencepiece area = 0.878 |mecab: area = 0.932|
| :------: | ------ |
| ![sentencepiece roc curve](https://user-images.githubusercontent.com/77907363/150270067-43da8330-16ed-44a7-aeea-0401c05b19a6.png) | ![mecab roc curve](https://user-images.githubusercontent.com/77907363/150269986-d9e434cc-1b82-4db8-baa4-93fbbe334e18.png) |

## Demo 

[영화리뷰 분석기 체험해 보기](https://mdkong.pythonanywhere.com "movie review classifier")

See also. 
[Model Used](https://scikit-learn.org/stable/modules/generated/sklearn.feature_extraction.text.HashingVectorizer.html "HashingVectorizer")
