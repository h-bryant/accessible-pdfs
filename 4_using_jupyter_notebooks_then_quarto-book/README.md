
added the following to the top of
`/opt/quarto/share/formats/pdf/pandoc/doc-class.tex` to make this work:

```{latex}
\DocumentMetadata{uncompress,lang=en,pdfversion=2.0,pdfstandard=ua-2,pdfstandard=a-4f,testphase=latest}
```


To build pdf of book, `cd` to this direrctory, then
```
quarto render mybook/ --to pdf
```

To render HTML, 
```
quarto render mybook/ --to html
```
