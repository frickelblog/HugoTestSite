+++
weight = 1
title = "Syntax Highlighting"
+++

## HTML
``` html
<section id="main">
  <div>
    <h1 id="title">{{ .Title }}</h1>
    {{ range .Data.Pages }}
      {{ .Render "summary"}}
    {{ end }}
  </div>
</section>
```

-----

## PHP
``` php
<? 

echo phpinfo();
return true;

?>
```
-----

## CSharp
``` cs
public class test()
{
    public int test(string zahl)
    {
        return Convert.ToInt32(zahl);
    }
}
```