# ICUnicodeDemo


#  iOS解决NSArray、NSDictionary打印乱码问题

    dict = {
    key1 = abc;
    key2 = "\U4e2d\U6587";
    } 

    array = (
    abc,
    "\U4e2d\U6587"
    )

# 使用方法：将 NSArray+Extension 和 NSDictionary+Extension 两个分类拖入项目即可

# 打印效果 ：
    2015-08-08 10:19:36.294 ICUnicodeDemo[2135:50801]

    dict = {
    key1 = abc,
    key2 = 中文
    } 


    array = [
    abc,
    中文
    ]

简述博客地址：http://www.jianshu.com/writer#/notebooks/1368746/notes/1700262