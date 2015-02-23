---
layout: book
title: wiki
---

- Progit http://git-scm.com/book/zh/v1
  - 很多地方讲得还是比较深，我弄本简单的小书
  - staging area 这个还是要图示给大家，太重要了
  - 分支开发工作流--这个可以不讲，只是一个 master 就能满足日常需求了
    - 试想，我自己都多长时间没用到分支开发工作流了
    - 但是，分支的基本概念和使用肯定是要覆盖的
    - progit 3.4 中介绍的这个工作流当然是分支实用的一种情况，我虽然不讲这个，但是讲分支也一定是从更简单的实用场景出发
      - 比如 gh-pages 分支，可以用来放页面
      - 比如 ... 反正我就是学英语的思路，就整最常用的

    - 3.5 远程分支
      - 这个肯定要讲

    - merge vs rebase
      - 这个要细讲，不然 git pull --rebase 就理解不了
      - conflict 的情况肯定要 cover

    - http://git-scm.com/book/en/v2/Git-on-the-Server-Getting-Git-on-a-Server
      - 这个确实是我自己每天都用得到，但是也可以不讲
      - 也可以演示一下实际用法，对于理解 github 有一定的好处，比如为何要添加 ssh key

    - http://git-scm.com/book/en/v2/Distributed-Git-Contributing-to-a-Project
      - 如何贡献项目当然是重点
      - 但是我面对的观众是大学生，不是公司
      - progit 这里太专业了，我要讲得都是最基础的 PR 流程

    - github
      - github 对于开源项目是免费的，但是如果你想拥有私有项目也就是把代码封闭起来，就是要付费订阅了
      - https 的那个 clone 链接还是有实际用途的，就是给那些没有添加 ssh key 的人
      - 给出详细的注册步骤的截图演示，不要跳过，说“注册是很简单的”，会被打的
      - v2 的 progit 对 github 的讲解是非常详细的，甚至包括了 markdown 在 issue 中怎么写
        - http://git-scm.com/book/en/v2/GitHub-Contributing-to-a-Project

      - http://git-scm.com/book/en/v2/Git-Tools-Reset-Demystified
        - reset 必须讲，但是要讲清原理不容易PP

    - 全书都扫了一遍，跟我要用的思路完全不一样


- http://gitref.org/
  - 首页的 how to think like a git 很实用

- gittalk 2008
  - https://www.youtube.com/watch?v=nPzJESC-fag
  - http://s3.amazonaws.com/chacon/git-talk.pdf

- how github use github to build github
  - https://www.youtube.com/watch?v=qyz3jkOBbQY
  - 12:44 有对 PR 的精炼解释，很白话
    master -> branch -> pr -> master
    17:00 一个 PR 的整个生命流程，用一个实例演示，再好不过了，比直接抽象聊好一千倍
    - 要有 snapshot 有 markdown 的 code ...
  - zach 的观点很喜欢：软件行业有各种开发方式，敏捷，瀑布，BDD，TDD，非常复杂，但是重要的时你找到一种自己喜欢的方式，github 就是这种方式。
  - 整个的异步工作流程，如此的重要，但是对于新人只是空话
  - 但是可以提一下，zachholman.com 很值得一看
  - 也谈到了 branch model 这些问题，所以 holman 可以在最后作为 next step 推荐给大家，真的是很重要
  - github 的流程应该是大家应该下一步学的，因为 github 的流程是企业中应用的流程中最简单的，跟个人开发流程没有什么大的差别
  - 整个流程中体现了对开发者的尊重，真正像一个创作者一样对待他们，而不是当打杂的。

- github pages
  - jekyll 本身肯定不讲了，http://happycasts.net/episodes/6 应该更新啦
  - github pages 的基本过程，用纯 html 的形式演示一下
  - 总之就是一个视频的空间，内容要选最基础的


