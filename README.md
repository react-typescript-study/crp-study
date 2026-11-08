# 브라우저 렌더링과 CRP 스터디

## 스터디 주제

브라우저가 HTML과 CSS를 화면에 그리는 과정을 이해하고,
DevTools를 활용해 렌더링 성능을 분석하고 최적화하는 방법을 학습합니다.

## 학습 목차

1. 브라우저 렌더링 파이프라인
   - CRP(Critical Rendering Path)의 전체 흐름
   - DOM·CSSOM 생성과 Render Tree 구성
   - Layout → Paint → Composite
   - 렌더링 엔진 구현 실습

2. DevTools를 활용한 성능 진단
   - DOM 구조와 최종 스타일 분석
   - Performance 타임라인으로 병목 찾기
   - Layout Shift와 CLS 측정
   - Paint·레이어 시각화 및 FPS 분석

3. 브라우저 생명주기와 렌더링 최적화
   - DOMContentLoaded·load 등 주요 이벤트
   - CSS·JS의 렌더링 차단과 로딩 전략
   - preload·async·defer 활용
   - 이미지·웹폰트 로딩 최적화
   - Intersection Observer와 Virtual List
