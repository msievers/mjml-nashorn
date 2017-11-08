### Try it out

```sh
$ git clone https://github.com/msievers/mjml-nashorn.git
$ cd mjml-nashorn
$ jjs
jjs> load("./dist/mjml.js")
jjs> var result = global.mjml.mjml2html('<mjml>   <mj-body>     <mj-container>       <mj-section>         <mj-column>            <mj-image width=\"100\" src=\"/assets/img/logo-small.png\"></mj-image>            <mj-divider border-color=\"#F45E43\"></mj-divider>            <mj-text font-size=\"20px\" color=\"#F45E43\" font-family=\"helvetica\">Hello World</mj-text>          </mj-column>       </mj-section>     </mj-container>   </mj-body> </mjml>')
jjs> result["html"] // gives you the generated html
```
