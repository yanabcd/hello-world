# hello-world
这是我的第一个代码库readme，2019/6/15,21.00，black，希望我会永远记得你
# 我学习的第一种计算机语言是Python，第二种计算机语言是JavaScript，我承认它们很重要，但是我想，总有一天我会成为一名真正的开发人员。
这个代码库的说明就是见证。
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>
    <style>
    div{display: inline-block;}
    .page2{
        display: none;
    }
    .page3{
        display: none;
    }
    .width{
        width: 300px;
    }
    .displaya{
        display: none;
    }
    </style>
</head>
<body>
    <div>
        <div class="width">
        <button class="" id="btn1">
            页面一
        </button>
        <br>
        <span id="page-1 ">
            context1
        </span>
    </div>
    <div class="width">
        
    <button class="" id="btn2">
        页面二
    </button>
    <br>
    <span class="displaya" id="page-2">
        context2
    </span>
    </div>
    <div class="width">
    <button class="" id="btn3">
        页面三
    </button>
    <br>
    <span id="page-3" class="displaya">
        context3
    </span>
    </div>
</div>
<script>
var a = document.getElementById('page-1');
var b = document.getElementById('page-2');
var c = document.getElementById('page-3');
var btn1 = document.getElementById('btn1');
var btn2 = document.getElementById('btn2');
var btn3 = document.getElementById('btn3');
 
btn1.onclick=function(){
    a.style.display="inline";
    
};
btn2.onclick=function(){
    b.style.display="inline";
    
};
btn3.onclick=function(){
    c.style.display="inline";
};

</script>
</body>
</html>
