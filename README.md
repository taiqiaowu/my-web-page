<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>
</head>

<body>
    <input type="text" value="请输入用户名" style="color: blueviolet" onfocus="if(this.value=='请输入用户名'){this.value='';}"
        onblur="if(this.value==''){this.value='请输入用户名';}">
    <h1 title="第一段">A</h1>
    <p>djskjdksjksjdsjdjsldjsldjskjdlksjdlkjsdjsldjsimh<abbr
            title="aaaaaaaaaaaaaaaaaa">a</abbr>fkdfjksdfsdkjfdskjhfkjsdmnchfojfd;fkdllgdjlgdf
        vcnvmcnvm,xncv,mnxc,vnekfdkdf;ldd;lds,dsmc,m v,m<abbr
            title="bbbbbbbbbbbbbbbbbb">b</abbr>fdskf;ldkfkdflkdjflkdjfjsdcjfsdjsflkdsjfljsdlfjs
        fjfkjdshfkjsdkjfhdskfh<abbr title="ccccccccccccccccc">c</abbr></p>
    <h1 title="第二段">B</h1>
    <p>djskjdksjksjdsjdjsldjsldjskjdlksjdlkjsdjsldjsimh<abbr
            title="aaaaaaaaaaaaaaaaaa">a</abbr>fkdfjksdfsdkjfdskjhfkjsdmnchfojfd;fkdllgdjlgdf
        vcnvmcnvm,xncv,mnxc,vnekfdkdf;ldd;lds,dsmc,m v,m<abbr
            title="bbbbbbbbbbbbbbbbbb">b</abbr>fdskf;ldkfkdflkdjflkdjfjsdcjfsdjsflkdsjfljsdlfjs
        fjfkjdshfkjsdkjfhdskfh<abbr title="ccccccccccccccccc">c</abbr></p>
    <h1 title="第三段">C</h1>
    <p>djskjdksjksjdsjdjsldjsldjskjdlksjdlkjsdjsldjsimh<abbr
            title="aaaaaaaaaaaaaaaaaa">a</abbr>fkdfjksdfsdkjfdskjhfkjsdmnchfojfd;fkdllgdjlgdf
        vcnvmcnvm,xncv,mnxc,vnekfdkdf;ldd;lds,dsmc,m v,m<abbr
            title="bbbbbbbbbbbbbbbbbb">b</abbr>fdskf;ldkfkdflkdjflkdjfjsdcjfsdjsflkdsjfljsdlfjs
        fjfkjdshfkjsdkjfhdskfh<abbr title="ccccccccccccccccc">c</abbr></p>
    <h1 title="第四段">D</h1>
    <p>djskjdksjksjdsjdjsldjsldjskjdlksjdlkjsdjsldjsimh<abbr
            title="aaaaaaaaaaaaaaaaaa">a</abbr>fkdfjksdfsdkjfdskjhfkjsdmnchfojfd;fkdllgdjlgdf
        vcnvmcnvm,xncv,mnxc,vnekfdkdf;ldd;lds,dsmc,m v,m<abbr
            title="bbbbbbbbbbbbbbbbbb">b</abbr>fdskf;ldkfkdflkdjflkdjfjsdcjfsdjsflkdsjfljsdlfjs
        fjfkjdshfkjsdkjfhdskfh<abbr title="ccccccccccccccccc">c</abbr></p>
    <h1 title="第五段">E</h1>
    <p>djskjdksjksjdsjdjsldjsldjskjdlksjdlkjsdjsldjsimh<abbr
            title="aaaaaaaaaaaaaaaaaa">a</abbr>fkdfjksdfsdkjfdskjhfkjsdmnchfojfd;fkdllgdjlgdf
        vcnvmcnvm,xncv,mnxc,vnekfdkdf;ldd;lds,dsmc,m v,m<abbr
            title="bbbbbbbbbbbbbbbbbb">b</abbr>fdskf;ldkfkdflkdjflkdjfjsdcjfsdjsflkdsjfljsdlfjs
        fjfkjdshfkjsdkjfhdskfh<abbr title="ccccccccccccccccc">c</abbr></p>
    <script>
        // 创建目录
        // var h1Nodes = document.getElementsByTagName("h1");
        // var len = h1Nodes.length;
        // var dllist = document.createElement("dl");
        // var dlText = document.createTextNode("目录");
        // dllist.appendChild(dlText);
        // for (var i = 0; i < len; i++) {
        //     var dttile = document.createElement("dt");
        //     var dtText = document.createTextNode(h1Nodes[i].firstChild.nodeValue);
        //     dttile.appendChild(dtText);
        //     dllist.appendChild(dttile);
        //     var ddesc = document.createElement("dd");
        //     var ddText = document.createTextNode(h1Nodes[i].getAttribute("title"));
        //     ddesc.appendChild(ddText);
        //     dllist.appendChild(ddesc);
        // }
        // var body = document.getElementsByTagName("body")[0];
        // body.appendChild(dllist);


        // 创建缩略表
        //     function displayAbbr() {
        //         if (document.getElementsByTagName && document.createElement && document.createTextNode) {
        //             var abbr = document.getElementsByTagName("abbr");
        //             if (abbr.length > 1) {
        //                 var defs = [];
        //                 for (var i = 0; i < abbr.length; i++) {
        //                     var definition = abbr[i].getAttribute("title");
        //                     var key = abbr[i].firstChild.nodeValue;
        //                     defs[key] = definition;
        //                 }
        //             }
        //             var dlist = document.createElement("dl");
        //             for (key in defs) {
        //                 var dttile = document.createElement("dt");
        //                 var ddesc = document.createElement("dd");
        //                 var dtText = document.createTextNode(key);
        //                 dttile.appendChild(dtText);
        //                 dlist.appendChild(dttile);
        //                 var ddText = document.createTextNode(defs[key]);
        //                 dlist.appendChild(ddesc);
        //                 ddesc.appendChild(ddText);
        //             }
        //             var head = document.getElementsByTagName("body")[0];
        //             var hearText = document.createTextNode("描述");
        //             head.appendChild(hearText);
        //             head.appendChild(dlist);
        //         }
        //     }
        //     window.onload = displayAbbr;
        // 
    </script>
</body>

</html>
