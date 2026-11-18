# Site
function random(){  let high=Math.random()&lt;0.5;  let min=high?169:0,max=high?200:170;  let a=Array.from({length:6},()=>Math.floor(Math.random()*(max-min+1))+min);  let fire=Math.floor(Math.random()*71)+30;  return {mode:high?"Cao":"Thấp",sensitivity:a,button:fire+"%"}; } console.log(random());
