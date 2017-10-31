## 函数

- __random(param1,param2):随机生成一个定长的字符串(不含中文)。param1:长度(非必填，默认为6)，param2：纯数字标识(非必填，默认为false)。
- __randomText(param1): 随机生成一个定长的字符串(含中文)。param1:长度(非必填，默认为6)
- __randomStrArr(param1,param2,param3)：随机生成一个定长字符串数组。param1:数组长度(非必填，默认为1)，param2：单个字符串长度（非必填，默认6），param3：纯数字标识(非必填，默认为false)。
- __date(param1)： 生成执行该函数时的格式化字符串。param1为转换的格式，默认为‘yyyy-MM-dd’。
- __generateStrArrByStr(param1,param2)：生成定长的字符串数组。param1:参数为数组长度 即生成参数个数，param2：字符串。
- __sub(param,params...)：减数。第一个参数作为减数，其他参数均作为被减数。
- __max(params...)：获取所有参数的最大值。
- __plus(params...)：将所有参数进行相加。//参数中其中有一个包含小数点将会返回带小数点的值。
- __multi(params...)：将所有参数相乘。
- __bodyfile()