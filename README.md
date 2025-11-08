# 前言

欢迎来到本项目的 Gitee 仓库！这是一个基于 Java 语言和 Spring Boot 框架开发的 Web 学校课程管理系统。此项目适用于计算机专业毕业设计，也可作为初学者和开发者的实战项目参考。本文档将详细介绍项目内容、技术栈、核心代码等，帮助您更好地了解和使用本项目。

# 内容介绍

本项目是一个学校课程管理系统，主要实现以下功能：

1. 管理员登录、课程管理、教师管理、学生管理等功能；
2. 教师登录、查看课程、录入成绩、修改密码等功能；
3. 学生登录、查看课程、查看成绩、修改密码等功能。

系统采用前后端分离的设计，前端使用 Vue、JS 和 CSS3 技术实现，后端采用 Java 语言和 Spring Boot 框架进行开发。数据库方面，使用 MySQL 5.7/8.0 存储。

# 技术介绍

- 语言：Java
- 使用框架：Spring Boot
- 前端技术：JS、Vue、CSS3
- 开发工具：IDEA/Eclipse
- 数据库：MySQL 5.7/8.0
- 数据库管理工具：phpstudy/Navicat
- JDK版本：jdk1.8
- Maven: apache-maven 3.8.1-bin
- 前端环境：Node.Js 12\14\16

# 核心代码

以下是一段本项目中的核心代码，展示了如何使用 Spring Boot 创建一个 RESTful API：

```java
@RestController
@RequestMapping("/api/courses")
public class CourseController {

    @Autowired
    private CourseService courseService;

    @GetMapping("/{id}")
    public ResponseEntity<Course> getCourseById(@PathVariable Long id) {
        Course course = courseService.getCourseById(id);
        if (course != null) {
            return new ResponseEntity<>(course, HttpStatus.OK);
        } else {
            return new ResponseEntity<>(HttpStatus.NOT_FOUND);
        }
    }
}
```

# 免费源码获取

```
8000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

# 项目截图

![封面图片](https://img10.360buyimg.com/ddimg/jfs/t1/332469/23/10295/124944/68bc598eFa219ff62/1ada1c68b645d73b.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/327082/26/17137/23103/68bc596aF95cd52ec/5a1b9a6436f73175.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/347102/2/457/70009/68bc596aFd19ad9f5/5de72a51f65d8367.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/338509/37/7889/59689/68bc596bF6c1a3083/fbefd15d70b09594.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/343040/8/468/24357/68bc596cF9f605c8b/3b425fe7bf5c5731.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/340819/30/7851/19499/68bc596cF8155b5d5/be78848b4970d8d1.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/349456/31/442/19349/68bc596cF15824a67/93293d20ead17f3b.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/349574/13/441/15032/68bc596dFd02a3292/7fdb276f5e9b47f2.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/345902/34/428/27193/68bc596dF44c31517/575bcb2615c4b0fa.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/349926/5/422/9660/68bc596eF059a4502/b8adf79cc2c4044b.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)
