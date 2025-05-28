# kaicrush
Template Streaming Anime Blogger

<h3>Dokumentasi</h3>

<h4>Header</h4>
<figure class="center">
  <img alt="header" src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEirdJ4VAN_mPzZwc7Wpkm9XIgS31ZY4qojmUKw0SGqKGrjbLbYSLgaICuaJDsYIPHfdArel8shq6xrYaRqQTFZCdedUkOg8_N_3Mkjjly1hGxKFZ2teY1_fgQIIIETG7STu1xu7jl40l6LfGCR2zIku-Jrcfti8yFBFzVWkU4xoDZoMM3ZlymtteaVtcRdK/s625/header.png">
</figure>


<h4>Custom Post</h4>
<figure class="center">
  <img alt="custompost" src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEjpEHqZjWsNRUsTrRTNUv6X3_K9VogZd-de7JJx99CSnrAc7Awojeak3Evr_aXlBDEgOrotJJnq-kzB4JYRmU5IME7BsgCCiU3eilXz-hWFkEMJOMn7TymgNMm_ktluI20KmfrfDS0E8A7_l1W0hP9Cc0GNsrpSR41D9iZCvTwj97WRoqJ9dQNHzoBhBd7x/s436/custom%20post.png">
</figure>

<ul>
  <li><code>label</code>: You can replace it with another label</li>
  <li><code>sort</code>: You can replace (published or updated)</li>
  <li><code>num</code>: you can change the number (max post)</li>
  <li><code>outputscore</code>: don't change it</li>
</ul>

<h3>Format Post</h3>
<pre class='html'><code>&lt;!-- [  Sinopsis  ] --&gt;
&lt;div class=&#039;synopsis&#039;&gt;
&lt;p&gt;SINOPSIS&lt;/p&gt;
&lt;/div&gt;
&lt;span&gt;&lt;a name=&quot;more&quot;&gt;&lt;/a&gt;&lt;/span&gt;

&lt;!--[  Thumbnail ]--&gt;


&lt;script&gt;
const schedule = &#039;2025-03-08T23:30:00&#039;;
const config = {
    eInfo: {
        cover: &#039;&#039;,
        japanese: &#039;JAPANESE&#039;,
        aired: &#039;AIRED&#039;,
        duration: &#039;DURATION&#039;,
        episodes: &#039;MAX_EPISODES&#039;,
        producers: &#039;PRODUCER&#039;,
    }
};
  
  const episodes = [
    {
        episode: &#039;01&#039;,
        servers: [
            { sub: 'NAME_SERVER', value: 'LINK' },
            { sub: 'NAME_SERVER', value: 'LINK' },
            { dub: 'NAME_SERVER', value: 'LINK' },
        ]
    },

     ADD_EPISODE_HERE 
    
];
&lt;/script&gt;</code>
</pre>
<p>if you want to add stream episodes</p>
<pre><code>{
        episode: '04',
        servers: [
            { sub: 'NAME_SERVER', value: 'LINK' },
            { sub: 'NAME_SERVER', value: 'LINK' },
        ]
    },</code></pre>

<h4>Label Example</h4>
<figure class="center">
  <img alt="SS" src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEhXFZaLbAwtTV8JwfSb2HMeR6C0GRxO00ou0I4f0tGOf3NvkJshyFFlk8vJJ1h1gIZBkbl892AS0F8Mo_YoQVi5FKQMaMK2UCJl6rcJvYSm0cjYyNdYvfKkuzKjP3CxHMK7-8Jm9fGrZW8L-HfFHqWs6nW8_zzxeze-O8qdI4PXFXo74pzj2PXXZe4TgijT/s542/contoh%20label.png">
</figure>
