# news-of-the-galaxy
News of the Galaxy is a Star Wars podcast

### Installation requirements

- [RapidWeaver 7](https://www.realmacsoftware.com/rapidweaver/)
- [Stacks 3](yourhead.com/stacks/)

### Rapidweaver requirements

- Theme: Lander (MultiThemes)

### Podcast release

- Podcasts released to [podcasts.newsofthegalaxy.com](podcasts.newsofthegalaxy.com)
- [iTunes page](https://itunes.apple.com/us/podcast/news-of-the-galaxy/id1223840330?mt=2)

### Podcast page release requirements

- HTML page format:

      <strong>Episode Title</strong>
      <a>Download link</a>
      <p>Summary</p>
      
      Show Notes:
      <ul>
          <li>Item</li>
      </ul>

- Pages minified with: (https://www.willpeavy.com/minifier/)

### Rapidweaver Sidebar

- Title:

      News of the Galaxy <i class="fa fa-space-shuttle "></i>

- Sidebar:

      <a href="https://itunes.apple.com/us/podcast/news-of-the-galaxy/id1223840330?mt=2"><i class="fa fa-apple"></i> iTunes</a>
        
      <br/>
      <a href="https://www.teepublic.com/t-shirt/1823758-news-of-the-galaxy-all-colors?store_id=131595">Check out News of the Galaxy Swag on Tee Public</a>

- HTML Head:

      <script type="application/ld+json">
      {
          "@context": "http://schema.org",
          "@type": "Organization",
          "name": "News of the Galaxy"
          "url": "https://newsofthegalaxy.com",
          "logo": "https://newsofthegalaxy.com/logo.jpg"
      }
      </script>
      <!-- Global site tag (gtag.js) - Google Analytics -->
      <script async src="https://www.googletagmanager.com/gtag/js?id=UA-109208405-1"></script>
      <script>
          window.dataLayer = window.dataLayer || [];
          function gtag(){dataLayer.push(arguments);}
          gtag('js', new Date());
          
          gtag('config', 'UA-109208405-1');
      </script>

- Description:

      News of the Galaxy, a Star Wars Podcast, is a fan based Podcast out of Seattle, Washington and Washington, D.C.
      connor
