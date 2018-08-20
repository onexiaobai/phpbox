# phpenvironment 
## Reason 
* vagrant下PHP环境的box文件网上资源较少且版本比较低，PHP7以上的我是没找到

* MACOS系统PHP集成环境不如windows下的使用起来方便(简单吐槽一下)
    
   * MAMP是收费的，而且比较贵，
   * XAMPP对于MACOS高版本系统兼容做的不好， 且缺少常用到的memcache和redis
   * 大多数人会选择使用brew，安装成本以及使用成本比较大，所用到的需要一个一个进行安装配置，而且日后更新不方便

* vagrant可以创建和部署虚拟化开发环境，可以更大程度的贴合线上环境而且通过多个实例的可以更好的部署开发环境和测试环境，环境一致性得到保证。
   

## Introduction
* 用于vagrant下的一套完整的PHP开发环境box文件，box文件系统为centos7,包含PHP7.1、mysql5.5、nginx1.14、memcached1.5、redis4.0

## Remarks
* vagrant搭建PHP开发环境还需要安装VirtualBox以及vagrant，此两项的安装百度和google有很多类似的教程，这里就不在说明了。这里只是提供了一个环境所需要很重要的一个box文件。
