<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>WP REST API MEDIA</title>
    <style>
      body {
        background-color: #338;
        color: white;
        text-align: center;
      }
      button {
        background-color: #f38;
        padding: 1em;
        border: thin solid;
        margin: 1em auto;
        display: block;
        cursor: pointer;
      }
      button:hover {
        background-color: #f3f;
      }
      .mansonry {
        columns: 5 10em;
        column-gap: 0.5em;
      }
      .mansonry img {
        max-width: 100%;
        margin-bottom: 0.5em;
        display: block;
        outline: 2px solid #fff4;
        /* outline-offset: -10px; */
      }
    </style>
  </head>
  <body>
    <h1>WP REST API MEDIA</h1>
    <div class="img-container mansonry"></div>
    <script>
      // https://asset.fgp.one/wp-json/wp/v2/media
      // https://asset.fgp.one/wp-json/wp/v2/media?per_page=9&page=1
      // https://blog.fgp.one/wp-json/wp/v2/posts/2385
      let div = document.querySelector("div");
      let pageUrl = "https://asset.fgp.one/";
      let per_page = 9;
      let page = 0;
      let cdn = "https://i0.wp.com/";

      const funcMedia = () => {
        // console.log(urlMedia);
        page++;
        let urlMedia = `${pageUrl}wp-json/wp/v2/media?per_page=${per_page}&page=${page}`;
        fetch(urlMedia)
          // fetch("https://asset.fgp.one/wp-json/wp/v2/media")
          .then((res) => (res.ok ? res.json() : Promise.reject(res)))
          .then((json) => {
            // console.log(json);
            // console.log(json[0].guid.rendered.split("https://")[1]);

            json.forEach((element) => {
              // console.log(element.guid.rendered);
              let img = document.createElement("img");
              img.src = cdn + element.guid.rendered.split("https://")[1];
              div.appendChild(img);
            });
          });
      };
      funcMedia();

      //
      // ========== Button functions... ==========
      window.addEventListener("scroll", (e) => {
        const { scrollTop, clientHeight, scrollHeight } = document.documentElement;
        // console.log(scrollTop, clientHeight, scrollHeight);
        // console.log(scrollTop + clientHeight);

        if (scrollTop + clientHeight >= scrollHeight) {
          console.log("ejecutar funcion");
          funcMedia();
        }
      });
      // ========== Button functions. ==========
    </script>
    <button onclick="funcMedia()">read more...</button>
  </body>
</html>
