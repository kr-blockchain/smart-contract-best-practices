# 스마트 컨트랙트 개발 모범 사례

[![Join the chat at https://gitter.im/smart-contract-best-practices/community](https://badges.gitter.im/smart-contract-best-practices/community.svg)](https://gitter.im/smart-contract-best-practices/community?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

- [Ethereum Smart Contract Best Practices](https://github.com/ConsenSys/smart-contract-best-practices)를 포크하여 한국어로 번역된 페이지를 제공합니다.

- 한국어 사이트: https://kr-blockchain.github.io/smart-contract-best-practices/

- 영문 사이트 (원본): https://consensys.github.io/smart-contract-best-practices/
- 중국어 번역본: https://github.com/ConsenSys/smart-contract-best-practices/blob/master/README-zh.md
- 베트남어 번역본: https://github.com/ConsenSys/smart-contract-best-practices/blob/master/README-vi.md

## 참여를 환영합니다!

자유롭게 수정을 위한 pull request 를 만들어주세요. 작은 수정 사항부터 새로운 섹션을 만드는 큰 기여까지 모두 환영합니다. 새로운 컨텐츠를 작성하실 때는 [contributing](./docs/about/index.md)에 있는 스타일 가이드를 참조하시길 바랍니다.

번역하거나 새로운 업데이트를 위한 주제를 찾으시려면 [issues](https://github.com/kr-blockchain/smart-contract-best-practices/issues) 내용을 확인해주세요. 토론하고 싶으신 새로운 아이디어가 있으신 경우에는 [Gitter](https://gitter.im/kr-blockchain/smart-contract-best-practices)에서 채팅으로 알려주세요.

## 문서 사이트 만들기

```
git clone git@github.com:kr-blockchain/smart-contract-best-practices.git
cd smart-contract-best-practices
pip install -r requirements.txt
mkdocs build 
```

서버를 실행 명령어 (실패 시 재시작 포함):

```
until mkdocs serve; do :; done
```

localhost에서 웹 사이트를 운영하기 위해서는 `mkdocs serve` 명령어를 사용하시면 됩니다. 문서 수정 시마다 자동으로 다시 로딩됩니다.

## 문서 웹 사이트 신규 배포

```
mkdocs gh-deploy
```
