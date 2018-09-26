# 지니 인스톨러
인스톨러를 통하여 jinyphp를 로컬 컴퓨터에 설치를 할 수 있습니다. 

컴포저를 통하여 인스톨러를 다음과 같이 글로벌로 설치를 합니다.

```php
$ composer global require jiny/installer
```

명령을 입력하면 다음과 같이 글로벌로 설치가 이루어 집니다.

```php
Changed current directory to C:/Users/infoh/AppData/Roaming/Composer
Using version ^0.0.1 for jinyphp/installer
./composer.json has been updated
Loading composer repositories with package information
Updating dependencies (including require-dev)
Package operations: 1 install, 0 updates, 0 removals
  - Installing jinyphp/installer (0.0.1): Downloading (100%)
Writing lock file
Generating autoload files
```

정상적으로 인스톨러가 설치가 된 후에는 어디에서든지 새로운 `jinyphp` 프로젝트를 생성할 수 있습니다.

## 프로젝트 생성
지니 인스톨러를 통하여 새로운 프로젝트를 생성합니다. 프로젝트 생성은 지니를 통하여 여러개의 웹사이트 프로젝트를 손쉽게 생성 복제 할 수 있습니다.

```php
jiny new 프로젝트명
```


## 글로벌 설치
글로벌 옵션을 통하여 컴포저를 설치하시면

```
~/AppData/Roaming/Composer/vendor/jiny/installer
```
에 설치가 됩니다.