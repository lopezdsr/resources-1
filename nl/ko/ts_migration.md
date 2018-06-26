---

copyright:

  years: 2018

lastupdated: "2018-05-31"

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:new_window: target="_blank"}
{:gif: data-image-type='gif'}
{:tip: .tip}

# 서비스 인스턴스 마이그레이션 문제점 해결

Cloud Foundry 서비스 인스턴스를 리소스 그룹으로 마이그레이션하는 동안 문제가 발생하는 경우 다음 공통 문제를 검토하면 마이그레이션을 진행하는 데 도움이 됩니다.

## 내 서비스 인스턴스를 잘못된 리소스 그룹에 마이그레이션하면 어떻게 됩니까?

현재는 리소스가 지정된 후에는 리소스 그룹 간에 해당 리소스를 이동할 수 없습니다. 따라서 인스턴스를 잘못된 리소스 그룹으로 마이그레이션한 경우 인스턴스를 삭제하고 카탈로그에서 새 인스턴스 작성을 시도할 수 있습니다. 인스턴스를 작성할 때 올바른 리소스 그룹에 지정할 수 있습니다.

## 마이그레이션할 수 없는 이유는 무엇입니까?

서비스 인스턴스를 마이그레이션하기 위한 올바른 액세스 권한이 지정되지 않았을 수 있습니다. 자세한 정보는 [누가 서비스 인스턴스를 마이그레이션할 수 있습니까?](/docs/account/instance_migration.html#whocanmigrate)를 참조하십시오.

## 내 서비스가 모두 마이그레이션에 적합하지 않은 이유는 무엇입니까?

현재는 IAM 액세스 제어 및 리소스 그룹을 사용하여 모든 서비스가 관리되지는 않습니다. 마이그레이션 태스크를 완료하기 위한 액세스 권한이 있는 경우에는 서비스가 IAM 사용을 지원하는 경우 알림을 받습니다.