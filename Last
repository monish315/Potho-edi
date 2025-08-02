<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Free online image compression tool to reduce file size while maintaining quality. Supports JPG, PNG, and WebP formats.">
    <meta name="keywords" content="image compressor, reduce image size, optimize images, free image tool, web optimization">
    <meta name="author" content="ImageCompressorPro">
    <meta name="robots" content="index, follow">
    <title>ImageCompressorPro - Free Online Image Compression Tool</title>
    <link rel="canonical" href="https://www.yourdomain.com/image-compressor" />
    
    <!-- Open Graph / Social Media Meta Tags -->
    <meta property="og:title" content="ImageCompressorPro - Free Online Image Compression Tool">
    <meta property="og:description" content="Reduce image file size without losing quality. Supports JPG, PNG, and WebP formats.">
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://www.yourdomain.com/image-compressor">
    <meta property="og:image" content="https://www.yourdomain.com/images/compressor-preview.jpg">
    
    <!-- Favicon -->
    <link rel="icon" href="favicon.ico" type="image/x-icon">
    
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;500;700&display=swap" rel="stylesheet">
    
    <style>
        :root {
            --primary-color: #4285f4;
            --secondary-color: #34a853;
            --accent-color: #ea4335;
            --light-gray: #f5f5f5;
            --dark-gray: #333;
            --medium-gray: #757575;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Roboto', sans-serif;
            line-height: 1.6;
            color: var(--dark-gray);
            background-color: #f9f9f9;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }
        
        header {
            background-color: white;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
            padding: 15px 0;
            position: sticky;
            top: 0;
            z-index: 100;
        }
        
        .header-content {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        
        .logo {
            font-size: 24px;
            font-weight: 700;
            color: var(--primary-color);
            text-decoration: none;
        }
        
        .logo span {
            color: var(--accent-color);
        }
        
        nav ul {
            display: flex;
            list-style: none;
        }
        
        nav ul li {
            margin-left: 20px;
        }
        
        nav ul li a {
            text-decoration: none;
            color: var(--dark-gray);
            font-weight: 500;
            transition: color 0.3s;
        }
        
        nav ul li a:hover {
            color: var(--primary-color);
        }
        
        main {
            padding: 40px 0;
        }
        
        .hero {
            text-align: center;
            margin-bottom: 40px;
        }
        
        .hero h1 {
            font-size: 2.5rem;
            margin-bottom: 15px;
            color: var(--dark-gray);
        }
        
        .hero p {
            font-size: 1.1rem;
            color: var(--medium-gray);
            max-width: 700px;
            margin: 0 auto 25px;
        }
        
        .compressor-container {
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
            padding: 30px;
            margin-bottom: 30px;
        }
        
        .upload-area {
            border: 2px dashed #ccc;
            border-radius: 6px;
            padding: 40px;
            text-align: center;
            cursor: pointer;
            transition: all 0.3s;
            margin-bottom: 25px;
        }
        
        .upload-area:hover {
            border-color: var(--primary-color);
            background-color: rgba(66, 133, 244, 0.05);
        }
        
        .upload-area.active {
            border-color: var(--secondary-color);
            background-color: rgba(52, 168, 83, 0.05);
        }
        
        .upload-icon {
            font-size: 48px;
            color: var(--primary-color);
            margin-bottom: 15px;
        }
        
        .controls {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            margin-bottom: 25px;
        }
        
        .control-group {
            flex: 1;
            min-width: 250px;
        }
        
        .control-group label {
            display: block;
            margin-bottom: 8px;
            font-weight: 500;
        }
        
        .slider-container {
            display: flex;
            align-items: center;
            gap: 15px;
        }
        
        .slider {
            flex: 1;
            -webkit-appearance: none;
            height: 8px;
            border-radius: 4px;
            background: #ddd;
            outline: none;
        }
        
        .slider::-webkit-slider-thumb {
            -webkit-appearance: none;
            appearance: none;
            width: 18px;
            height: 18px;
            border-radius: 50%;
            background: var(--primary-color);
            cursor: pointer;
        }
        
        .slider-value {
            width: 40px;
            text-align: center;
            font-weight: 500;
        }
        
        select {
            width: 100%;
            padding: 10px;
            border: 1px solid #ddd;
            border-radius: 4px;
            font-size: 16px;
            background-color: white;
        }
        
        .buttons {
            display: flex;
            gap: 15px;
            margin-top: 20px;
        }
        
        button {
            padding: 12px 24px;
            border: none;
            border-radius: 4px;
            font-size: 16px;
            font-weight: 500;
            cursor: pointer;
            transition: all 0.3s;
        }
        
        .btn-primary {
            background-color: var(--primary-color);
            color: white;
            flex: 1;
        }
        
        .btn-primary:hover {
            background-color: #3367d6;
        }
        
        .btn-secondary {
            background-color: var(--light-gray);
            color: var(--dark-gray);
            flex: 1;
        }
        
        .btn-secondary:hover {
            background-color: #e0e0e0;
        }
        
        .results {
            display: none;
            margin-top: 30px;
            padding-top: 30px;
            border-top: 1px solid #eee;
        }
        
        .comparison {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            margin-bottom: 30px;
        }
        
        .image-box {
            flex: 1;
            min-width: 300px;
            text-align: center;
        }
        
        .image-box img {
            max-width: 100%;
            height: auto;
            border-radius: 4px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
        }
        
        .image-info {
            margin-top: 10px;
            font-size: 14px;
            color: var(--medium-gray);
        }
        
        .stats {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            gap: 15px;
            margin-bottom: 30px;
        }
        
        .stat-card {
            background-color: var(--light-gray);
            padding: 15px;
            border-radius: 6px;
            text-align: center;
            flex: 1;
            min-width: 150px;
        }
        
        .stat-card h3 {
            font-size: 14px;
            color: var(--medium-gray);
            margin-bottom: 5px;
        }
        
        .stat-card p {
            font-size: 18px;
            font-weight: 500;
            color: var(--dark-gray);
        }
        
        .download-btn {
            text-align: center;
            margin-top: 20px;
        }
        
        .ad-container {
            margin: 30px 0;
            text-align: center;
            background-color: var(--light-gray);
            padding: 20px;
            border-radius: 6px;
        }
        
        .ad-label {
            font-size: 12px;
            color: var(--medium-gray);
            margin-bottom: 10px;
            text-transform: uppercase;
            letter-spacing: 1px;
        }
        
        footer {
            background-color: var(--dark-gray);
            color: white;
            padding: 30px 0;
            text-align: center;
        }
        
        .footer-content {
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        
        .footer-links {
            display: flex;
            gap: 20px;
            margin: 20px 0;
        }
        
        .footer-links a {
            color: white;
            text-decoration: none;
        }
        
        .footer-links a:hover {
            text-decoration: underline;
        }
        
        .copyright {
            font-size: 14px;
            color: #aaa;
        }
        
        @media (max-width: 768px) {
            .header-content {
                flex-direction: column;
                gap: 15px;
            }
            
            nav ul {
                flex-wrap: wrap;
                justify-content: center;
            }
            
            nav ul li {
                margin: 0 10px;
            }
            
            .hero h1 {
                font-size: 2rem;
            }
            
            .upload-area {
                padding: 30px 15px;
            }
            
            .controls {
                flex-direction: column;
                gap: 15px;
            }
            
            .buttons {
                flex-direction: column;
            }
        }
        
        /* Loading spinner */
        .spinner {
            display: none;
            width: 40px;
            height: 40px;
            margin: 20px auto;
            border: 4px solid rgba(0, 0, 0, 0.1);
            border-radius: 50%;
            border-top-color: var(--primary-color);
            animation: spin 1s ease-in-out infinite;
        }
        
        @keyframes spin {
            to { transform: rotate(360deg); }
        }
        
        /* Tooltip */
        .tooltip {
            position: relative;
            display: inline-block;
            margin-left: 5px;
            cursor: help;
        }
        
        .tooltip .tooltiptext {
            visibility: hidden;
            width: 200px;
            background-color: #555;
            color: #fff;
            text-align: center;
            border-radius: 6px;
            padding: 5px;
            position: absolute;
            z-index: 1;
            bottom: 125%;
            left: 50%;
            margin-left: -100px;
            opacity: 0;
            transition: opacity 0.3s;
            font-size: 14px;
            font-weight: normal;
        }
        
        .tooltip:hover .tooltiptext {
            visibility: visible;
            opacity: 1;
        }
    </style>
</head>
<body>
    <header>
        <div class="container header-content">
            <a href="/" class="logo">Image<span>Compressor</span>Pro</a>
            <nav>
                <ul>
                    <li><a href="/">Home</a></li>
                    <li><a href="/features">Features</a></li>
                    <li><a href="/blog">Blog</a></li>
                    <li><a href="/contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>
    
    <main class="container">
        <!-- Top Ad Banner -->
        <div class="ad-container">
            <div class="ad-label">Advertisement</div>
            <!-- Replace with your Google AdSense code -->
            <script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-YOUR_PUBLISHER_ID"
                crossorigin="anonymous"></script>
            <!-- ImageCompressor_Top_Banner -->
            <ins class="adsbygoogle"
                style="display:block"
                data-ad-client="ca-pub-YOUR_PUBLISHER_ID"
                data-ad-slot="YOUR_AD_SLOT_ID"
                data-ad-format="auto"
                data-full-width-responsive="true"></ins>
            <script>
                (adsbygoogle = window.adsbygoogle || []).push({});
            </script>
        </div>
        
        <section class="hero">
            <h1>Compress Images Online for Free</h1>
            <p>Reduce image file size without losing quality. Supports JPG, PNG, and WebP formats. Perfect for websites, social media, and email attachments.</p>
        </section>
        
        <section class="compressor-container">
            <div class="upload-area" id="uploadArea">
                <div class="upload-icon">📁</div>
                <h2>Drag & Drop Your Images Here</h2>
                <p>or click to browse files</p>
                <input type="file" id="fileInput" accept="image/*" style="display: none;">
            </div>
            
            <div class="controls">
                <div class="control-group">
                    <label for="compressionLevel">Compression Level 
                        <span class="tooltip">?
                            <span class="tooltiptext">Higher values mean smaller files but lower quality</span>
                        </span>
                    </label>
                    <div class="slider-container">
                        <input type="range" min="0" max="100" value="70" class="slider" id="compressionLevel">
                        <span class="slider-value" id="compressionValue">70</span>
                    </div>
                </div>
                
                <div class="control-group">
                    <label for="outputFormat">Output Format</label>
                    <select id="outputFormat">
                        <option value="auto">Auto (Recommended)</option>
                        <option value="jpeg">JPEG</option>
                        <option value="png">PNG</option>
                        <option value="webp">WebP (Modern)</option>
                    </select>
                </div>
            </div>
            
            <div class="buttons">
                <button class="btn-primary" id="compressBtn">Compress Image</button>
                <button class="btn-secondary" id="resetBtn">Reset</button>
            </div>
            
            <div class="spinner" id="spinner"></div>
            
            <div class="results" id="results">
                <div class="comparison">
                    <div class="image-box">
                        <h3>Original Image</h3>
                        <img id="originalImage" src="" alt="Original image">
                        <div class="image-info" id="originalInfo"></div>
                    </div>
                    <div class="image-box">
                        <h3>Compressed Image</h3>
                        <img id="compressedImage" src="" alt="Compressed image">
                        <div class="image-info" id="compressedInfo"></div>
                    </div>
                </div>
                
                <div class="stats">
                    <div class="stat-card">
                        <h3>File Size Reduction</h3>
                        <p id="reductionPercent">0%</p>
                    </div>
                    <div class="stat-card">
                        <h3>Original Size</h3>
                        <p id="originalSize">0 KB</p>
                    </div>
                    <div class="stat-card">
                        <h3>Compressed Size</h3>
                        <p id="compressedSize">0 KB</p>
                    </div>
                </div>
                
                <div class="download-btn">
                    <button class="btn-primary" id="downloadBtn">Download Compressed Image</button>
                </div>
            </div>
        </section>
        
        <!-- Middle Ad Banner -->
        <div class="ad-container">
            <div class="ad-label">Advertisement</div>
            <!-- Replace with your Google AdSense code -->
            <script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-YOUR_PUBLISHER_ID"
                crossorigin="anonymous"></script>
            <!-- ImageCompressor_Mid_Banner -->
            <ins class="adsbygoogle"
                style="display:block"
                data-ad-client="ca-pub-YOUR_PUBLISHER_ID"
                data-ad-slot="YOUR_AD_SLOT_ID_2"
                data-ad-format="auto"
                data-full-width-responsive="true"></ins>
            <script>
                (adsbygoogle = window.adsbygoogle || []).push({});
            </script>
        </div>
        
        <section class="info-section">
            <h2>Why Compress Your Images?</h2>
            <p>Image compression is essential for faster website loading, better SEO rankings, and improved user experience. Our tool helps you find the perfect balance between quality and file size.</p>
            
            <h3>How to Use This Tool</h3>
            <ol>
                <li>Upload your image by dragging and dropping or clicking to browse</li>
                <li>Adjust the compression level using the slider</li>
                <li>Select your preferred output format (or leave on Auto)</li>
                <li>Click "Compress Image" and wait a few seconds</li>
                <li>Download your optimized image</li>
            </ol>
            
            <h3>Supported Formats</h3>
            <ul>
                <li><strong>JPEG</strong> - Best for photographs and complex images</li>
                <li><strong>PNG</strong> - Best for graphics with transparency</li>
                <li><strong>WebP</strong> - Modern format with superior compression</li>
            </ul>
        </section>
        
        <!-- Bottom Ad Banner -->
        <div class="ad-container">
            <div class="ad-label">Advertisement</div>
            <!-- Replace with your Google AdSense code -->
            <script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-YOUR_PUBLISHER_ID"
                crossorigin="anonymous"></script>
            <!-- ImageCompressor_Bottom_Banner -->
            <ins class="adsbygoogle"
                style="display:block"
                data-ad-client="ca-pub-YOUR_PUBLISHER_ID"
                data-ad-slot="YOUR_AD_SLOT_ID_3"
                data-ad-format="auto"
                data-full-width-responsive="true"></ins>
            <script>
                (adsbygoogle = window.adsbygoogle || []).push({});
            </script>
        </div>
    </main>
    
    <footer>
        <div class="container footer-content">
            <a href="/" class="logo" style="color: white;">Image<span style="color: #fbbc05;">Compressor</span>Pro</a>
            <div class="footer-links">
                <a href="/privacy">Privacy Policy</a>
                <a href="/terms">Terms of Service</a>
                <a href="/contact">Contact Us</a>
                <a href="/blog">Blog</a>
            </div>
            <p class="copyright">© 2023 ImageCompressorPro. All rights reserved.</p>
        </div>
    </footer>
    
    <script>
        // DOM Elements
        const uploadArea = document.getElementById('uploadArea');
        const fileInput = document.getElementById('fileInput');
