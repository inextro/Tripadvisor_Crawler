# Tripadvisor_Crawler

해당 코드는 selenium을 활용한 dynamic crawling입니다.

총 59개의 호텔에 대해서 특정 고객들의 리뷰 데이터로부터 정보를 수집합니다. 수집하는 호텔과 고객 리스트는 사전에 확보하였으며, 수집하는 정보는 다음과 같습니다.
- Title
- Date
- Review
- isMultiple
- isPartnership

이번 task를 수행하면서 마주칠 수 있는 경우의 수만 코드에 포함하였습니다.
- 작성한 리뷰가 많아 한 페이지에 모든 리뷰가 표시되지 않고 'Show More' 버튼을 눌러야하는 경우
- 작성한 리뷰가 많아 'Show More' 버튼을 눌러도 한 페이지에 모든 리뷰가 표시되지 않고 스크롤을 끝까지 내려야 하는 경우
- 리뷰의 길이가 너무 길어 'More' 버튼을 눌러야 하는 경우
- 리뷰를 삭제한 경우, 탈퇴한 회원의 경우 -> Title, Date, Review에 각각 'The review has been removed'라는 값을 대신 기입
