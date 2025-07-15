# React Version Boilerplate

**React 16, 17, 18, 19 버전별 맞춤형 개발 환경을 제공하는 보일러플레이트**

[![build status](https://img.shields.io/badge/build-passing-brightgreen.svg)](https://github.com/your-username/react-boilerplate-ssngza)
[![license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/your-username/react-boilerplate-ssngza/blob/main/LICENSE)

## 🌟 개요 (Overview)

이 프로젝트는 특정 React 버전에 맞는 개발 환경을 신속하게 구축할 수 있도록 돕는 보일러플레이트입니다. 각 브랜치는 **React 16, 17, 18, 19** 버전에 최적화된 설정(Webpack, Babel, Test 등)을 포함하고 있어, 버전별 호환성 테스트, 마이그레이션 준비, 또는 특정 버전 기반의 프로젝트 시작에 유용합니다.

## 🌱 브랜치 가이드 (Branch Guide)

각 브랜치는 해당 React 버전에 맞는 설정과 라이브러리를 가집니다.

-   **`react/16`**: React 16 (Legacy Context API, Class Components 중심)
-   **`react/17`**: React 17 (새로운 JSX Transform)
-   **`react/18`**: React 18 (Concurrent Mode, Automatic Batching, 새로운 Root API)
-   **`react/19`**: React 19 (Actions, Compiler 등 최신 기능 실험)

### 특정 버전으로 프로젝트 시작하기

```bash
# 예시: React 18 브랜치로 프로젝트 시작하기
git clone --branch react/18 --single-branch https://github.com/ssngza/react-boilerplate-ssngza.git your-new-project
```

## ✨ 공통 기능 (Core Features)

모든 브랜치는 다음의 핵심적인 개발 환경을 공유합니다.

-   **Webpack 5** & **Babel 7** (버전별 최적화 설정)
-   **ESLint** & **Prettier** (코드 스타일 및 품질 관리)
-   **Jest** & **React Testing Library** (테스팅 환경)

## 🚀 시작하기 (Getting Started)

1.  **저장소 복제 (Clone)**

    원하는 React 버전의 브랜치를 선택하여 저장소를 복제합니다.

    ```bash
    git clone --branch <branch_name> --single-branch https://github.com/ssngza/react-boilerplate-ssngza.git your-new-project
    # 예: git clone --branch react/18 --single-branch ...
    ```

2.  **프로젝트 폴더로 이동**

    ```bash
    cd your-new-project
    ```

3.  **의존성 설치 (Install Dependencies)**

    ```bash
    npm install
    # 또는
    yarn install
    ```

4.  **개발 서버 실행 (Run Development Server)**

    ```bash
    npm start
    # 또는
    yarn start
    ```

    이제 브라우저에서 `http://localhost:3000`으로 접속하여 확인할 수 있습니다.

## 📜 사용 가능한 스크립트 (Available Scripts)

-   `npm start`: 개발 모드로 앱을 실행합니다.
-   `npm run build`: 프로덕션용으로 앱을 빌드합니다.
-   `npm test`: 테스트를 실행합니다.
-   `npm run lint`: ESLint로 코드 문제를 검사합니다.

## 📁 폴더 구조 (Folder Structure)

```
/
├── public
│   ├── index.html
│   └── ...
├── src
│   ├── components
│   ├── App.js
│   └── index.js
├── .eslintrc.js
├── .prettierrc
├── babel.config.js
├── package.json
└── webpack.config.js
```
*Note: `index.js`의 `ReactDOM.render` 방식 등은 React 버전에 따라 차이가 있을 수 있습니다.*

## 🤝 기여하기 (Contributing)

각 버전별 설정 개선이나 기능 추가에 대한 기여는 언제나 환영입니다! 이슈를 등록하거나 Pull Request를 보내주세요.

## 📄 라이선스 (License)

이 프로젝트는 MIT 라이선스를 따릅니다.
