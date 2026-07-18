<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>AI Prompt Generator Pro</title>
<meta name="description" content="Generate professional AI prompts for ChatGPT, Gemini, Claude, Midjourney and more.">

<link rel="stylesheet" href="style.css">
</head>

<body>

<header>
    <h1>🤖 AI Prompt Generator Pro</h1>
    <p>Create powerful AI prompts instantly</p>
</header>


<div class="container">

    <div class="box">

        <label>Category</label>

        <select id="category">
            <option value="blog">Blog Writing</option>
            <option value="seo">SEO Content</option>
            <option value="youtube">YouTube Script</option>
            <option value="marketing">Marketing</option>
            <option value="image">AI Image Prompt</option>
            <option value="coding">Coding</option>
        </select>


        <label>Your Topic</label>

        <input 
        type="text" 
        id="topic"
        placeholder="Enter your topic...">


        <label>Tone</label>

        <select id="tone">
            <option>Professional</option>
            <option>Creative</option>
            <option>Friendly</option>
            <option>Expert</option>
        </select>


        <button onclick="generatePrompt()">
            ⚡ Generate Prompt
        </button>


        <textarea 
        id="result"
        placeholder="Your AI prompt will appear here..."
        readonly></textarea>


        <div class="buttons">

            <button onclick="copyPrompt()">
                📋 Copy
            </button>

            <button onclick="downloadPrompt()">
                📥 Download
            </button>

        </div>

    </div>

</div>


<footer>
<p>© 2026 AI Prompt Generator Pro</p>
</footer>


<script src="prompts.js"></script>
<script src="script.js"></script>

</body>
</html>
