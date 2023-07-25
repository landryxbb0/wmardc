# wmardc
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width" />
    <title>LANDR</title>
    <base href="/" />
    <link
      rel="apple-touch-icon"
      sizes="180x180"
      href="https://cdn.landr.com/images/apple-touch-icon.png?v=dLn6e7bpqR"
    />
    <link
      rel="icon"
      type="image/png"
      sizes="32x32"
      href="https://cdn.landr.com/images/favicon-32x32.png?v=dLn6e7bpqR"
    />
    <link
      rel="icon"
      type="image/png"
      sizes="16x16"
      href="https://cdn.landr.com/images/favicon-16x16.png?v=dLn6e7bpqR"
    />
    <link rel="manifest" href="https://cdn.landr.com/images/site.webmanifest?v=dLn6e7bpqR" />
    <link rel="mask-icon" href="https://cdn.landr.com/images/safari-pinned-tab.svg?v=dLn6e7bpqR" color="#142739" />
    <link rel="shortcut icon" href="https://cdn.landr.com/images/favicon.ico?v=dLn6e7bpqR" />
    <meta name="apple-mobile-web-app-title" content="LANDR" />
    <meta name="application-name" content="LANDR" />
    <meta name="msapplication-TileColor" content="#142739" />
    <meta name="msapplication-config" content="https://cdn.landr.com/images/browserconfig.xml?v=dLn6e7bpqR" />
    <meta name="theme-color" content="#142739" />

    <!-- Start SmartBanner configuration -->
    <meta name="smartbanner:title" content="LANDR App" />
    <meta name="smartbanner:author" content="Messaging for musicians" />
    <meta name="smartbanner:price" content="FREE" />
    <meta name="smartbanner:price-suffix-apple" content=" - On the App Store" />
    <meta name="smartbanner:price-suffix-google" content=" - On Google Play" />
    <meta name="smartbanner:icon-apple" content="https://play-lh.googleusercontent.com/Vuf_ejgmoz6HKTZi8HEH8E577lWnAwzE4Tki2UFWQLoNdikRvjVj34WVhocqlhy_Auu2=w64-h64-rw" />
    <meta name="smartbanner:icon-google" content="https://play-lh.googleusercontent.com/Vuf_ejgmoz6HKTZi8HEH8E577lWnAwzE4Tki2UFWQLoNdikRvjVj34WVhocqlhy_Auu2=w64-h64-rw" />
    <meta name="smartbanner:button" content="View" />
    <meta name="smartbanner:button-url-apple" content="https://apps.apple.com/app/id6443542020" />
    <meta name="smartbanner:button-url-google" content="https://play.google.com/store/apps/details?id=com.landr.mobile.app" />
    <meta name="smartbanner:enabled-platforms" content="android,ios" />
    <meta name="smartbanner:close-label" content="Close" />
    <meta name="smartbanner:custom-design-modifier" content="landr" />
    <meta name="smartbanner:exclude-user-agent-regex" content="^.*(Windows NT|Intel Mac OS X).*$" />
    <!-- End SmartBanner configuration -->

    <!--  Preload, preconnect data for production -->
    <link rel="preconnect" href="//api3.landr.com" />
    <link rel="preconnect" href="//cdn.landr.com" />
    <link rel="preconnect" href="//cdn.segment.com" />

    <link rel="preload" href="https://cdn.landr.com/fonts/Sailec/style.css" as="style" />
    <link rel="preload" href="https://cdn.landr.com/fonts/Sailec/SailecMedium.woff2" as="font" crossorigin />
    <link rel="preload" href="https://cdn.landr.com/fonts/Sailec/SailecRegular.woff2" as="font" crossorigin />

    <link rel="stylesheet" type="text/css" href="https://cdn.jsdelivr.net/npm/smartbanner.js@1.19.1/dist/smartbanner.css" />
    <script async src="https://cdn.jsdelivr.net/npm/smartbanner.js@1.19.1/dist/smartbanner.min.js"></script>

    <script src="https://cdn.landr.com/universal-login/clean-encoded-cookies.js"></script>

    <script>
      !(function () {
        if ('PerformanceLongTaskTiming' in window) {
          var g = (window.__tti = { e: [] });
          g.o = new PerformanceObserver(function (l) {
            g.e = g.e.concat(l.getEntries());
          });
          g.o.observe({ entryTypes: ['longtask'] });
        }
      })();
    </script>
    <script>
      window.LANDR_CONFIG = {"LANDR_ENV":"production","OFFLINE_URL":"https://offline.landr.com/","UNSUPPORTED_BROWSER_URL":"https://offline.landr.com/unsupported.html","MAESTRO_THEME":"default","SEGMENT_WRITE_KEY":"IOIt6E7ETDp6LN2VZLjZtDX4j2RFst5Z","FEATURE_FLAG_API":"https://api3.landr.com/featureflag","LOG_APPLICATION_NAME":"RootApp","LOG_TAGS":"Web,MFE,RootApp","LOG_SERVICE_KEY":"RootApp","LOG_DEPLOYMENT_KIND":"Production","LOG_SEPARATOR":" :: ","LOG_ENABLED":"true","LOG_LOGGLY_ENABLED":"true","LOG_LOGGLY_MINLEVEL":"ERROR","LOG_LOGGLY_API_KEY":"9c47830d-797b-4509-98a6-5e7cb064743d","LOG_LOGGLY_CONSECUTIVE_OCCURRENCES":"0","LOG_LOGGLY_MAX_BUNDLE_SIZE":"100","LOG_CONSOLE_ENABLED":"true","LOG_CONSOLE_MINLEVEL":"FATAL","UTM_COOKIE_SECURE":"true","UTM_COOKIE_EXPIRES":"30","UTM_COOKIE_DOMAIN":".landr.com","SUBSCRIPTION_API":"https://api3.landr.com/subscription/api","FIRST_PROMOTER_ID":"v13ohqts","PROFITWELL_TOKEN":"d8232ed03ff861138d44fc45f59c739b","FUSIONAUTH_DOMAIN":"https://accounts.landr.com","FUSIONAUTH_CLIENT_ID":"16129c67-583f-4707-87d3-eb7e8375eaf3","PORT":"","HOST":"","BROWSER":""};
    </script>
    <style>
      .smartbanner--landr {
        top: -84px;
        font-family: 'Sailec',-apple-system,BlinkMacSystemFont,'Segoe UI',Roboto,'Helvetica Neue',Arial,sans-serif,'Apple Color Emoji','Segoe UI Emoji','Segoe UI Symbol';
        background: white;
        box-shadow: none;
      }
      .smartbanner--landr .smartbanner__exit {
        box-shadow: none;
        background: transparent;
      }
      .smartbanner--landr .smartbanner__info {
        line-height: 20px;
        color: rgb(108 119 130);
        text-shadow: none;
      }
      .smartbanner--landr .smartbanner__info__title {
        color: rgb(20 39 57);
        font-weight: 600;
      }
      .smartbanner--landr .smartbanner__info__price {
        margin-top: 3px;
      }
      .smartbanner--landr .smartbanner__button {
        background: transparent;
        box-shadow: none;
        right: 10px;
      }
      .smartbanner--landr .smartbanner__button__label {
        color: #3b82f6;
        font-size: 14px;
        background: transparent;
        font-weight: 600;
      }


      html.on-behalf {
        border: thick solid red;
      }

      .RootApp {
        box-sizing: border-box;
        z-index: 6000;
        display: flex;
        position: absolute;
        top: 0;
        left: 0;
        align-items: center;
        justify-content: center;
        width: 100vw;
        height: 100vh;
        max-width: 100vw;
        max-height: 100vh;
        background-color: #fff;
        opacity: 1;
        transition: opacity 200ms cubic-bezier(0.55, 0.085, 0.68, 0.53);
      }

      .RootApp .RootApp-loader {
        position: relative;
        display: inline-block;
        text-align: center;
      }

      .RootApp .RootApp-loader-icon {
        display: inline-block;
        height: 48px;
        width: 53px;
        margin-bottom: 6px;
        background-image: url('/root-app/images/icon-loading.gif');
        background-position: center center;
        background-size: cover;
      }
    </style>

    <script>
      window.hj =
        window.hj ||
        function () {
          (hj.q = hj.q || []).push(arguments);
        };
    </script>
  </head>
  <body>
    <div id="loading-container" class="RootApp">
      <div class="RootApp-loader">
        <div class="RootApp-loader-icon"></div>
      </div>
    </div>

    <script>
      function isBrowserUnsupported() {
        // Taken from https://github.com/faisalman/ua-parser-js/blob/bd6dee4a08070815d55b2c867a16b0172df78b9d/src/ua-parser.js
        var OperaMiniRegex = /(opera\smini)\/([\w.-]+)/i;
        var OperaIOSRegex = /(opios)[/\s]+([\w.]+)/i;
        var IERegex = /(?:ms|\()(ie)\s([\w.]+)/i;
        var IE11Regex = /(trident).+rv[:\s]([\w\.]+).+like\sgecko/i;
        var userAgent = window.navigator.userAgent || '';
        var esModuleSupported = 'noModule' in HTMLScriptElement.prototype;

        return (
          userAgent.match(OperaMiniRegex) ||
          userAgent.match(OperaIOSRegex) ||
          userAgent.match(IERegex) ||
          userAgent.match(IE11Regex) ||
          !esModuleSupported
        );
      }

      if (isBrowserUnsupported()) {
        window.location.assign(window.LANDR_CONFIG.UNSUPPORTED_BROWSER_URL);
      }
    </script>

    <script type="systemjs-importmap" src="/root-app/importMap.json"></script>
    <!-- This tells SystemJS to load the application -->
    <script type="module">
      System.import('@landr/root-app-config');
    </script>

    <script src="https://cdn.jsdelivr.net/npm/systemjs@6.8.3/dist/s.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/systemjs@6.8.3/dist/extras/amd.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/systemjs@6.8.3/dist/extras/named-register.min.js"></script>

    <div id="single-spa-application-core-mfe"></div>

    <script async defer src="https://9r5vl8rcb47b.statuspage.io/embed/script.js"></script>
