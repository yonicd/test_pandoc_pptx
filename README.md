# CMEI Quarto templates

This Quarto format will help you create documents for the CMEI documents. 

For more about Quarto and how to use format extensions, see <https://quarto.org/docs/extensions/managing.html>.

## Creating a New Document

You can use this as a template to create an docuemnt for the CMEI. To do this, use the following command:

```quarto use template yonisidi/cmei_quarto```

This will install the extension and create an example qmd and powerpoint template that you can use as a starting place for your slide deck.


## Installation For Existing Document

You may also use this format with an existing Quarto project or document. From the quarto project or document directory, run the following command to install this format:

```quarto add yonisidi/cmei_quarto```

## Usage 

To use the format, you can use the format names `cmei-pptx`. For example:

```quarto render slides.qmd --to cmei-pptx```

or in your document yaml

```yaml
format: cmei-pptx
```
