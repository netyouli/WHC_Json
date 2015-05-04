# WHC_Json
自动把字典转换为json
####Use Example
```objective-c
NSDictionary * dict = @{
        @"weatherinfo":@{
                @"city":@"武汉",
            @"cityid":@"101010100",
                @"img1":@"d1.gif",
            @"img2" : @"n1.gif",
            @"ptime" :@"08:00",
            @"temp1" : @"15",
            @"temp2" : @"5",
            @"weather" : @"hao"
        }
};
    
    NSString * jsonString = [WHC_Json jsonWithDictionary:dict];
    NSLog (@"jsonString = %@",jsonString);
    //jsonString = {\"weatherinfo\":{\"city\":\"北京\",\"cityid\":\"101010100\",\"temp1\":\"15℃\",\"temp2\":\"5℃\",\"weather\":\"多云\",\"img1\":\"d1.gif\",\"img2\":\"n1.gif\",\"ptime\":\"08:00\"}}
```
