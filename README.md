```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ChefMate - AI Recipe App</title>
    <style>
        body {
            margin: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #fff7ed, #ffe0cc);
            color: #2c2c2c;
            padding: 20px;
        }

        .container {
            max-width: 900px;
            margin: auto;
            background: white;
            border-radius: 20px;
            padding: 40px;
            box-shadow: 0 15px 30px rgba(0,0,0,0.1);
        }

        .header {
            text-align: center;
        }

        .header h1 {
            font-size: 3rem;
            color: #ff6b35;
            margin: 0;
        }

        .header p {
            font-size: 1.2rem;
            color: #666;
        }

        .badge {
            display: inline-block;
            background: #ff6b35;
            color: #fff;
            padding: 8px 16px;
            border-radius: 30px;
            margin-top: 10px;
            font-size: 0.9rem;
        }

        h2 {
            color: #ff6b35;
            margin-top: 40px;
            border-bottom: 2px solid #ff6b35;
            display: inline-block;
            padding-bottom: 5px;
        }

        ul {
            line-height: 1.8;
        }

        ul li::marker {
            color: #ff6b35;
        }

        .box {
            background: #fff3eb;
            padding: 20px;
            border-radius: 12px;
            border-left: 5px solid #ff6b35;
        }

        .code {
            background: #2d2d2d;
            color: #f8f8f2;
            padding: 15px;
            border-radius: 10px;
            overflow-x: auto;
            font-family: monospace;
        }

        .footer {
            text-align: center;
            margin-top: 50px;
            color: #888;
            font-size: 0.9rem;
        }
    </style>
</head>
<body>

<div class="container">

    <div class="header">
        <h1>🍳 ChefMate</h1>
        <p>AI-Powered Recipe Suggestion iOS App</p>
        <div class="badge">UIKit • Gemini AI • URLSession</div>
    </div>

    <h2>✨ Overview</h2>
    <p>
        ChefMate is an intelligent iOS application that converts user-input ingredients into smart, structured recipe suggestions using Gemini AI. It provides clean UI, real-time responses, and detailed cooking instructions for a smooth and modern culinary experience.
    </p>

    <h2>🚀 Features</h2>
    <ul>
        <li>AI recipe generation using Gemini API</li>
        <li>Real-time ingredient processing</li>
        <li>Minimal & modern UIKit UI</li>
        <li>Step-by-step recipe instructions</li>
        <li>Save favourite recipes locally</li>
        <li>Smooth navigation flow</li>
    </ul>

    <h2>🛠 Tech Stack</h2>
    <ul>
        <li>Swift + UIKit</li>
        <li>URLSession for API networking</li>
        <li>Gemini AI (Google Generative AI)</li>
        <li>UserDefaults for storage</li>
        <li>MVC / MVVM Lite Architecture</li>
    </ul>

    <h2>🧠 Workflow</h2>
    <div class="box">
        <ol>
            <li>User enters ingredients</li>
            <li>Request sent to Gemini AI</li>
            <li>AI returns structured recipe JSON</li>
            <li>Recipes displayed in UI</li>
            <li>User saves favourites</li>
        </ol>
    </div>

    <h2>📱 Screens</h2>
    <ul>
        <li>Ingredient Input Screen</li>
        <li>AI Recipe List</li>
        <li>Recipe Detail View</li>
    </ul>

    <h2>📦 Installation</h2>
    <div class="code">
        git clone https://github.com/your-username/ChefMate.git
        
        cd ChefMate
        
        open ChefMate.xcodeproj
    </div>

    <h2>🔑 API Setup</h2>
    <p>Insert your Gemini API key inside <strong>APIManager.swift</strong>:</p>
    <div class="code">
        private let apiKey = "YOUR_GEMINI_API_KEY"
    </div>

    <h2>🎯 Future Enhancements</h2>
    <ul>
        <li>AI food image generation</li>
        <li>Voice recipe narration</li>
        <li>Recipe sharing & export</li>
        <li>Advanced filters & health modes</li>
    </ul>

    <div class="footer">
        <p>ChefMate • AI Recipe Generator App</p>
    </div>

</div>

</body>
</html>
```
