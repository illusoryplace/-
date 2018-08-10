# hello-illusory
this is my creation
what do this meain?
<!DOCTYPE html>
<html lang=en>
<head>
    <meta charset='utf-8'>
    <title>document</title>
</head>
<body>
    <script>
        // do{
        //     //从弹框录入数据并打印
        //     var input = prompt('输入数据：');
        //     console.log(input)
        // }while(input != 'exit');
        var year = Number(prompt('year'));
        var month = Number(prompt('month'));
        var days = Number(prompt('days'));
        var totalDays = 0;
        var i = 1;
        while(i<month){
            switch(i){
                case 1:
                case 3:
                case 5:
                case 7:
                case 8:
                case 10:
