SlideUp Social Plugin
-----

A simple plugin to show social media link like (facebook,twitter,instagram) on your webpage footer when scroll down.

Available social sites right now
* facebook
* twitter
* instagram

Demo : [link](https://f4h3m.github.io/f4-slideup-social/ "Demo link")
-------------
How to use
-------------

In your index.html
  
  ```
<!-- Slideup social -->
  <div class="float-banner nav-down">
    <div class="float-container">
      <div class="float-row">
        <div class="floar-banner-wrap">
          <div class="btn-close" id="btn-close">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 40 40" enable-background="new 0 0 40 40">
              <line x1="5" y1="5" x2="35" y2="35" stroke="#fff" stroke-width="3" stroke-linecap="round"
                stroke-miterlimit="10"></line>
              <line x1="35" y1="5" x2="5" y2="35" stroke="#fff" stroke-width="3" stroke-linecap="round"
                stroke-miterlimit="10"></line>
            </svg>
          </div>
        </div>
      </div>
    </div>
  </div>

  ```
Also Add the js files 

```
<!-- js files -->
<script src="js/jquery-3.2.1.min.js"></script>
<script src="js/slideup-social.js"></script>

<script>
$(function () {
    $('.float-banner').floatbanner({
    // socialName: ['facebook', 'twitter', 'instagram'],
    // userName: ['f4h3m', 'f4h3m', 'f4h3m'],
    // socialUrl: ['#', '#', '#'],
    });
});
</script>

```

For the css style add slideup-social.css

```
  <link rel="stylesheet" href="css/slideup-social.css">
```

