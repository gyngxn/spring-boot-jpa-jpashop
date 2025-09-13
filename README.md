## 📚 실전! 스프링 부트와 JPA 활용1

> ※ 본 게시글은 인프런 [실전! 스프링 부트와 JPA 활용1 - 웹 애플리케이션 개발](https://www.inflearn.com/course/%EC%8A%A4%ED%94%84%EB%A7%81%EB%B6%80%ED%8A%B8-JPA-%ED%99%9C%EC%9A%A9-1/dashboard) 강의를 바탕으로 작성하였습니다.
> 강의 내용을 참고하여 개인적으로 정리한 글입니다.

- **섹션 2**  [프로젝트 환경설정](https://velog.io/@gyngxn_/%EC%9D%B8%ED%94%84%EB%9F%B0-%EC%8B%A4%EC%A0%84-%EC%8A%A4%ED%94%84%EB%A7%81-%EB%B6%80%ED%8A%B8%EC%99%80-JPA-%ED%99%9C%EC%9A%A91-%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8-%ED%99%98%EA%B2%BD%EC%84%A4%EC%A0%95)
- **섹션 3**  [도메인 분석 설계](https://velog.io/@gyngxn_/%EC%9D%B8%ED%94%84%EB%9F%B0-%EC%8B%A4%EC%A0%84-%EC%8A%A4%ED%94%84%EB%A7%81-%EB%B6%80%ED%8A%B8%EC%99%80-JPA-%ED%99%9C%EC%9A%A91-%EB%8F%84%EB%A9%94%EC%9D%B8-%EB%B6%84%EC%84%9D-%EC%84%A4%EA%B3%84)
- **섹션 4**  [애플리케이션 구현 준비](https://velog.io/@gyngxn_/%EC%9D%B8%ED%94%84%EB%9F%B0-%EC%8B%A4%EC%A0%84-%EC%8A%A4%ED%94%84%EB%A7%81-%EB%B6%80%ED%8A%B8%EC%99%80-JPA-%ED%99%9C%EC%9A%A91-%EC%95%A0%ED%94%8C%EB%A6%AC%EC%BC%80%EC%9D%B4%EC%85%98-%EA%B5%AC%ED%98%84-%EC%A4%80%EB%B9%84)
- **섹션 5**  [회원 도메인 개발](https://velog.io/@gyngxn_/%EC%9D%B8%ED%94%84%EB%9F%B0-%EC%8B%A4%EC%A0%84-%EC%8A%A4%ED%94%84%EB%A7%81-%EB%B6%80%ED%8A%B8%EC%99%80-JPA-%ED%99%9C%EC%9A%A91-%ED%9A%8C%EC%9B%90-%EB%8F%84%EB%A9%94%EC%9D%B8-%EA%B0%9C%EB%B0%9C)
- **섹션 6**  [상품 도메인 개발](https://velog.io/@gyngxn_/%EC%9D%B8%ED%94%84%EB%9F%B0-%EC%8B%A4%EC%A0%84-%EC%8A%A4%ED%94%84%EB%A7%81-%EB%B6%80%ED%8A%B8%EC%99%80-JPA-%ED%99%9C%EC%9A%A91-%EC%83%81%ED%92%88-%EB%8F%84%EB%A9%94%EC%9D%B8-%EA%B0%9C%EB%B0%9C)
- **섹션 7**  [주문 도메인 개발](https://velog.io/@gyngxn_/%EC%9D%B8%ED%94%84%EB%9F%B0-%EC%8B%A4%EC%A0%84-%EC%8A%A4%ED%94%84%EB%A7%81-%EB%B6%80%ED%8A%B8%EC%99%80-JPA-%ED%99%9C%EC%9A%A91-%EC%A3%BC%EB%AC%B8-%EB%8F%84%EB%A9%94%EC%9D%B8-%EA%B0%9C%EB%B0%9C)
- **섹션 8**  [웹 계층 개발](https://velog.io/@gyngxn_/%EC%9D%B8%ED%94%84%EB%9F%B0-%EC%8B%A4%EC%A0%84-%EC%8A%A4%ED%94%84%EB%A7%81-%EB%B6%80%ED%8A%B8%EC%99%80-JPA-%ED%99%9C%EC%9A%A91-%EC%9B%B9-%EA%B3%84%EC%B8%B5-%EA%B0%9C%EB%B0%9C)

---

📌 [실전! 스프링 부트와 JPA 활용1 - Velog 시리즈 전체 보기](https://velog.io/@gyngxn_/series/%EC%8A%A4%ED%94%84%EB%A7%81-JPA-%ED%99%9C%EC%9A%A9-1)
