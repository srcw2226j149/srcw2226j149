<!DOCTYPE html>
<html lang="en" dir="ltr">

<head>
  <title></title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="css/style.css">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
</head>

<body>

  <header>
    <div class="container">
      <div class="navbar">
        <div class="logo">
          <h2>Tattoo House</h2>
        </div>

        <nav>
          <ul id="menuitem">
            <li class="active"><a href="index.html">HOME</a></li>
            <li><a href="index.html">ABOUT</a></li>
            <li><a href="contact.html">GALLERY</a></li>
            <li><a href="account.html">TESTIMONIAL</a></li>
            <li><a href="account.html">SERVICES</a></li>
            <i class="fa fa-search"></i>
          </ul>
        </nav>
        <span class="fa fa-bars" onclick="menutoggle()"></span>
      </div>

      <div class="home flex">
        <div class="left">
          <h2>Best Tattoos</h2>
          <p> Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
          <button>Read More</button>
          <div class="dots flex">
            <label></label>
            <label></label>
            <label></label>
          </div>
        </div>
        <div class="right">
          <div class="img">
            <img src="image/h.png" alt="">
          </div>
        </div>
      </div>
    </div>
  </header>





  <script>
    var menuitem = document.getElementById("menuitem");
    menuitem.style.maxHeight = "0px";

    function menutoggle() {
      if (menuitem.style.maxHeight == '0px') {
        menuitem.style.maxHeight = "200px"
      } else {
        menuitem.style.maxHeight = "0px"
      }
    }

    window.addEventListener("scroll", function() {
      var header = document.querySelector("header");
      header.classList.toggle("sticky", window.scrollY > 0);
    })
  </script>


  <section class="about">
    <div class="container">
      <h2>What We Do</h2>
      <div class="grid">
        <div class="item">
          <svg xmlns="http://www.w3.org/2000/svg" x="0px" y="0px" width="50" height="50" viewBox="0 0 172 172" style=" fill:#000000;">
            <g fill="none" fill-rule="nonzero" stroke="none" stroke-width="1" stroke-linecap="butt" stroke-linejoin="miter" stroke-miterlimit="10" stroke-dasharray="" stroke-dashoffset="0" font-family="none" font-weight="none" font-size="none"
              text-anchor="none" style="mix-blend-mode: normal">
              <path d="M0,172v-172h172v172z" fill="none"></path>
              <g fill="#0e6c66">
                <path
                  d="M137.6,20.64c-4.44781,0 -8.23719,2.9025 -9.675,6.88h-2.66062l-4.15219,-4.15219c-0.645,-0.67188 -1.53187,-1.03469 -2.4725,-1.03469c-1.3975,0 -2.64719,0.84656 -3.18469,2.13656c-0.52406,1.30344 -0.215,2.78156 0.79281,3.7625l9.60781,9.60781l-3.80281,3.80281l-0.65844,-0.65844c-1.38406,-1.38406 -3.30563,-1.59906 -4.73,-1.30344c-1.42438,0.29563 -2.63375,0.99438 -3.64156,2.01563v0.01344l-19.71281,19.69938c-1.02125,1.02125 -1.73344,2.23062 -2.02906,3.655c-0.29562,1.42437 -0.06719,3.34594 1.31688,4.73l0.645,0.65844l-3.80281,3.80281l-2.01562,-2.01563l2.72781,-2.72781l-4.86437,-4.86437l-1.72,1.72l-8.89563,-8.89563l3.44,-3.44l-4.86437,-4.86437l-4.44781,4.44781l-2.72781,-2.72781c-0.86,-0.90031 -2.15,-1.26313 -3.34594,-0.94063c-1.20937,0.30906 -2.15,1.24969 -2.45906,2.45906c-0.3225,1.19594 0.04031,2.48594 0.94063,3.34594l2.72781,2.72781l-4.44781,4.44781l4.86437,4.86437l3.44,-3.44l8.89563,8.89563l-1.00781,1.00781l-2.01562,-2.01563c-1.33031,-1.33031 -3.09063,-2.00219 -4.86438,-1.98875c-1.77375,0 -3.53406,0.65844 -4.86437,1.98875l-29.53563,29.53563c-2.66062,2.66062 -2.66062,7.06812 0,9.72875l1.00781,1.00781l-18.20781,18.20781l1.72,1.72l-8.6,8.6l-6.88,10.32l10.32,-6.88l8.6,-8.6l1.72,1.72l18.20781,-18.20781l1.00781,1.00781c2.66062,2.66063 7.06812,2.66063 9.72875,0l29.53562,-29.53562c2.66063,-2.66063 2.66063,-7.06813 0,-9.72875l-2.01562,-2.01563l2.01562,-2.01562l40.27219,40.27219l4.86438,-4.86438c-1.37063,-1.37062 -1.37063,-3.49375 0,-4.86437l31.55125,-31.55125c1.37062,-1.37063 3.49375,-1.37063 4.86437,0l4.86438,-4.86438l-2.60688,-2.60687c1.10188,-0.41656 1.92156,-1.37063 2.16344,-2.52625c0.24187,-1.15563 -0.13438,-2.35156 -0.98094,-3.17125l-3.44,-3.44c-0.645,-0.67188 -1.53187,-1.03469 -2.4725,-1.04813c-1.42437,0.01344 -2.71437,0.90031 -3.21156,2.24406l-19.53813,-19.52469c3.88344,-0.51063 7.095,-3.17125 8.385,-6.75906h7.525v-6.88h-7.525c-1.43781,-3.9775 -5.22719,-6.88 -9.675,-6.88zM137.6,27.52c1.935,0 3.44,1.505 3.44,3.44c0,1.935 -1.505,3.44 -3.44,3.44c-1.935,0 -3.44,-1.505 -3.44,-3.44c0,-1.935 1.505,-3.44 3.44,-3.44zM130.72,42.70438l12.33563,12.33562l-3.80281,3.80281l-0.65844,-0.65844c-1.38406,-1.38406 -3.30563,-1.59906 -4.73,-1.30344c-1.42438,0.29563 -2.63375,0.99438 -3.64156,2.01563v0.01344l-19.71281,19.69938c-1.02125,1.02125 -1.73344,2.23062 -2.02906,3.655c-0.29562,1.42437 -0.06719,3.34594 1.31688,4.73l0.645,0.65844l-3.80281,3.80281l-12.33562,-12.33563l3.80281,-3.80281l0.65844,0.645c1.38406,1.38406 3.31906,1.6125 4.74344,1.31688c1.41094,-0.29563 2.62031,-1.00781 3.62812,-2.02906h0.01344l19.69937,-19.71281c1.02125,-1.00781 1.73344,-2.21719 2.02906,-3.64156c0.29562,-1.42438 0.06719,-3.34594 -1.30344,-4.71656v-0.01344l-0.65844,-0.65844zM117.56469,46.88344l4.11188,4.11188l-19.06781,19.08125l-4.12531,-4.12531zM147.92,59.90438l7.17563,7.17562l-36.41563,36.41563l-7.17562,-7.17563l3.80281,-3.80281l0.65844,0.645c1.38406,1.38406 3.31906,1.6125 4.74344,1.31688c1.41094,-0.29563 2.62031,-1.00781 3.62812,-2.02906h0.01344l19.69937,-19.71281c1.02125,-1.00781 1.73344,-2.21719 2.02906,-3.64156c0.29562,-1.42438 0.06719,-3.34594 -1.30344,-4.71656v-0.01344l-0.65844,-0.65844zM134.76469,64.08344l4.11188,4.11188l-19.06781,19.08125l-4.12531,-4.12531zM68.8,77.10438l8.89563,8.89562l-29.53563,29.53563l-8.89562,-8.89563z">
                </path>
              </g>
            </g>
          </svg>
          <h2>Tattooing</h2>
          <p> Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
        </div>
        <div class="item">
          <svg xmlns="http://www.w3.org/2000/svg" x="0px" y="0px" width="30" height="30" viewBox="0 0 172 172" style=" fill:#000000;">
            <g fill="none" fill-rule="nonzero" stroke="none" stroke-width="1" stroke-linecap="butt" stroke-linejoin="miter" stroke-miterlimit="10" stroke-dasharray="" stroke-dashoffset="0" font-family="none" font-weight="none" font-size="none"
              text-anchor="none" style="mix-blend-mode: normal">
              <path d="M0,172v-172h172v172z" fill="none"></path>
              <g fill="#0e6c66">
                <path
                  d="M85.91042,11.38828c-3.16203,0.04943 -5.68705,2.6496 -5.64375,5.81172v12.54167c-6.63536,2.39286 -11.46667,8.71089 -11.46667,16.125c0,2.84614 0.77969,5.49664 2.02683,7.87214l-23.26927,49.4612h-18.89089c-2.06765,-0.02924 -3.99087,1.05709 -5.03322,2.843c-1.04236,1.78592 -1.04236,3.99474 0,5.78066c1.04236,1.78592 2.96558,2.87225 5.03322,2.843h13.49349l-13.49349,28.66667v5.73333l5.73333,5.73333l5.73333,-5.73333v-4.44558l15.74427,-29.95442h24.38906v5.73333c-0.02924,2.06765 1.05709,3.99087 2.843,5.03322c1.78592,1.04236 3.99474,1.04236 5.78066,0c1.78592,-1.04236 2.87225,-2.96558 2.843,-5.03322v-5.73333h24.38906l15.74427,29.95442v4.44558l5.73333,5.73333l5.73333,-5.73333v-5.73333l-13.49349,-28.66667h13.49349c2.06765,0.02924 3.99087,-1.05709 5.03322,-2.843c1.04236,-1.78592 1.04236,-3.99474 0,-5.78066c-1.04236,-1.78592 -2.96558,-2.87225 -5.03322,-2.843h-18.89089l-23.26927,-49.4612c1.24713,-2.37549 2.02683,-5.026 2.02683,-7.87214c0,-7.41411 -4.83131,-13.73214 -11.46667,-16.125v-12.54167c0.02122,-1.54972 -0.58581,-3.04203 -1.68279,-4.1369c-1.09698,-1.09487 -2.59045,-1.69903 -4.14013,-1.67482zM85.67526,40.20052c0.22004,0.0127 0.44064,0.0127 0.66068,0c3.05911,0.17655 5.39739,2.55205 5.39739,5.66615c0,3.23434 -2.49899,5.73333 -5.73333,5.73333c-3.23434,0 -5.73333,-2.49899 -5.73333,-5.73333c0,-3.11796 2.34386,-5.49497 5.40859,-5.66615zM83.14453,62.77552c0.93379,0.15968 1.87928,0.29114 2.85547,0.29114c0.97619,0 1.92168,-0.13147 2.85547,-0.29114l21.24245,40.42448h-18.36458v-5.73333c0.02122,-1.54972 -0.58581,-3.04203 -1.68279,-4.1369c-1.09698,-1.09487 -2.59045,-1.69903 -4.14013,-1.67482c-3.16203,0.04943 -5.68705,2.6496 -5.64375,5.81172v5.73333h-18.36458z">
                </path>
              </g>
            </g>
          </svg>
          <h2>Piercing</h2>
          <p> Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
        </div>
        <div class="item">
          <svg xmlns="http://www.w3.org/2000/svg" x="0px" y="0px" width="64" height="64" viewBox="0 0 172 172" style=" fill:#000000;">
            <g fill="none" fill-rule="nonzero" stroke="none" stroke-width="1" stroke-linecap="butt" stroke-linejoin="miter" stroke-miterlimit="10" stroke-dasharray="" stroke-dashoffset="0" font-family="none" font-weight="none" font-size="none"
              text-anchor="none" style="mix-blend-mode: normal">
              <path d="M0,172v-172h172v172z" fill="none"></path>
              <g fill="#0e6c66">
                <path
                  d="M80.625,0c-1.4842,0.00015 -2.68735,1.2033 -2.6875,2.6875v8.0625h-8.0625c-1.4842,0.00015 -2.68735,1.2033 -2.6875,2.6875v2.6875h-5.375c-0.96921,-0.01371 -1.87072,0.49551 -2.35932,1.33266c-0.4886,0.83715 -0.4886,1.87253 0,2.70968c0.4886,0.83715 1.39011,1.34637 2.35932,1.33266h5.375v10.75c0.00015,1.4842 1.2033,2.68735 2.6875,2.6875h8.0625v18.8125h-8.0625v-8.0625c-0.00015,-1.4842 -1.2033,-2.68735 -2.6875,-2.6875h-10.75c-1.4842,0.00015 -2.68735,1.2033 -2.6875,2.6875v8.0625h-5.375c-1.4842,0.00015 -2.68735,1.2033 -2.6875,2.6875h-5.375v-8.0625c0.00995,-0.72643 -0.2746,-1.42595 -0.78881,-1.93917c-0.51421,-0.51322 -1.21427,-0.79642 -1.94068,-0.78507c-1.4822,0.02317 -2.66581,1.242 -2.64551,2.72424v8.0625h-2.6875c-1.4842,0.00015 -2.68735,1.2033 -2.6875,2.6875v10.75c0.00015,1.4842 1.2033,2.68735 2.6875,2.6875h2.6875v8.0625c-0.01371,0.96921 0.49551,1.87072 1.33266,2.35932c0.83715,0.4886 1.87253,0.4886 2.70968,0c0.83715,-0.4886 1.34637,-1.39011 1.33266,-2.35932v-8.0625h5.375c0.00015,1.4842 1.2033,2.68735 2.6875,2.6875h5.375v18.8125h-5.375c-1.4842,0.00015 -2.68735,1.2033 -2.6875,2.6875v12.98608c-0.04797,0.29023 -0.04797,0.58636 0,0.87659v12.56091c-0.04797,0.29023 -0.04797,0.58636 0,0.87659v13.01233c0.00015,1.4842 1.2033,2.68735 2.6875,2.6875h5.375v11.92578c0.00002,0.28162 0.04431,0.56148 0.13123,0.82935l5.71094,17.63672c0.36563,1.12302 1.42153,1.87578 2.60239,1.85527c1.18086,-0.02051 2.20998,-0.80947 2.53641,-1.9445l5.03906,-17.63672c0.0693,-0.24061 0.10463,-0.48972 0.10498,-0.74011v-11.92578h5.375c1.4842,-0.00015 2.68735,-1.2033 2.6875,-2.6875v-40.3125c-0.00015,-1.4842 -1.2033,-2.68735 -2.6875,-2.6875h-5.375v-18.8125h10.75h10.75h29.5625c0.007,0.00003 0.014,0.00003 0.02099,0c0.08243,-0.00146 0.16475,-0.00672 0.2467,-0.01575c0.0703,-0.00599 0.14035,-0.01474 0.20996,-0.02625c0.01928,-0.00329 0.03853,-0.00679 0.05774,-0.0105c0.01051,-0.00169 0.02101,-0.00344 0.03149,-0.00525c0.07612,-0.01771 0.15142,-0.03872 0.22571,-0.06299c0.07282,-0.02317 0.14463,-0.04944 0.21521,-0.07874c0.01227,-0.00341 0.02452,-0.00691 0.03674,-0.0105c0.00701,-0.00347 0.01401,-0.00697 0.02099,-0.0105c0.04607,-0.01972 0.09158,-0.04072 0.13648,-0.06299l10.75,-5.375c0.91047,-0.45537 1.48554,-1.38605 1.48547,-2.40405h8.0625c0.96921,0.01371 1.87072,-0.49551 2.35932,-1.33266c0.4886,-0.83715 0.4886,-1.87253 0,-2.70968c-0.4886,-0.83715 -1.39011,-1.34637 -2.35932,-1.33266h-8.0625c0.00007,-1.018 -0.575,-1.94868 -1.48547,-2.40405l-10.73425,-5.3645c-0.00524,-0.00352 -0.01049,-0.00702 -0.01575,-0.0105c-0.07539,-0.03683 -0.15246,-0.07011 -0.23096,-0.09973c-0.06902,-0.02561 -0.13907,-0.04838 -0.20996,-0.06824c-0.01395,-0.00537 -0.02795,-0.01062 -0.04199,-0.01575c-0.00699,-0.00178 -0.01399,-0.00353 -0.02099,-0.00525c-0.0035,-0.00001 -0.007,-0.00001 -0.0105,0c-0.08301,-0.02328 -0.16709,-0.04254 -0.25195,-0.05774c-0.0817,-0.0143 -0.16403,-0.02481 -0.2467,-0.03149c-0.00525,-0.00002 -0.0105,-0.00002 -0.01575,0c-0.05767,-0.00361 -0.11544,-0.00536 -0.17322,-0.00525h-0.09973h-21.93567h-4.8396v-13.4375h51.0625c1.4842,-0.00015 2.68735,-1.2033 2.6875,-2.6875v-34.9375c-0.00015,-1.4842 -1.2033,-2.68735 -2.6875,-2.6875h-53.75zM83.3125,5.375h5.375v32.25v18.8125v13.4375h-5.375v-13.4375v-24.1875v-18.8125zM94.0625,5.375h48.375v29.5625h-48.375zM72.5625,16.125h5.375v13.4375h-5.375v-10.29858c0.04797,-0.29023 0.04797,-0.58636 0,-0.87659zM102.08301,18.77576c-1.4822,0.02317 -2.66581,1.242 -2.64551,2.72424v5.375c-0.01371,0.96921 0.49551,1.87072 1.33266,2.35932c0.83715,0.4886 1.87253,0.4886 2.70968,0c0.83715,-0.4886 1.34637,-1.39011 1.33266,-2.35932v-5.375c0.00995,-0.72643 -0.2746,-1.42595 -0.78881,-1.93917c-0.51421,-0.51322 -1.21427,-0.79642 -1.94068,-0.78507zM112.83301,18.77576c-1.4822,0.02317 -2.66581,1.242 -2.64551,2.72424v5.375c-0.01371,0.96921 0.49551,1.87072 1.33266,2.35932c0.83715,0.4886 1.87253,0.4886 2.70968,0c0.83715,-0.4886 1.34637,-1.39011 1.33266,-2.35932v-5.375c0.00995,-0.72643 -0.2746,-1.42595 -0.78881,-1.93917c-0.51421,-0.51322 -1.21427,-0.79642 -1.94068,-0.78507zM123.58301,18.77576c-1.4822,0.02317 -2.66581,1.242 -2.64551,2.72424v5.375c-0.01371,0.96921 0.49551,1.87072 1.33266,2.35932c0.83715,0.4886 1.87253,0.4886 2.70968,0c0.83715,-0.4886 1.34637,-1.39011 1.33266,-2.35932v-5.375c0.00995,-0.72643 -0.2746,-1.42595 -0.78881,-1.93917c-0.51421,-0.51322 -1.21427,-0.79642 -1.94068,-0.78507zM134.33301,18.77576c-1.4822,0.02317 -2.66581,1.242 -2.64551,2.72424v5.375c-0.01371,0.96921 0.49551,1.87072 1.33266,2.35932c0.83715,0.4886 1.87253,0.4886 2.70968,0c0.83715,-0.4886 1.34637,-1.39011 1.33266,-2.35932v-5.375c0.00995,-0.72643 -0.2746,-1.42595 -0.78881,-1.93917c-0.51421,-0.51322 -1.21427,-0.79642 -1.94068,-0.78507zM59.125,48.375h5.375v5.375h-5.375zM51.0625,59.125h5.52722h21.34778v10.75h-26.875zM94.0625,59.125h4.8396h19.3479v10.75h-24.1875zM123.625,60.78369l5.375,2.6875v0.57739c-0.04797,0.29023 -0.04797,0.58636 0,0.87659v0.60364l-5.375,2.6875zM34.9375,61.8125h2.23608c0.29023,0.04797 0.58636,0.04797 0.87659,0h7.63733v5.375h-7.64783c-0.1509,-0.02522 -0.30368,-0.03752 -0.45667,-0.03674c-0.13019,0.00282 -0.26001,0.0151 -0.38843,0.03674h-2.25708zM59.125,75.25h5.375v18.8125h-5.375zM51.0625,99.4375h21.5v8.0625h-21.5zM51.0625,112.875h21.5v8.0625h-21.5zM51.0625,126.3125h21.5v8.0625h-15.78906h-5.71094zM59.125,139.75h5.375v11.5531l-2.50903,8.79211l-2.86597,-8.8446z">
                </path>
              </g>
            </g>
          </svg>
          <h2>Tattoo Design </h2>
          <p> Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
        </div>
      </div>

      <div class="content flex">
        <div class="left">
          <div class="img">
            <img src="image/a.png" alt="">
          </div>
        </div>
        <div class="right">
          <h2>About Us</h2>
          <p> Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
          <button type="button" name="button">Read More</button>
        </div>
      </div>
    </div>
  </section>


  <section class="gallery">
    <h2>Our Tattoo Gallery </h2>
    <div class="image">
      <div class="img img_item1">
        <img src="image/i1.jpg">
      </div>
      <div class="img img_item2">
        <img src="image/i2.jpeg">
      </div>
      <div class="img img_item3">
        <img src="image/i3.jpeg">
      </div>
      <div class="img img_item4">
        <img src="image/i4.jpeg">
      </div>
      <div class="img img_item5">
        <img src="image/i5.jpeg">
      </div>
      <div class="img img_item6">
        <img src="image/i6.jpeg">
      </div>
    </div>
  </section>


  <section class="customer">
    <div class="container">
      <h2>What Says Our Client</h2>
      <div class="items grid">
        <div class="box">
          <div class="para">
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
              Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
          </div>
          <div class="image flex ">
            <div class="img">
              <img src="image/c1.jpg">
            </div>
            <div class="text">
              <h3>Alex Ander</h3>
              <p>Customer</p>
            </div>
          </div>
        </div>
        <div class="box">
          <div class="para">
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
              Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
          </div>
          <div class="image flex ">
            <div class="img">
              <img src="image/c2.jpg">
            </div>
            <div class="text">
              <h3>Alex Ander</h3>
              <p>Customer</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <footer>
    <div class="container">
      <div class="content flex">
        <div class="left">
          <div class="top flex">
            <div class="input">
              <input type="text" placeholder="Enter your email">
            </div>
            <div class="arrow">
              <i class="fa fa-paper-plane"></i>
            </div>
          </div>
        </div>
        <div class="right">
          <i class="fa fa-facebook"></i>
          <i class="fa fa-instagram"></i>
          <i class="fa fa-twitter"></i>
          <i class="fa fa-youtube"></i>
        </div>
      </div>

      <div class="grid">
        <div class="item">
          <h2>About</h2>
          <p> Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
        </div>
        <div class="item">
          <h2>Instagram</h2>
          <div class="box flex">
            <img src="image/i2.jpeg">
            <p>Excepteur sint occaecat cupidatat</p>
          </div>
          <div class="box flex">
            <img src="image/i4.jpeg">
            <p>Excepteur sint occaecat cupidatat</p>
          </div>
        </div>
        <div class="item">
          <h2>Contact Us</h2>
          <i class="fa fa-map"></i>
          <label>Location</label><br><br>
          <i class="fa fa-phone"></i>
          <label>Call +01 123456987</label><br><br>
          <i class="fa fa-envelope"></i>
          <label>yourmail@.com</label>
        </div>
        <div class="item">
          <iframe
            src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d56482.28235940186!2d85.29363651901193!3d27.774578537470312!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x39eb1ec025757983%3A0x31e21a2803752ce9!2z4KSf4KWL4KSW4KS-!5e0!3m2!1sne!2snp!4v1626886843762!5m2!1sne!2snp"
            width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
        </div>
      </div>
    </div>
  </footer>
  <p class="legal">Copyright (c) 2021 Copyright Holder All Rights Reserved | This template is made by <i class="fa fa-heart"></i> Dot Studio </p>
</body>

</html>
