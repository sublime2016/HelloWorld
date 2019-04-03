<!DOCTYPE html>
<html>
	<head>
		<meta charset="UTF-8">
		<title></title>
		<style>
			*{
				margin:0px;
				padding:0px;
			}
			body{
				
			}
			.box{
				border:solid 2px red;
			}
			.small{
				width:200px;
				border:solid 5px blue;
				padding:10px;
				margin:20px;
			}
		</style>
	</head>
	<body>
		<div class="box">
			<div class="small">
			上面这个盒子，width:200px; height:200px; 但是真实占有的宽高是302*302。 这是因为还要加上padding、border。
注意：宽度和真实占有宽度，不是一个概念！来看下面这例子。
               </div>
		</div>
	</body>
</html>
