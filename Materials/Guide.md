# 실험노트 작성 예시
아래 내용은 실험노트 작성 예시이니, 참고하여 작성 바랍니다.🫡

#### 실험 일자: 2025. 03. 17 월
#### 실험 제목: Sequence quality control
#### 실험 목적: Sequencing 결과물의 품질을 확인하고 적절한 조건으로 고품질 데이터만 추출함
#### 사용한 소프트웨어 및 원리
 * **FastQC**: Base calling 결과물을 사용하여 sequence 위치별 신뢰수준을 보여주는 소프트웨어
 * **Trimmomatic**: ...blah blah
 * **Galaxy**: ...blah blah
 * **Phred score**: ...blah blah
 * **Trimming**: ...blah blah
#### 실험 방법
 * Sequencing 데이터를 Galaxy 서버 상에 업로드함
 * 업로드한 데이터를 FastQC를 사용하여 품질을 확인함
 * 저품질의 sequence는 trimming될 수 있도록 ... blah blah

#### 실험 결과 및 고찰
 * FastQC 확인 결과, 평균 Q25 수준의 sequences들이 존재함
 * Sequence 길이가 길어질 수록 Phred score값이 낮아짐
 * Trimmomatic을 이용하여 저품질의 데이터를 제거한 후에 FastQC로 다시 quality를 확인한 결과, 평균 Q30 수준의 sequences들만 남게됨
 * Trimming parameter에 따라 제거되는 sequence의 비율이 달라짐
 * ...blah blah
