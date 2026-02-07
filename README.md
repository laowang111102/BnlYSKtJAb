# 松江大学城就餐推荐系统设计与实现

## 前言

本项目是一款针对松江大学城的就餐推荐系统，基于SSM（Spring、SpringMVC、MyBatis）框架开发。该系统旨在为大学生提供便捷、高效的就餐建议，以解决就餐选择困难的问题。以下是本项目的基本介绍。

## 内容介绍

本项目主要包括以下功能模块：

1. 用户模块：提供用户注册、登录、个人信息管理等功能；
2. 推荐模块：根据用户的喜好、历史就餐记录等因素，为用户推荐合适的餐厅和菜品；
3. 评论模块：用户可以对餐厅和菜品进行评论，为其他用户提供参考；
4. 消息模块：实时推送优惠信息、新品推荐等内容，提高用户活跃度；
5. 管理员模块：负责管理和维护系统，包括用户管理、餐厅管理、菜品管理等功能。

## 技术介绍

本项目采用以下技术栈：

- 语言：Java
- 使用框架：Spring、SpringMVC、MyBatis、微信小程序
- 前端技术：JS、Vue、CSS3、Uniapp
- 开发工具：IDEA/Eclipse、Uniapp
- 数据库：MySQL 5.7/8.0
- 数据库管理工具：phpstudy/Navicat
- JDK版本：jdk1.8
- Maven：apache-maven 3.8.1-bin
- 前端环境：Node.Js 12\14\16

## 核心代码

以下是本项目中的部分核心代码：

```java
// 使用Spring Data JPA实现分页查询
public Page<Restaurant> findRestaurantsByPage(int page, int size) {
    Pageable pageable = PageRequest.of(page, size);
    return restaurantRepository.findAll(pageable);
}
```

## 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

## 项目截图
![封面图片](https://img12.360buyimg.com/ddimg/jfs/t1/326546/33/19642/83145/68c5a332F8635e289/5530017b64371db9.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/344377/3/3031/33664/68c5a30aF311d95b5/85a5410e6ef7ba15.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/324286/5/19668/11726/68c5a30aF59e2b03f/3545f32aa12c085b.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/324657/31/19710/22627/68c5a30bF1e37942b/f64785f4e5fc6b31.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/327780/33/19852/17304/68c5a30bFaa32a74c/dddc89613b057f04.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/336564/6/10475/27443/68c5a30bFd7585316/8a5b708f5766db7d.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/336872/5/10477/29246/68c5a30cFd8fa4313/9c6e80f8e9e152dd.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/326140/2/19541/45192/68c5a30cF58888e98/159af34ad856eeca.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/328313/21/19475/58849/68c5a30dF6db4b127/76f36c8d87cd54cb.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/324466/26/19802/64113/68c5a30dFdbad8d51/8ab5d095eb3362bf.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)
