<a href="https://github.com/sudo-self/moodylass/fork">CREATE FORK</a>

![AmazingMoodylass](https://github.com/user-attachments/assets/71418a80-da76-415f-b53f-3f0afca06b12)


## Updates

--development <a href="https://moodylasss.pages.dev">moodylasss.pages.dev</a>

--CNAME dns Record

<img width="637" alt="Screenshot 2024-10-11 at 12 42 34 AM" src="https://github.com/user-attachments/assets/a3661671-72e8-4e43-9200-8332b0018807"><br>

--Download&nbsp;[Moodylass.pdf](https://github.com/user-attachments/files/17339017/Moodylass.pdf)

--View:&nbsp;<a href="https://github.com/sudo-self/moodylass/blob/main/Moodylass.pdf">Moodylass.pdf</a>

--changing anchor tags to < video > allows local playback "/tea.mp4"

```
<p class="MoodyLassHeadingCxSpLast">
      A valuable lesson about Consent, shared by Moody Lass, and brought to you
      by the English with Tea.
    </p>
    <p class="MoodyLassHeadingCxSpLast">
    <video width="300" height="200" controls>
        <source src="./tea.mp4" type="video/mp4">
        Your browser does not support the video tag.
    </video>

    </p>

```
--added light grey gradient across body

```

body {
    background: linear-gradient(to bottom, rgba(255, 255, 255, 1), rgba(240, 240, 240, 1)); 
}

```
--could set the thumbnail with the poster attribute inside controls 

```
  <video width="300" height="200" controls poster="./YOUR_PHOTO_HERE.jpg"

```

<img width="1209" alt="Screenshot 2024-10-11 at 5 26 41 AM" src="https://github.com/user-attachments/assets/48ffc73b-a3a2-4243-80ef-5303ea6ec740">



-- Style to match current theme with css

```

.MoodyLassHeadingCxSpLast {
  color: #333;
  background-color: #f9f9f9;
  padding: 10px;
  border-radius: 8px;
  box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.3);
  text-align: center;
  max-width: 320px;
  margin: 20px auto;
  font-family: "Arial", sans-serif;
}

video {
  box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.3);
  border-radius: 8px;
  margin-top: 10px;
}

```


--icon set meta 

![icon-round-32x32](https://github.com/user-attachments/assets/55a7b2a8-1363-44a8-a684-1252e1c1cd5c)

![icon-round-64x64](https://github.com/user-attachments/assets/3bb16a65-4813-4e7a-9015-149301cbc759)

![favicon](https://github.com/user-attachments/assets/4a867f1a-802b-44ff-821f-4a1a34697bf4)

![apple-touch-icon](https://github.com/user-attachments/assets/ee0cecca-c3ff-40b7-a920-bfba6aa53813)

![icon-round-196x196](https://github.com/user-attachments/assets/c25a232d-001b-4f26-b022-e6d91eae03f1)

![icon-round-196x196](https://github.com/user-attachments/assets/5621c334-547a-43e0-bcf3-ddceacbc812f)

![icon192](https://github.com/user-attachments/assets/8884731d-c918-46a7-9550-5b164d67e446)

![icon512](https://github.com/user-attachments/assets/1139a86b-9dbc-457e-92e1-78f310c8fc75)


--.mp4 local 

https://github.com/user-attachments/assets/1764a431-e8f7-4d6b-960c-c63acce92806


 -added "moodylassLOGO.svg" resolves <a href="https://moodylass.com/moodylassLOGO.svg">/moodylassLOGO.svg</a>

 -added "sitemap.xml" 

 ```
<?xml version="1.0" encoding="UTF-8"?>
<urlset>
  <url>
    <loc>https://moodylass.com/</loc>
    <lastmod>2024-10-11T06:27:21.393Z</lastmod>
    <changefreq>daily</changefreq>
    <priority>0.7</priority>
  </url>
</urlset>

```

--DYNAMIC SEO HEADER

```
<!doctype html>
<html>

<head>
    <!-- Favicon and Icons -->
    <link rel="shortcut icon" href="favicon.ico" />                                         
    <link rel="icon" type="image/x-icon" sizes="16x16 32x32" href="favicon.ico" />        
    <link rel="apple-touch-icon" sizes="any" href="apple-touch-icon.png" />               
    <link rel="icon" sizes="32x32" href="favicon.png" />
    <link rel="icon" sizes="192x192" href="icon192.png" />                            
    <meta name="msapplication-TileColor" content="#FFFFFF" />
    <meta name="msapplication-TileImage" content="favicon.png" />
    <meta name="theme-color" content="#ffffff" />

    <!-- Manifest -->
    <link rel="manifest" href="manifest.json" />            

    <!-- Meta Information -->
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
    <meta name="author" content="Lani Krewson" />

    <!-- Page Title -->
    <title> Moodylass | Freelance Muse and Writer </title>
    <meta name="title" content="Moodylass | Freelance Muse and Writer" />
    <meta name="description" content="A pseudo-advice column for simple solutions to complicated life problems using knowledge, experience, and a cup of tea." />

    <!-- Open Graph Meta Tags -->
    <meta property="og:type" content="website" />
    <meta property="og:url" content="https://moodylass.com" />
    <meta property="og:title" content="Moodylass | Freelance Muse and Writer" />
    <meta property="og:description" content="A pseudo-advice column for simple solutions to complicated life problems using knowledge, experience, and a cup of tea." />
    <meta property="og:image" content="https://moodylass.com/moodylassLOGO.svg" />

    <!-- Twitter Meta Tags -->
    <meta property="twitter:card" content="summary_large_image" />
    <meta property="twitter:url" content="https://moodylass.com" />
    <meta property="twitter:title" content="Moodylass | Freelance Muse and Writer" />
    <meta property="twitter:description" content="A pseudo-advice column for simple solutions to complicated life problems using knowledge, experience, and a cup of tea." />
    <meta property="twitter:image" content="https://moodylass.com/moodylassLOGO.svg" />
      
    <!-- DYNAMIC SEO -->
    <script>
        fetch('/seo.json')
            .then(response => response.json())
            .then(data => {
                document.title = data.title;
                document.querySelector('meta[name="description"]').setAttribute('content', data.description);
                document.querySelector('meta[name="author"]').setAttribute('content', data.author);
                document.querySelector('meta[name="theme-color"]').setAttribute('content', data.themeColor);

                // Set Open Graph meta tags
                document.querySelector('meta[property="og:title"]').setAttribute('content', data.openGraph.title);
                document.querySelector('meta[property="og:description"]').setAttribute('content', data.openGraph.description);
                document.querySelector('meta[property="og:url"]').setAttribute('content', data.openGraph.url);
                document.querySelector('meta[property="og:image"]').setAttribute('content', data.openGraph.image);

                // Set Twitter meta tags
                document.querySelector('meta[property="twitter:title"]').setAttribute('content', data.twitter.title);
                document.querySelector('meta[property="twitter:description"]').setAttribute('content', data.twitter.description);
                document.querySelector('meta[property="twitter:url"]').setAttribute('content', data.twitter.url);
                document.querySelector('meta[property="twitter:image"]').setAttribute('content', data.twitter.image);
            })
            .catch(error => console.error('Error loading SEO data:', error));
    </script>
</head>

```

![Dynamic Header](https://github.com/user-attachments/assets/da1e798a-60eb-435b-9100-cb99e6385051)



