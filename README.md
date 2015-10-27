# Single Sign On for Central Authentication Service (SSO CAS)

## 简介

欢迎访问单点登录中心认证服务项目Demo演示。

CAS提供企业级单点登录服务:

- 提供开放且完善的文档API
- 提供多种开源Java服务组件（Oauth2,OpenID,SAML,LDAP,etc...）
- 提供多种开发语言的客户端 Java, .Net, PHP, Perl, Apache, uPortal, and others
- 集成 uPortal, BlueSocket, TikiWiki, Mule, Liferay, Moodle and others
- 提供公共文档和实施技术支持
- 拥有广泛的用户群体

## CAS Demo介绍
- CAS服务端演示
- 集成Spring Security客户端演示
- 集成NodeJs客户端演示
- 集成Remember Me功能

## 相关文档

CAS 官网：<http://www.jasig.org/cas>

CAS API：<http://jasig.github.io/cas/4.0.x/installation/

## Build [![Build Status](https://api.travis-ci.org/Jasig/cas.png)](http://travis-ci.org/Jasig/cas) [![Codeship Status for Jasig/cas](https://www.codeship.io/projects/a204a3a0-727c-0131-ab14-4e46b2fa20d2/status)](https://www.codeship.io/projects/13661)
It is recommended to build and deploy CAS locally using the [Maven War Overlay method][overlay]. 
This approach does not require the adopter to *explicitly* download any version of CAS, but 
rather utilizes Maven's overlay mechanism to combine CAS original artifacts and local 
customizations to further ease future upgrades and maintenance.

## Download
- The codebase may also be *cloned* using a Git client via the following command:
```bash
git clone https://github.com/tanxinzheng/cas-sso.git
```

**注:** If building CAS from the source, running the test cases currently requires an active Internet connection.
Please [see the maven docs][skip] on how to disable the tests.
