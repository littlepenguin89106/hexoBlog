---
title: Hello World
categories: music
---

<script src="/js/insertBtn.js"></script>

<div id="player1" class="player"></div>
<button onclick="inverseDisplay(&quot;btnGroup1&quot;)">clck me to show</button>
<div id="btnGroup1" class="animate__animated animate__fadeIn"></div>
<script>insertBtn({btnGroupId:"btnGroup1",barId:"btnBar1_1",text:"5 to 10",playerInd:0,start:5,end:10});</script>
<script>insertBtn({btnGroupId:"btnGroup1",barId:"btnBar1_2",text:"15 to 20",playerInd:0,start:15,end:20});</script>

<div id="btnGroup2" class="animate__animated animate__fadeIn"><br/></div>
<div id="player2" class="player"></div>
<button onclick="inverseDisplay(&quot;btnGroup2&quot;)">clck me to show</button>
<script>insertBtn({btnGroupId:"btnGroup2",barId:"btnBar2_1",text:"5 to 10",playerInd:1,start:5,end:10});</script>
<script>insertBtn({btnGroupId:"btnGroup2",barId:"btnBar2_2",text:"15 to 20",playerInd:1,start:15,end:20});</script>

<script>var plist=["Y4nEEZwckuU","vcGbefQBvJ4"];</script>
<script src="/js/player.js"></script>
