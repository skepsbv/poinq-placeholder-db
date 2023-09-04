# poinq-placeholder-db

Generated using the following code on https://json-generator.com:
```js
{
  "initiatieven": [
  '{{repeat(2)}}',
  {
    id: '{{objectId()}}',
    name: '{{lorem(4, "words")}}',
    icon: '{{random("👶🏻", "😍", "🎉")}}',
    size: '{{integer(0, 100)}}',
    description: '{{lorem(1, "paragraphs")}}',
    price: '{{integer(10, 1200)}}',
    askingPrice: '{{integer(700, 1200)}}',
    contributions: [
      '{{repeat(0, 4)}}',
      {
        id: '{{index()}}',
        name: '{{firstName()}}',
        amount: '{{integer(5, 250)}}',
        image: 'https://picsum.photos/id/{{integer(1, 50)}}/24',
        description: '{{random(lorem(1, "sentences"), "")}}'
      }
    ]
  }
]
}
```
