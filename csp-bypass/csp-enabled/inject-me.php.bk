<?php header("Content-Security-Policy: default-src 'self'"); ?>
<html>
<head>
<?php echo isset($_GET['inhead']) ? $_GET['inhead'] : ""; ?>
</head>
<title> Injection Attack </title>
<body>
	<form>
		<?php echo isset($_GET['inform_1']) ? $_GET['inform_1'] : ""; ?>
		<input type="text" name=<?php echo isset($_GET['inusername']) ? $_GET['inusername'] : "username"; ?> value="username" />
		<?php echo isset($_GET['inform_2']) ? $_GET['inform_2'] : ""; ?>
		<input type="hidden" name="csrf_token" value="csrf_token"/>
		<input type='password' name="password" value="password" />
	</form>
</body>
</html>
