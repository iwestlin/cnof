# cnof
short for Count Number of Files

## usage
```bash
cnof path_of_dir
```

## install
```
npm i -g cnof
```

## capture
![](https://fffast.oss-cn-hongkong.aliyuncs.com/1590641102838.png)

## notice
cnof will ignore:  
- directory which starts with `.`, like .git
- file which does not contains `.`, like LICENSE, README, etc

Also, cnof will call `.toLowerCase()` to file extension name, which makes `PNG -> png`