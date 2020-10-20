# Single

1. https://www.overleaf.com/docs?snip_uri=https%3A%2F%2Fraw.githubusercontent.com%2Fmaverickwoo%2F1019-overleaf%2Fmain%2Fsingle%2Fa.tex => a.tex becomes main.tex; title = "a"

2. https://www.overleaf.com/docs?snip_uri[]=https%3A%2F%2Fraw.githubusercontent.com%2Fmaverickwoo%2F1019-overleaf%2Fmain%2Fsingle%2Fa.tex&snip_name[]=a.tex => *a.tex still becomes main.tex*; title = "a.tex"

# Multi

3. https://www.overleaf.com/docs?snip_uri[]=https%3A%2F%2Fraw.githubusercontent.com%2Fmaverickwoo%2F1019-overleaf%2Fmain%2Fmulti%2Fb.tex&snip_uri[]=https%3A%2F%2Fraw.githubusercontent.com%2Fmaverickwoo%2F1019-overleaf%2Fmain%2Fmulti%2Fc.tex => names remain intact; title = "Untitled"

4. https://www.overleaf.com/docs?snip_uri[]=https%3A%2F%2Fraw.githubusercontent.com%2Fmaverickwoo%2F1019-overleaf%2Fmain%2Fmulti%2Fb.tex&snip_uri[]=https%3A%2F%2Fraw.githubusercontent.com%2Fmaverickwoo%2F1019-overleaf%2Fmain%2Fmulti%2Fc.tex&snip_name[]=b.tex&snip_name[]=c.tex => names remain intact; title = "Untitled"
