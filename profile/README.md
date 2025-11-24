### WORDTAMJEONG - 한국어 의미 유사도 기반 단어 추측 게임

<div align="center">
  <h1>WORDTAMJEONG - 한국어 의미 유사도 기반 단어 추측 게임</h1>
  <p>🧠 AWS Bedrock 기반 한국어 단어 추측 게임 🧠</p>
</div>

<br/>

<div align="center">
  <img src="./assets/Main.png" alt="WORDTAMJEONG 메인 화면" style="border-radius: 10px;"/>
</div>

<br/>

<div align="center">
  <img src="./assets/Result.png" alt="WORDTAMJEONG 추측 결과 화면" style="border-radius: 10px;"/>
</div>

<br/>

<div align="center">
  <a href="https://wordtamjeong-frontend.vercel.app/">홈페이지</a>
</div>

---

## ✍️ 프로젝트 개요

- **프로젝트명:** WORDTAMJEONG
- **프로젝트 기간:** 2025.11
- **프로젝트 형태:** 프로젝트
- **목표:** 한국어 단어 간 **의미 유사도**를 활용해, 사용자가 단어를 추측하면서 자연스럽게 단어 의미 공간을 탐색할 수 있는 게임
- **주요 타겟 사용자:**  
  - 한국어 Wordle / Semantle 류의 게임을 좋아하는 사용자  
  - AWS Bedrock 기반 임베딩/유사도 데모가 필요한 개발자

---

## ✍️ 프로젝트 소개

### 프로젝트 배경

기존 단어 게임들은 철자 일치나 단순 규칙 기반(예: 자리수, 알파벳 포함 여부)에 집중되어 있어  
**“의미가 비슷한 단어들끼리 얼마나 가까운가?”** 를 체감하기는 어려웠습니다.

또한, 영어권에는 Semantle 같은 의미 기반 단어 추측 게임이 있지만  
한국어에서는 **의미 유사도 기반 게임**을 체험할 수 있는 서비스가 많지 않습니다.

**WORDTAMJEONG**은 AWS Bedrock의 임베딩 모델을 활용해  
한국어 단어를 벡터 공간에 매핑하고,  
사용자가 입력한 단어와 정답 단어의 **코사인 유사도**를 기반으로  
얼마나 “가깝게” 맞추고 있는지를 직관적으로 보여주는 게임입니다.

---

## 🚀 프로젝트 목표

1. **의미 기반 단어 추측 경험 제공**  
   - 철자가 아닌 *의미*로 정답에 접근하는 새로운 방식의 단어 게임 제공  

2. **한국어 임베딩/벡터 검색 실험 플랫폼**  
   - AWS Bedrock 임베딩 모델(Titan / Cohere)을 활용한  
     한국어 의미 공간 실험 및 벡터 유사도 계산 구조 구현  

3. **운영 및 확장 고려한 구조 설계**  
   - 일별 정답 로테이션, 상위 유사 단어 집계, JSON 기반 히스토리 관리 등  
     향후 웹/앱 클라이언트 연동, 랭킹/통계 기능 확장을 고려한 설계

---

## 🧑‍💻 팀원 소개

| **이름** | **역할**         |
|:--------:|:----------------:|
| 김주호   | BE (Go 서버)     |
| 이동건   | FE (Vue.js 프론트)|

---

## ⚙️ 기술 스택

<table>
  <thead>
    <tr>
      <th>분류</th>
      <th>기술 스택</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>프론트엔드</td>
      <td>
        <img src="https://img.shields.io/badge/Vue.js%203-4FC08D?style=flat&logo=Vue.js&logoColor=white"/>
        <img src="https://img.shields.io/badge/Vite-646CFF?style=flat&logo=vite&logoColor=white"/>
        <img src="https://img.shields.io/badge/Axios-5A29E4?style=flat"/>
        <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white"/>
      </td>
    </tr>
    <tr>
      <td>백엔드</td>
      <td>
        <img src="https://img.shields.io/badge/Go-1.21+-00ADD8?style=flat&logo=go&logoColor=white"/>
        <img src="https://img.shields.io/badge/net/http-Standard%20Library-lightgrey?style=flat"/>
      </td>
    </tr>
    <tr>
      <td>AWS &amp; AI</td>
      <td>
        <img src="https://img.shields.io/badge/AWS%20SDK%20for%20Go%20v2-FF9900?style=flat&logo=Amazon-AWS&logoColor=white"/>
        <img src="https://img.shields.io/badge/AWS%20Bedrock-FF9900?style=flat&logo=Amazon-AWS&logoColor=white"/>
        <img src="https://img.shields.io/badge/Titan%2FCohere%20Embeddings-000000?style=flat"/>
      </td>
    </tr>
    <tr> 
      <td>협업 &amp; 기타</td> 
      <td> 
        <img src="https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white"/> 
        <img src="https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white"/> 
      </td> 
    </tr>
  </tbody>
</table>

---
