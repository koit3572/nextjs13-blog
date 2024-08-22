# 설치

## dependencies

- tailwindCSS
- redux
  - redux
  - @reduxjs/toolkit
  - redux-persist : redux상태를 지속적으로 저장하고 복원
  - next-redux-wrapper
  - redux-logger

## devDependencies

- redux
  - @types/redux-persist
  - @types/redux-logger
- eslint
  - eslint-config-prettier : prettier와 충돌하는 eslint 설정을 off
- prettier
  - prettier : 코드를 특정 규칙에 맞게 정렬
  - prettier-plugin-tailwindcss : tailwind에 prettier를 적용

# 개발일지

## tailwindCSS prettier

- 기존에는 내 나름대로의 규칙을 정하고 해당 규칙에 따라서 직접 tailwindcss를 정렬하고 정리하였다 그러다보니다 시간도 시간이지만 내가 직접 정리 정렬을 해나감에 따라 일관되지도 않았고 추후 협업때 무용지물이 될거같다는 생각이 들었다. 사실 prettier의 존재를 바로 생각해 내지 못했고 'tailwindcss className정렬'과 같은 검색어들로 검색을 했고 prettier가 있었다는걸 다시 알았다. tailwindcss의 prettier에 대한 내용은 아니지만 prettier를 이미 공부했었던 기억이 있지만 내 잣대로 중요도를 낮게 생각해 기억을 못한거 같아서 한번더 반성하게 되었다.
