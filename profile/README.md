# taggy | Open Semantic Tagging

<p align="center">
  <img width="240" alt="mtl-taggy" src="https://github.com/open-taggy/website/blob/main/static/img/logo.png">
</p>
<p align="center">
taggy is a frontend package to automatically tag (or categorize) textual content.
</p>

## 🧩 The problem

Tagging content in web-based editorial systems -
*i.e. assigning content to a selection of topics* - 
is mostly still done manually and therefore tedious and error-prone. Especially when it comes to large amounts of data.
Proprietary systems are often expensive and questionable in terms of data protection.

## 🎯 taggy gives you
- An open, easy-to-start-with, easy-to-integrate and quite powerful frontend module to fit your tagging needs.

- Just define some trigger words or put in your existing [glossary](#the-glossary) and start to tag your content. 

## 👁️ Demo

- **[try it out here](https://open-taggy.github.io/demo/)**

## 💡 Examples

### Website Forms
Assign form input by your users automatically to the right internal tracks:

<img src="/screencasts/screencast-shop_en_submit.gif" width="600" />

Categorize input while typing:

<img src="/screencasts/screencast-fan_en_live.gif" width="600" />

### News Articles
Tag them automatically:

<img src="/screencasts/screencast-media_en_media.gif" width="600" /> 

## 📘 Documentation

### Getting started
Please visit the [main repo of taggy](https://github.com/open-taggy/taggy) to get going quickly.

### The Glossary
This is a list of trigger words in JSON-format with top- and sub-tags. taggy categorizes the input based on that.
The structure is like this:

```json
{
  "tags": [
    {
      "name": "First Category",
      "words": ["tag1", "tag2", "another-tag", "and-another-tag"]
    },
    {
      "name": "Second Category",
      "words": ["First one for #2", "Second one for #2"]
    },
    {
      "name": "A Third Category",
      "words": ["sub3-1", "sub3-2"]
    }
  ]
}

```


## ⚡ Powered by

<a href="https://media-tech-lab.com">Media Tech Lab by Media Lab Bayern</a> (<a href="https://github.com/media-tech-lab">@media-tech-lab</a>)

<img width="240" alt="mtl-powered-by" src="https://user-images.githubusercontent.com/12242651/189848013-001839f4-f866-434c-b1d8-90b195ab738b.png">
