# angularjs

<html>
<head>
<style>
body {
    background-color: #d0e4fe;
}

h1 {
    color: DarkOrchid;
    text-align: center;
}

p {
    font-family: "Times New Roman";
    font-size: 20px;
}
</style>
</head>
<body>

<h1>ISEM-551 Project-2</h1>

<button type="button"
onclick="document.getElementById('demo').innerHTML = Date()">
Click me to display Date and Time.</button>
<p id="demo"></p>

<p>Hello! </p>

<script src="http://ajax.googleapis.com/ajax/libs/angularjs/1.4.8/angular.min.js"></script>
<body>

<div ng-app="">
 	<p>Name : <input type="text" ng-model="name"></p>
 	
	<h1>Hello {{name}}</h1>

</div>





</script>

</body>
</html>
