# Resume

markdown based resume.

## Generate

`docker run --rm -v ${PWD}:/resume there4/markdown-resume md2resume pdf /resume/example.md /resume`

### See avaliable themes

`docker run --rm -v ${PWD}:/resume there4/markdown-resume md2resume templates`

### Generate w/ Theme

`docker run --rm -v ${PWD}:/resume there4/markdown-resume md2resume pdf /resume/example.md /resume -t roboto`