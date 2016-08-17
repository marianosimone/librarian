search for:
<li id="fn(\d+)".*><p>(.*)<a href=.*

replace with:
<aside id="fn\1" epub:type="footnote" class="footnote"><p><a class="noteref" href="#fnref\1">\1</a>. \2</p></aside>