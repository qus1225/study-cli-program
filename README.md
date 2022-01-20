# 파일 구조

- bin: will contain all executable .js files
- lib: contains other files which files of bin might use

# package.json

- bin
  - key of this field is command
  - value is file to execute with that command which is
- main

  - Adding main makes our module both locally and globally usable.
  - tells node that when somebody is trying to import this module locally like
  - If main is missing, then node by default will try to pull index.js file from module’s root directory

# npm repo에 배포되지 않은 패키지 설치

- npm install -g {local_dir_path}
  - ex) `npm install -g ./`

# 참고

- https://medium.com/jspoint/creating-cli-executable-global-npm-module-5ef734febe32
