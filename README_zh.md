
# Leanote��Ʒ

## 1. ����

Leanote, ��ֻ�Ǳʼ�!
![leanote.png](leanote.png "")

**����**

* ֪ʶ����: ͨ��leanote������֪ʶ, leanote���ײ����Ľ���, ��������༭��tinymce��markdown. ��leanote, ����Ծ�������д��.
* ����: ��Ҳ����ͨ������֪ʶ������, �ú���ӵ�����֪ʶ.
* Э��: �ڷ����ͬʱҲ���������һ��Э��֪ʶ.
* ����: leanoteҲ������Ϊ��Ĳ���, ��֪ʶ�����ɲ���, ��leanote�����֪ʶ�����ĸ�Զ!

## 2. Ϊʲô����Ҫ����leanote?
˵ʵ��, ��������evernote����ʵ��˿, ��������Ҳ����evernote�Ĳ���:
* evernote�ı༭�������������ǵ�����, ����������(��ʽ���ҵ�, ��Ϊ����Ա, ���������ǵĻ�������), ͼƬ��������.
* ������markdown�İ�����, ����evernote��Ȼû��.
* ����Ҳ�뽫֪ʶ����, �����������Լ��Ĳ���, ��wordpress, ��Ϊʲô�����߲��ܺ϶�Ϊһ��?
* ����...������Ҫ��O(��_��)O����~

## 3.��װleanote
leanote��һ��˽���Ʊʼ�, �������������װ���Լ��ķ�������, ��ȻҲ������ http://leanote.com ��ע��.

������ϸ������leanote�������leanote������İ�װ�̳�, ���Ʋ���:
* [leanote��������ϸ��װ�̳�](https://github.com/leanote/leanote/wiki/leanote%E4%BA%8C%E8%BF%9B%E5%88%B6%E7%89%88%E8%AF%A6%E7%BB%86%E5%AE%89%E8%A3%85%E6%95%99%E7%A8%8B)
* [leanote��������ϸ��װ�̳�](https://github.com/leanote/leanote/wiki/leanote%E5%BC%80%E5%8F%91%E7%89%88%E8%AF%A6%E7%BB%86%E5%AE%89%E8%A3%85%E6%95%99%E7%A8%8B)

### 3.1. ����leanote

Leanote V1.0-beta.2 �ѷ���, �������ļ�(��ʱû��windows���):

* Linux: [leanote-linux-x86_64.v1.0-beta.2.bin.tar.gz](https://github.com/leanote/leanote/releases/download/1.0-beta/leanote-linux-x86_64.v1.0-beta.2.bin.tar.gz)
* MacOS X: [leanote-mac-x86_64.v1.0-beta.2.bin.tar.gz](https://github.com/leanote/leanote/releases/download/1.0-beta/leanote-mac-x86_64.v1.0-beta.2.bin.tar.gz)

����ֱ�Ӽ��[Leanote bin repository](https://github.com/leanote/leanote-bin) (�Ƽ�, ��ΪΪ���°汾)

### 3.2. ��װ MongodbDB

Leanote����golang(ʹ��[revel](https://revel.github.io/)��� �� [MongoDB](https://www.mongodb.org)���ݿ�), ����Ҫ�Ȱ�װMongodb.

��װMongodbDB, �������ݸ���ϸ����鿴: [wiki](https://github.com/leanote/leanote/wiki/Install-Mongodb)

### 3.3. �����ʼ����

MongodbDB��ʼ������ `[PATH_TO_LEANOTE]/mongodb_backup/leanote_install_data`

```
$> mongorestore -h localhost -d leanote --directoryperdb PATH_TO_LEANOTE/mongodb_backup/leanote_install_data
```

��ʼ���ݰ��������û�:

```
user2 username: admin, password: abc123 (����Ա, ��Ҫ!)
user3 username: demo@leanote.com, password: demo@leanote.com (Ϊ����ʹ��)
```

### 3.4. ����

�޸� `[PATH_TO_LEANOTE]/conf/app.conf`. ������ѡ��:

``mongodb``  **��������!**

```Shell
db.host=localhost
db.port=27017
db.dbname=leanote
db.username=
db.password=
```

``app.secret`` **��Ҫ**
�������޸�һ��, app����Կ, ����ʹ��Ĭ�ϵ�, ��Ȼ���а�ȫ����

����������鿴 `app/app.conf` �� [revel �ֲ�](https://revel.github.io/)

### 3.5. ����leanote

```
$> cd PATH_TO_LEANOTE/bin
$> sudo sh run.sh
```

## 4. ��ζ�leanote���ж��ο���

��鿴 [How-to-develop-leanote](https://github.com/leanote/leanote/wiki/How-to-develop-leanote-%E5%A6%82%E4%BD%95%E5%BC%80%E5%8F%91leanote)

## 5. ������
��л [������](https://github.com/leanote/leanote/graphs/contributors) �Ĺ���, leanote�������Ƕ�������!

## 6. ��������

��ӭ�ύ[pull requests](https://github.com/leanote/leanote/pulls) ��leanote.

leanote���кܶ�����, �����ϲ����, ��ӭ��������һ������leanote.

## ����ĵ�
* [leanote�����ư���ϸ��װ�̳�](https://github.com/leanote/leanote/wiki/leanote%E4%BA%8C%E8%BF%9B%E5%88%B6%E7%89%88%E8%AF%A6%E7%BB%86%E5%AE%89%E8%A3%85%E6%95%99%E7%A8%8B)
* [leanote��������ϸ��װ�̳�](https://github.com/leanote/leanote/wiki/leanote%E5%BC%80%E5%8F%91%E7%89%88%E8%AF%A6%E7%BB%86%E5%AE%89%E8%A3%85%E6%95%99%E7%A8%8B)
* [Leanote source leanoteԴ�뵼��](https://github.com/leanote/leanote/wiki/Leanote-source-leanoteԴ�뵼��)
* [leanote blog theme api(���İ�)](https://github.com/leanote/leanote/wiki/leanote-blog-theme-api)
* [How to develop leanote ��ο���leanote](https://github.com/leanote/leanote/wiki/How-to-develop-leanote-��ο���leanote)


## ����
* [leanote ����](http://bbs.leanote.com)
* QQȺ: 158716820
* [leanote google group](https://groups.google.com/forum/#!forum/leanote)

----------------------------------------------------------------
[English](README.md)
