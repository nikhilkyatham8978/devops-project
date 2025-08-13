<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Login Page</title>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.6.1/dist/css/bootstrap.min.css">
  <style>
    body {
      background-color: #f8f9fa;
    }
    .login-container {
      margin-top: 100px;
      max-width: 400px;
      padding: 30px;
      background-color: white;
      box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
      border-radius: 8px;
    }
  </style>
</head>
<body>

<div class="container d-flex justify-content-center">
  <div class="login-container">
    <h3 class="text-center mb-4">User Login</h3>

    <!-- Alert Message (Optional) -->
    <!-- <div class="alert alert-danger">Invalid credentials</div> -->

    <form action="/login" method="post">
      <div class="form-group">
        <label for="email">Email address</label>
        <input 
          type="email" 
          class="form-control" 
          id="email" 
          name="email" 
          placeholder="Enter email" 
          required>
      </div>
      
      <div class="form-group">
        <label for="password">Password</label>
        <input 
          type="password" 
          class="form-control" 
          id="password" 
          name="password" 
          placeholder="Enter password" 
          required>
      </div>

      <button type="submit" class="btn btn-primary btn-block">Login</button>

      <p class="text-center mt-3">
        Don't have an account? <a href="/register">Register here</a>
      </p>
    </form>
  </div>
</div>

</body>
</html>

