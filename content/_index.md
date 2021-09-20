Ciao mamma

{{< highlight go >}} A bunch of code here {{< /highlight >}}

{{ $_hugo_config := `{ "version": 1 }` }}

{{< figure src="/media/spf13.jpg" title="Steve Francia" >}}


{{< alert "info" "This is a notice." >}}

{{< highlight html >}}
<section id="main">
  <div>
   <h1 id="title">{{ .Title }}</h1>
    {{ range .Pages }}
        {{ .Render "summary"}}
    {{ end }}
  </div>
</section>
{{< /highlight >}}

[Neat]({{< ref "posts/my-first-post.md" >}})

{{< vimeo id="146022717" class="my-vimeo-wrapper-class" title="My vimeo video" >}}
