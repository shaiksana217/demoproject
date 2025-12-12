<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Demo Website</title>
</head>
<body style="margin:0; font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; background-color:#f9f9f9;">

    <!-- Header / Navigation -->
    <header style="background-color:#0d6efd; color:white; padding:20px 40px; display:flex; justify-content:space-between; align-items:center;">
        <h1 style="margin:0; font-size:24px;">DemoSite</h1>
        <nav>
            <a href="#home" style="color:white; margin-right:15px; text-decoration:none; font-weight:bold;">Home</a>
            <a href="#features" style="color:white; margin-right:15px; text-decoration:none; font-weight:bold;">Features</a>
            <a href="#contact" style="color:white; text-decoration:none; font-weight:bold;">Contact</a>
        </nav>
    </header>

    <!-- Hero Section -->
    <section id="home" style="text-align:center; padding:80px 20px; background-color:#e9f2ff;">
        <h2 style="font-size:36px; margin-bottom:20px;">Welcome to DemoSite</h2>
        <p style="font-size:18px; color:#333; max-width:600px; margin:0 auto 30px;">This is a modern demo landing page built with HTML and inline CSS. Deploy it online and access from any device!</p>
        <a href="#features" style="display:inline-block; padding:12px 25px; background-color:#0d6efd; color:white; text-decoration:none; border-radius:5px; font-weight:bold;">Explore Features</a>
    </section>

    <!-- Features Section -->
    <section id="features" style="display:flex; flex-wrap:wrap; justify-content:center; gap:20px; padding:60px 20px;">
        <div style="background-color:white; padding:30px; border-radius:10px; width:280px; box-shadow:0 4px 12px rgba(0,0,0,0.1); text-align:center;">
            <h3 style="color:#0d6efd;">Fast & Lightweight</h3>
            <p>Static websites load quickly and are easy to maintain.</p>
        </div>
        <div style="background-color:white; padding:30px; border-radius:10px; width:280px; box-shadow:0 4px 12px rgba(0,0,0,0.1); text-align:center;">
            <h3 style="color:#0d6efd;">Responsive Design</h3>
            <p>Your website will look good on all devices — mobile, tablet, and desktop.</p>
        </div>
        <div style="background-color:white; padding:30px; border-radius:10px; width:280px; box-shadow:0 4px 12px rgba(0,0,0,0.1); text-align:center;">
            <h3 style="color:#0d6efd;">Easy Deployment</h3>
            <p>Deploy online for free using platforms like Vercel or Netlify.</p>
        </div>
    </section>

    <!-- Contact Section / Footer -->
    <footer id="contact" style="background-color:#222; color:white; text-align:center; padding:40px 20px;">
        <h3>Contact Us</h3>
        <p>Email: info@demosite.com | Phone: +123 456 7890</p>
        <p style="margin-top:15px;">© 2025 DemoSite. All rights reserved.</p>
    </footer>

</body>
</html>
