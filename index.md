---
layout: default
---

# Portfolio

## ML-guided protein function enhancement framework (current work)

I designed and led a team of three people through the implementation and deployment of a system that lets a customer (reagent manufacturer or a biotech startup) navigate a fitness landscape of mutant protein versions in search of functionally enhanced variants with respect to multiple protein aspects. In order to bring value to the customer, we only need the primary protein structure, as many as 18 mutant versions with experimentally evaluated fitness, and two weeks. The main components of the system are the following: 

* A protein function regressor that makes use of information-rich embeddings derived from large protein language models (pLMs).

* A graphical user interface that allows a customer to select promising candidates with desired properties and compare them using various visualizations.

Hiplots (https://pypi.org/project/hiplot/) are particularly good at this (see image below).

* A search engine that performs directed evolution on a surrogate fitness landscape to maximize a specific function.

* A database that stores millions of previously tested candidates.

<center><img src="/assets/img/enhancement_hiplot.png"/>center>




   My goal as a researcher and team leader of this project is to make the product as data-effective (therefore cost-effective) as possible and to further scale the product by making multiple customers stick to our service in their ongoing efforts to modernize the set of reagents used.

   

## [Multimodal Single-Cell Data Integration Challenge](https://openproblems.bio/neurips_2021/) (part of NeurIPS 2021)

Our team (me and my colleagues Gleb Ryazantsev and Igor I) participated in this competition and won first place in the ADT->GEX nomination of the modality prediction task ([github](https://github.com/openproblems-bio/neurips2021_multimodal_topmethods/tree/main/src/predict_modality/methods/novel)) and second place in all nominations of the modality matching task ([github](https://github.com/openproblems-bio/neurips2021_multimodal_topmethods/tree/main/src/match_modality/methods/novel)).

Publication regarding the competition: [link](https://www.biorxiv.org/content/10.1101/2022.04.11.487796v1.abstract) <a href=["https://github.com/orderedlist](https://www.biorxiv.org/content/10.1101/2022.04.11.487796v1.abstract)">link</a>

## [Protomenal](https://protomenal.com) - protein functional domain annotation service.

  I designed a novel approach for prediction of protein functional domains algorithm based on protein language models and deep metric learning and led a team of

ML researchers and developers to productionalizing it as a web service. The service performs superior to alignemt-based methods in remote homology setup.  To my knowledge, this is the first ML-based web-service which predicts functional domains in multi-domain proteins (now [ProteInfer](https://google-research.github.io/proteinfer/) does that too).

<center><img src="/assets/img/protomenal.png"/>center>

# Publications
* Multimodal single cell data integration challenge: results and lessons learned : [link](https://www.biorxiv.org/content/10.1101/2022.04.11.487796.abstract)
* Style transfer with variational autoencoders is a promising approach to RNA-Seq data harmonization and analysis : [link](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7755413/)
* CellCountCV-A Web-Application for Accurate Cell Counting and Automated Batch Processing of Microscopic Images Using Fully Convolutional Neural Networks: [link](https://pubmed.ncbi.nlm.nih.gov/32610652/)

<!---
Text can be **bold**, _italic_, or ~~strikethrough~~.

[Link to another page](./another-page.html).

There should be whitespace between paragraphs.

There should be whitespace between paragraphs. We recommend including a README, or a file with information about your project.

# Header 1

This is a normal paragraph following a header. GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere.

## Header 2

> This is a blockquote following a header.
>
> When something is important enough, you do it even if the odds are not in your favor.

### Header 3

```js
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```

```ruby
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
```

#### Header 4

*   This is an unordered list following a header.
*   This is an unordered list following a header.
*   This is an unordered list following a header.

##### Header 5

1.  This is an ordered list following a header.
2.  This is an ordered list following a header.
3.  This is an ordered list following a header.

###### Header 6

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

### There's a horizontal rule below this.

* * *

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four

### And a nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item

### Small image

![Octocat](https://github.githubassets.com/images/icons/emoji/octocat.png)

### Large image

![Branching](https://guides.github.com/activities/hello-world/branching.png)


### Definition lists can be used with HTML syntax.

<dl>
<dt>Name</dt>
<dd>Godzilla</dd>
<dt>Born</dt>
<dd>1952</dd>
<dt>Birthplace</dt>
<dd>Japan</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl>

```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```

```
The final element.
```
-->
