# Shared Config Example

이 프로젝트는 우아한 기술블로그를 따라 pnpm을 사용하여 ESLint 및 Prettier 설정을 공유하는 모노레포를 설정하는 방법을 보여줍니다.

## Introduction

이 저장소는 ESLint 및 Prettier 설정을 공유하는 모노레포를 설정하기 위한 템플릿을 제공합니다. 여러 프로젝트에서 일관된 코딩 스타일과 형식을 유지하여 개발 과정을 간소화하는 것을 목표로 합니다.

## Getting Started

### Prerequisites

- Node.js (>= 14.x)
- pnpm (>= 6.x)

### Installation

1. **pnpm 설치:**

   ```bash
   npm install -g pnpm
   ```

2. **저장소 클론:**

   ```bash
   git clone https://github.com/your-repo/shared-config-example.git
   cd shared-config-example
   ```

3. **의존성 설치:**

   ```bash
   pnpm install
   ```

## Project Structure

### 🏗️ Structure

- **Monorepo:** pnpm workspace로 관리
- **Packages:**
  - **eslint-config**
    - (Main) [@rushstack/eslint-config](https://github.com/microsoft/rushstack/tree/main/eslint/eslint-config)
  - **prettier-config**
  - **example**
    - Vite 기반
    - React 사용

## Usage

### ⚙️ Scripts

예제 앱에서 린트 명령어 실행:

```bash
pnpm example lint
```
