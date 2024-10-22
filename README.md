### 제2기 BDA 데이터 분석 활용 공모전

> 최우수상\
> 11번가와 네이버에서 cj제일제당의 상품 판매량 증대를 위한 마케팅 전략 제안
>
>> - 주최 : 
>> - 기간 : 2023.07.19 ` 2023.08.26
>> - 핵심 역할 : 날짜에 따른 판매량 차이 파악, 유의미한 인사이트 도출
>> - language : Python, Matplotlib, Seaborn, Pandas

 --- 
 cj제일제당의 네이버와 11번가 판매 데이터를 받아서 분석 후 마케팅 전략
크롤링을 통해 카테고리열 생성
요일별 매출 특성 파악(각 사이트별 카테고리별 주문수량과 매출액 평균, 요일별 상품주문량, 상품유형별 주문수량과 매출액 평균, 요일별 상품유형에 따른 주문량, 요일별 카테고리 주문량)
사이트별 군집분석(min-max scaler, 원핫인코딩, pca, )
사이트별 마케팅 전략 + 사이트의 군집별 마케팅 전략 제안
	다담찌개사랑꾼 : 다담 상품 구매시 어울리는 상품 같이 추천
	충성도가 높은 군집 : 주문취소가 가장 적은 그룹으로 조금이라도 할인율이 계속 오르게 함
