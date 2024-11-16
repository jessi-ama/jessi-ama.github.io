<!DOCTYPE html>
<html>
<head>
	<title>Tribute Form</title>
	<style>
		body {
			font-family: Arial, sans-serif;
			margin: 20px;
		}
		.container {
			max-width: 800px;
			margin: 40px auto;
			padding: 20px;
			background-color: #f9f9f9;
			border: 1px solid #ddd;
			box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
		}
		.header {
			text-align: center;
		}
		.form {
			margin-top: 20px;
		}
		.form-group {
			margin-bottom: 20px;
		}
		.form-label {
			display: block;
			margin-bottom: 10px;
		}
		.form-input {
			width: 100%;
			height: 40px;
			padding: 10px;
			margin-bottom: 20px;
			border: 1px solid #ccc;
		}
		.form-textarea {
			width: 100%;
			height: 100px;
			padding: 10px;
			margin-bottom: 20px;
			border: 1px solid #ccc;
		}
		.submit-button {
			background-color: #4CAF50;
			color: #fff;
			padding: 10px 20px;
			border: none;
			border-radius: 5px;
			cursor: pointer;
		}
		.submit-button:hover {
			background-color: #3e8e41;
		}
	</style>
</head>
<body>
	<div class="container">
		<div class="header">
			<h1>Share Your Tribute</h1>
			<p>Leave a message or share a story about [Name]</p>
		</div>
		<form class="form">
			<div class="form-group">
				<label class="form-label" for="name">Your Name:</label>
				<input type="text" id="name" class="form-input" required>
			</div>
			<div class="form-group">
				<label class="form-label" for="text">Your Memories Shared:</label>
				<input type="text" id="text" class="form-input" required>
			</div>
			<div class="form-group">
				<label class="form-label" for="message">Your Tribute:</label>
				<textarea id="message" class="form-textarea" required></textarea>
			</div>
			<button class="submit-button" type="submit">Submit Your Tribute</button>
		</form>
	</div>
</body>
</html>
