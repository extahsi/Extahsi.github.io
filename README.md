# Extahsi.github.io

<!doctype html>
  <html>
    <head>
    <title>Termino.js Basic Example</title>
    </head>
    <body>
      <div id="terminal">
      <pre><code class="termino-console"></code></pre>
      <textarea class="termino-input" rows="1" wrap="hard"></textarea>
      </div>
      <script type="module">
        import {Termino} from 'https://cdn.jsdelivr.net/gh/MarketingPipeline/Termino.js@v1.0.0/dist/termino.min.js';
        let term= Termino(document.getElementById("terminal"))
        term.echo("Hello world from https://github.com/MarketingPipeline")
      </script>
    </body>
  </html>
