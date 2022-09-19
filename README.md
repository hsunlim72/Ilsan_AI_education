# 일산병원 의료인공지능(A.I.) 교육

일산병원 의료인공지능 교육 관련 Github 생성하였습니다.

1. Github 회원가입
2. 가입된 메일주소 보내주기...권한 드리겠습니다.
3. https://github.com/hsunlim72/Ilsan_AI_education 들어가서 본인만의 branch 생성하기
4. 교육 자료 및 실습 코드 올리기
(실습 코드는 구글 코랩으로 작성하고 "GIthub로 사본저장"로 한 후 "Colaboratory 링크 추가"하면 Open in colab 아이콘 추가됨)
5. 국민건강보험공단 자료(무작위 샘플 10%)는 Google drive에 올리신 후 아래 내용으로 연동하세요

import os

import pandas as pd

from google.colab import drive  

drive.mount('/content/gdrive/')  
cloud_directory = '/content/gdrive/MyDrive/sample_data/'  # 국민건강보험공단 자료(무작위 샘플 10%) 위치

os.listdir(cloud_directory)

T20 = pd.read_csv('{}/nhid_gy20_t1.csv'.format(cloud_directory),keep_default_na = False, encoding='cp949')

관련 자료 준비되는대로 올려주시면 검토하겠습니다.
학생 시선으로 맥락성을 유지할 수 있도록 교육 내용은 다를지라도 동일한 자료로 실습 진행 등 검토하겠습니다.
