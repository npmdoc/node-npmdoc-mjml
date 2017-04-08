# api documentation for  [mjml (v3.3.0)](https://mjml.io)  [![npm package](https://img.shields.io/npm/v/npmdoc-mjml.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-mjml) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-mjml.svg)](https://travis-ci.org/npmdoc/node-npmdoc-mjml)
#### MJML: the only framework that makes responsive-email easy

[![NPM](https://nodei.co/npm/mjml.png?downloads=true)](https://www.npmjs.com/package/mjml)

[![apidoc](https://npmdoc.github.io/node-npmdoc-mjml/build/screenCapture.buildNpmdoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-mjml%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-mjml/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-mjml/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-mjml/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bin": {
        "mjml": "bin/mjml"
    },
    "bugs": {
        "url": "https://github.com/mjmlio/mjml/issues"
    },
    "dependencies": {
        "lodash": "^4.17.4",
        "mjml-accordion": "~3.3.0",
        "mjml-button": "~3.3.0",
        "mjml-carousel": "~3.3.0",
        "mjml-cli": "~3.3.0",
        "mjml-column": "~3.3.0",
        "mjml-container": "~3.3.0",
        "mjml-core": "~3.3.0",
        "mjml-divider": "~3.3.0",
        "mjml-group": "~3.3.0",
        "mjml-head-attributes": "~3.3.0",
        "mjml-head-font": "~3.3.0",
        "mjml-head-style": "~3.3.0",
        "mjml-head-title": "~3.3.0",
        "mjml-hero": "~3.3.0",
        "mjml-html": "~3.3.0",
        "mjml-image": "~3.3.0",
        "mjml-invoice": "~3.3.0",
        "mjml-list": "~3.3.0",
        "mjml-location": "~3.3.0",
        "mjml-navbar": "~3.3.0",
        "mjml-raw": "~3.3.0",
        "mjml-section": "~3.3.0",
        "mjml-social": "~3.3.0",
        "mjml-spacer": "~3.3.0",
        "mjml-table": "~3.3.0",
        "mjml-text": "~3.3.0",
        "mjml-wrapper": "~3.3.0"
    },
    "description": "MJML: the only framework that makes responsive-email easy",
    "devDependencies": {},
    "directories": {},
    "dist": {
        "shasum": "d4d1a188d8bd1c9e5aba3a0f77ccfc6e2ce33596",
        "tarball": "https://registry.npmjs.org/mjml/-/mjml-3.3.0.tgz"
    },
    "homepage": "https://mjml.io",
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "mailjet-admin",
            "email": "api@mailjet.com"
        },
        {
            "name": "mjml",
            "email": "hi@mjml.io"
        }
    ],
    "name": "mjml",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/mjmlio/mjml.git"
    },
    "scripts": {},
    "version": "3.3.0"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module mjml](#apidoc.module.mjml)
1.  [function <span class="apidocSignatureSpan">mjml.</span>MJMLElement (ComposedComponent)](#apidoc.element.mjml.MJMLElement)
1.  [function <span class="apidocSignatureSpan">mjml.</span>MJMLRenderer (content)](#apidoc.element.mjml.MJMLRenderer)
1.  [function <span class="apidocSignatureSpan">mjml.</span>MJMLValidator (element)](#apidoc.element.mjml.MJMLValidator)
1.  [function <span class="apidocSignatureSpan">mjml.</span>documentParser (content, attributes)](#apidoc.element.mjml.documentParser)
1.  [function <span class="apidocSignatureSpan">mjml.</span>elements.mj-accordion (props)](#apidoc.element.mjml.elements.mj-accordion)
1.  [function <span class="apidocSignatureSpan">mjml.</span>elements.mj-carousel (props)](#apidoc.element.mjml.elements.mj-carousel)
1.  [function <span class="apidocSignatureSpan">mjml.</span>elements.mj-column (props)](#apidoc.element.mjml.elements.mj-column)
1.  [function <span class="apidocSignatureSpan">mjml.</span>elements.mj-container (props)](#apidoc.element.mjml.elements.mj-container)
1.  [function <span class="apidocSignatureSpan">mjml.</span>elements.mj-divider (props)](#apidoc.element.mjml.elements.mj-divider)
1.  [function <span class="apidocSignatureSpan">mjml.</span>elements.mj-group (props)](#apidoc.element.mjml.elements.mj-group)
1.  [function <span class="apidocSignatureSpan">mjml.</span>elements.mj-hero (props)](#apidoc.element.mjml.elements.mj-hero)
1.  [function <span class="apidocSignatureSpan">mjml.</span>elements.mj-hero-content (props)](#apidoc.element.mjml.elements.mj-hero-content)
1.  [function <span class="apidocSignatureSpan">mjml.</span>elements.mj-inline-links (props)](#apidoc.element.mjml.elements.mj-inline-links)
1.  [function <span class="apidocSignatureSpan">mjml.</span>elements.mj-link (props)](#apidoc.element.mjml.elements.mj-link)
1.  [function <span class="apidocSignatureSpan">mjml.</span>elements.mj-raw (props)](#apidoc.element.mjml.elements.mj-raw)
1.  [function <span class="apidocSignatureSpan">mjml.</span>elements.mj-section (props)](#apidoc.element.mjml.elements.mj-section)
1.  [function <span class="apidocSignatureSpan">mjml.</span>elements.mj-social (props)](#apidoc.element.mjml.elements.mj-social)
1.  [function <span class="apidocSignatureSpan">mjml.</span>elements.mj-text (props)](#apidoc.element.mjml.elements.mj-text)
1.  [function <span class="apidocSignatureSpan">mjml.</span>elements.mj-wrapper ()](#apidoc.element.mjml.elements.mj-wrapper)
1.  [function <span class="apidocSignatureSpan">mjml.</span>formatValidationError (message, element)](#apidoc.element.mjml.formatValidationError)
1.  [function <span class="apidocSignatureSpan">mjml.</span>mjml2html (mjml)](#apidoc.element.mjml.mjml2html)
1.  [function <span class="apidocSignatureSpan">mjml.</span>registerMJElement (Component)](#apidoc.element.mjml.registerMJElement)
1.  [function <span class="apidocSignatureSpan">mjml.</span>registerMJHeadElement ()](#apidoc.element.mjml.registerMJHeadElement)
1.  [function <span class="apidocSignatureSpan">mjml.</span>registerMJRule (rule, name)](#apidoc.element.mjml.registerMJRule)
1.  [function <span class="apidocSignatureSpan">mjml.</span>version ()](#apidoc.element.mjml.version)
1.  object <span class="apidocSignatureSpan">mjml.</span>MJMLHeadElements
1.  object <span class="apidocSignatureSpan">mjml.</span>elements
1.  object <span class="apidocSignatureSpan">mjml.</span>helpers
1.  object <span class="apidocSignatureSpan">mjml.</span>helpers.dom
1.  object <span class="apidocSignatureSpan">mjml.</span>mjIncludeRegexp
1.  object <span class="apidocSignatureSpan">mjml.</span>rulesCollection

#### [module mjml.MJMLHeadElements](#apidoc.module.mjml.MJMLHeadElements)
1.  [function <span class="apidocSignatureSpan">mjml.MJMLHeadElements.</span>mj-attributes (element, globalAttributes)](#apidoc.element.mjml.MJMLHeadElements.mj-attributes)
1.  [function <span class="apidocSignatureSpan">mjml.MJMLHeadElements.</span>mj-font (_ref, globalAttributes)](#apidoc.element.mjml.MJMLHeadElements.mj-font)
1.  [function <span class="apidocSignatureSpan">mjml.MJMLHeadElements.</span>mj-style (_ref, globalAttributes)](#apidoc.element.mjml.MJMLHeadElements.mj-style)
1.  [function <span class="apidocSignatureSpan">mjml.MJMLHeadElements.</span>mj-title (_ref, globalAttributes)](#apidoc.element.mjml.MJMLHeadElements.mj-title)

#### [module mjml.elements](#apidoc.module.mjml.elements)
1.  [function <span class="apidocSignatureSpan">mjml.elements.</span>mj-accordion (props)](#apidoc.element.mjml.elements.mj-accordion)
1.  [function <span class="apidocSignatureSpan">mjml.elements.</span>mj-accordion-element (props)](#apidoc.element.mjml.elements.mj-accordion-element)
1.  [function <span class="apidocSignatureSpan">mjml.elements.</span>mj-accordion-text (props)](#apidoc.element.mjml.elements.mj-accordion-text)
1.  [function <span class="apidocSignatureSpan">mjml.elements.</span>mj-accordion-title (props)](#apidoc.element.mjml.elements.mj-accordion-title)
1.  [function <span class="apidocSignatureSpan">mjml.elements.</span>mj-button (props)](#apidoc.element.mjml.elements.mj-button)
1.  [function <span class="apidocSignatureSpan">mjml.elements.</span>mj-carousel (props)](#apidoc.element.mjml.elements.mj-carousel)
1.  [function <span class="apidocSignatureSpan">mjml.elements.</span>mj-carousel-image (props)](#apidoc.element.mjml.elements.mj-carousel-image)
1.  [function <span class="apidocSignatureSpan">mjml.elements.</span>mj-column (props)](#apidoc.element.mjml.elements.mj-column)
1.  [function <span class="apidocSignatureSpan">mjml.elements.</span>mj-container (props)](#apidoc.element.mjml.elements.mj-container)
1.  [function <span class="apidocSignatureSpan">mjml.elements.</span>mj-divider (props)](#apidoc.element.mjml.elements.mj-divider)
1.  [function <span class="apidocSignatureSpan">mjml.elements.</span>mj-group (props)](#apidoc.element.mjml.elements.mj-group)
1.  [function <span class="apidocSignatureSpan">mjml.elements.</span>mj-hero (props)](#apidoc.element.mjml.elements.mj-hero)
1.  [function <span class="apidocSignatureSpan">mjml.elements.</span>mj-hero-content (props)](#apidoc.element.mjml.elements.mj-hero-content)
1.  [function <span class="apidocSignatureSpan">mjml.elements.</span>mj-html (props)](#apidoc.element.mjml.elements.mj-html)
1.  [function <span class="apidocSignatureSpan">mjml.elements.</span>mj-image (props)](#apidoc.element.mjml.elements.mj-image)
1.  [function <span class="apidocSignatureSpan">mjml.elements.</span>mj-inline-links (props)](#apidoc.element.mjml.elements.mj-inline-links)
1.  [function <span class="apidocSignatureSpan">mjml.elements.</span>mj-invoice (props)](#apidoc.element.mjml.elements.mj-invoice)
1.  [function <span class="apidocSignatureSpan">mjml.elements.</span>mj-invoice-item (props)](#apidoc.element.mjml.elements.mj-invoice-item)
1.  [function <span class="apidocSignatureSpan">mjml.elements.</span>mj-link (props)](#apidoc.element.mjml.elements.mj-link)
1.  [function <span class="apidocSignatureSpan">mjml.elements.</span>mj-list (props)](#apidoc.element.mjml.elements.mj-list)
1.  [function <span class="apidocSignatureSpan">mjml.elements.</span>mj-location (props)](#apidoc.element.mjml.elements.mj-location)
1.  [function <span class="apidocSignatureSpan">mjml.elements.</span>mj-navbar (props)](#apidoc.element.mjml.elements.mj-navbar)
1.  [function <span class="apidocSignatureSpan">mjml.elements.</span>mj-raw (props)](#apidoc.element.mjml.elements.mj-raw)
1.  [function <span class="apidocSignatureSpan">mjml.elements.</span>mj-section (props)](#apidoc.element.mjml.elements.mj-section)
1.  [function <span class="apidocSignatureSpan">mjml.elements.</span>mj-social (props)](#apidoc.element.mjml.elements.mj-social)
1.  [function <span class="apidocSignatureSpan">mjml.elements.</span>mj-spacer (props)](#apidoc.element.mjml.elements.mj-spacer)
1.  [function <span class="apidocSignatureSpan">mjml.elements.</span>mj-table (props)](#apidoc.element.mjml.elements.mj-table)
1.  [function <span class="apidocSignatureSpan">mjml.elements.</span>mj-text (props)](#apidoc.element.mjml.elements.mj-text)
1.  [function <span class="apidocSignatureSpan">mjml.elements.</span>mj-wrapper ()](#apidoc.element.mjml.elements.mj-wrapper)

#### [module mjml.elements.mj-accordion](#apidoc.module.mjml.elements.mj-accordion)
1.  [function <span class="apidocSignatureSpan">mjml.elements.</span>mj-accordion (props)](#apidoc.element.mjml.elements.mj-accordion.mj-accordion)
1.  [function <span class="apidocSignatureSpan">mjml.elements.mj-accordion.</span>postRender ($)](#apidoc.element.mjml.elements.mj-accordion.postRender)
1.  object <span class="apidocSignatureSpan">mjml.elements.mj-accordion.</span>baseStyles
1.  object <span class="apidocSignatureSpan">mjml.elements.mj-accordion.</span>defaultMJMLDefinition
1.  object <span class="apidocSignatureSpan">mjml.elements.mj-accordion.</span>parentTag
1.  string <span class="apidocSignatureSpan">mjml.elements.mj-accordion.</span>tagName

#### [module mjml.elements.mj-carousel](#apidoc.module.mjml.elements.mj-carousel)
1.  [function <span class="apidocSignatureSpan">mjml.elements.</span>mj-carousel (props)](#apidoc.element.mjml.elements.mj-carousel.mj-carousel)
1.  [function <span class="apidocSignatureSpan">mjml.elements.mj-carousel.</span>postRender ($)](#apidoc.element.mjml.elements.mj-carousel.postRender)
1.  object <span class="apidocSignatureSpan">mjml.elements.mj-carousel.</span>baseStyles
1.  object <span class="apidocSignatureSpan">mjml.elements.mj-carousel.</span>defaultMJMLDefinition
1.  object <span class="apidocSignatureSpan">mjml.elements.mj-carousel.</span>parentTag
1.  string <span class="apidocSignatureSpan">mjml.elements.mj-carousel.</span>tagName

#### [module mjml.elements.mj-column](#apidoc.module.mjml.elements.mj-column)
1.  [function <span class="apidocSignatureSpan">mjml.elements.</span>mj-column (props)](#apidoc.element.mjml.elements.mj-column.mj-column)
1.  [function <span class="apidocSignatureSpan">mjml.elements.mj-column.</span>postRender ($)](#apidoc.element.mjml.elements.mj-column.postRender)
1.  object <span class="apidocSignatureSpan">mjml.elements.mj-column.</span>baseStyles
1.  object <span class="apidocSignatureSpan">mjml.elements.mj-column.</span>defaultMJMLDefinition
1.  object <span class="apidocSignatureSpan">mjml.elements.mj-column.</span>parentTag
1.  string <span class="apidocSignatureSpan">mjml.elements.mj-column.</span>tagName

#### [module mjml.elements.mj-container](#apidoc.module.mjml.elements.mj-container)
1.  [function <span class="apidocSignatureSpan">mjml.elements.</span>mj-container (props)](#apidoc.element.mjml.elements.mj-container.mj-container)
1.  [function <span class="apidocSignatureSpan">mjml.elements.mj-container.</span>postRender ($)](#apidoc.element.mjml.elements.mj-container.postRender)
1.  object <span class="apidocSignatureSpan">mjml.elements.mj-container.</span>defaultMJMLDefinition
1.  object <span class="apidocSignatureSpan">mjml.elements.mj-container.</span>parentTag
1.  string <span class="apidocSignatureSpan">mjml.elements.mj-container.</span>tagName

#### [module mjml.elements.mj-divider](#apidoc.module.mjml.elements.mj-divider)
1.  boolean <span class="apidocSignatureSpan">mjml.elements.mj-divider.</span>selfClosingTag
1.  [function <span class="apidocSignatureSpan">mjml.elements.</span>mj-divider (props)](#apidoc.element.mjml.elements.mj-divider.mj-divider)
1.  [function <span class="apidocSignatureSpan">mjml.elements.mj-divider.</span>postRender ($)](#apidoc.element.mjml.elements.mj-divider.postRender)
1.  object <span class="apidocSignatureSpan">mjml.elements.mj-divider.</span>baseStyles
1.  object <span class="apidocSignatureSpan">mjml.elements.mj-divider.</span>defaultMJMLDefinition
1.  object <span class="apidocSignatureSpan">mjml.elements.mj-divider.</span>parentTag
1.  string <span class="apidocSignatureSpan">mjml.elements.mj-divider.</span>tagName

#### [module mjml.elements.mj-group](#apidoc.module.mjml.elements.mj-group)
1.  [function <span class="apidocSignatureSpan">mjml.elements.</span>mj-group (props)](#apidoc.element.mjml.elements.mj-group.mj-group)
1.  [function <span class="apidocSignatureSpan">mjml.elements.mj-group.</span>postRender ($)](#apidoc.element.mjml.elements.mj-group.postRender)
1.  object <span class="apidocSignatureSpan">mjml.elements.mj-group.</span>baseStyles
1.  object <span class="apidocSignatureSpan">mjml.elements.mj-group.</span>defaultMJMLDefinition
1.  object <span class="apidocSignatureSpan">mjml.elements.mj-group.</span>parentTag
1.  string <span class="apidocSignatureSpan">mjml.elements.mj-group.</span>tagName

#### [module mjml.elements.mj-hero](#apidoc.module.mjml.elements.mj-hero)
1.  boolean <span class="apidocSignatureSpan">mjml.elements.mj-hero.</span>endingTag
1.  [function <span class="apidocSignatureSpan">mjml.elements.</span>mj-hero (props)](#apidoc.element.mjml.elements.mj-hero.mj-hero)
1.  [function <span class="apidocSignatureSpan">mjml.elements.mj-hero.</span>postRender ($)](#apidoc.element.mjml.elements.mj-hero.postRender)
1.  object <span class="apidocSignatureSpan">mjml.elements.mj-hero.</span>baseStyles
1.  object <span class="apidocSignatureSpan">mjml.elements.mj-hero.</span>defaultMJMLDefinition
1.  object <span class="apidocSignatureSpan">mjml.elements.mj-hero.</span>parentTag
1.  string <span class="apidocSignatureSpan">mjml.elements.mj-hero.</span>tagName

#### [module mjml.elements.mj-hero-content](#apidoc.module.mjml.elements.mj-hero-content)
1.  boolean <span class="apidocSignatureSpan">mjml.elements.mj-hero-content.</span>endingTag
1.  [function <span class="apidocSignatureSpan">mjml.elements.</span>mj-hero-content (props)](#apidoc.element.mjml.elements.mj-hero-content.mj-hero-content)
1.  [function <span class="apidocSignatureSpan">mjml.elements.mj-hero-content.</span>postRender ($)](#apidoc.element.mjml.elements.mj-hero-content.postRender)
1.  object <span class="apidocSignatureSpan">mjml.elements.mj-hero-content.</span>baseStyles
1.  object <span class="apidocSignatureSpan">mjml.elements.mj-hero-content.</span>defaultMJMLDefinition
1.  object <span class="apidocSignatureSpan">mjml.elements.mj-hero-content.</span>parentTag
1.  string <span class="apidocSignatureSpan">mjml.elements.mj-hero-content.</span>tagName

#### [module mjml.elements.mj-inline-links](#apidoc.module.mjml.elements.mj-inline-links)
1.  [function <span class="apidocSignatureSpan">mjml.elements.</span>mj-inline-links (props)](#apidoc.element.mjml.elements.mj-inline-links.mj-inline-links)
1.  [function <span class="apidocSignatureSpan">mjml.elements.mj-inline-links.</span>postRender ($)](#apidoc.element.mjml.elements.mj-inline-links.postRender)
1.  object <span class="apidocSignatureSpan">mjml.elements.mj-inline-links.</span>baseStyles
1.  object <span class="apidocSignatureSpan">mjml.elements.mj-inline-links.</span>defaultMJMLDefinition
1.  object <span class="apidocSignatureSpan">mjml.elements.mj-inline-links.</span>parentTag
1.  string <span class="apidocSignatureSpan">mjml.elements.mj-inline-links.</span>tagName

#### [module mjml.elements.mj-link](#apidoc.module.mjml.elements.mj-link)
1.  boolean <span class="apidocSignatureSpan">mjml.elements.mj-link.</span>endingTag
1.  [function <span class="apidocSignatureSpan">mjml.elements.</span>mj-link (props)](#apidoc.element.mjml.elements.mj-link.mj-link)
1.  [function <span class="apidocSignatureSpan">mjml.elements.mj-link.</span>postRender ($)](#apidoc.element.mjml.elements.mj-link.postRender)
1.  object <span class="apidocSignatureSpan">mjml.elements.mj-link.</span>baseStyles
1.  object <span class="apidocSignatureSpan">mjml.elements.mj-link.</span>defaultMJMLDefinition
1.  object <span class="apidocSignatureSpan">mjml.elements.mj-link.</span>parentTag
1.  string <span class="apidocSignatureSpan">mjml.elements.mj-link.</span>tagName

#### [module mjml.elements.mj-raw](#apidoc.module.mjml.elements.mj-raw)
1.  boolean <span class="apidocSignatureSpan">mjml.elements.mj-raw.</span>endingTag
1.  boolean <span class="apidocSignatureSpan">mjml.elements.mj-raw.</span>rawElement
1.  [function <span class="apidocSignatureSpan">mjml.elements.</span>mj-raw (props)](#apidoc.element.mjml.elements.mj-raw.mj-raw)
1.  [function <span class="apidocSignatureSpan">mjml.elements.mj-raw.</span>postRender ($)](#apidoc.element.mjml.elements.mj-raw.postRender)
1.  object <span class="apidocSignatureSpan">mjml.elements.mj-raw.</span>defaultMJMLDefinition
1.  object <span class="apidocSignatureSpan">mjml.elements.mj-raw.</span>parentTag
1.  string <span class="apidocSignatureSpan">mjml.elements.mj-raw.</span>tagName

#### [module mjml.elements.mj-section](#apidoc.module.mjml.elements.mj-section)
1.  [function <span class="apidocSignatureSpan">mjml.elements.</span>mj-section (props)](#apidoc.element.mjml.elements.mj-section.mj-section)
1.  [function <span class="apidocSignatureSpan">mjml.elements.mj-section.</span>postRender ($)](#apidoc.element.mjml.elements.mj-section.postRender)
1.  object <span class="apidocSignatureSpan">mjml.elements.mj-section.</span>baseStyles
1.  object <span class="apidocSignatureSpan">mjml.elements.mj-section.</span>defaultMJMLDefinition
1.  object <span class="apidocSignatureSpan">mjml.elements.mj-section.</span>parentTag
1.  string <span class="apidocSignatureSpan">mjml.elements.mj-section.</span>tagName

#### [module mjml.elements.mj-social](#apidoc.module.mjml.elements.mj-social)
1.  boolean <span class="apidocSignatureSpan">mjml.elements.mj-social.</span>selfClosingTag
1.  [function <span class="apidocSignatureSpan">mjml.elements.</span>mj-social (props)](#apidoc.element.mjml.elements.mj-social.mj-social)
1.  [function <span class="apidocSignatureSpan">mjml.elements.mj-social.</span>postRender ($)](#apidoc.element.mjml.elements.mj-social.postRender)
1.  object <span class="apidocSignatureSpan">mjml.elements.mj-social.</span>baseStyles
1.  object <span class="apidocSignatureSpan">mjml.elements.mj-social.</span>buttonDefinitions
1.  object <span class="apidocSignatureSpan">mjml.elements.mj-social.</span>defaultMJMLDefinition
1.  object <span class="apidocSignatureSpan">mjml.elements.mj-social.</span>parentTag
1.  string <span class="apidocSignatureSpan">mjml.elements.mj-social.</span>tagName

#### [module mjml.elements.mj-text](#apidoc.module.mjml.elements.mj-text)
1.  boolean <span class="apidocSignatureSpan">mjml.elements.mj-text.</span>endingTag
1.  [function <span class="apidocSignatureSpan">mjml.elements.</span>mj-text (props)](#apidoc.element.mjml.elements.mj-text.mj-text)
1.  [function <span class="apidocSignatureSpan">mjml.elements.mj-text.</span>postRender ($)](#apidoc.element.mjml.elements.mj-text.postRender)
1.  object <span class="apidocSignatureSpan">mjml.elements.mj-text.</span>baseStyles
1.  object <span class="apidocSignatureSpan">mjml.elements.mj-text.</span>defaultMJMLDefinition
1.  object <span class="apidocSignatureSpan">mjml.elements.mj-text.</span>parentTag
1.  string <span class="apidocSignatureSpan">mjml.elements.mj-text.</span>tagName

#### [module mjml.elements.mj-wrapper](#apidoc.module.mjml.elements.mj-wrapper)
1.  [function <span class="apidocSignatureSpan">mjml.elements.</span>mj-wrapper ()](#apidoc.element.mjml.elements.mj-wrapper.mj-wrapper)
1.  [function <span class="apidocSignatureSpan">mjml.elements.mj-wrapper.</span>postRender ($)](#apidoc.element.mjml.elements.mj-wrapper.postRender)
1.  object <span class="apidocSignatureSpan">mjml.elements.mj-wrapper.</span>defaultMJMLDefinition
1.  object <span class="apidocSignatureSpan">mjml.elements.mj-wrapper.</span>parentTag
1.  string <span class="apidocSignatureSpan">mjml.elements.mj-wrapper.</span>tagName

#### [module mjml.helpers](#apidoc.module.mjml.helpers)
1.  [function <span class="apidocSignatureSpan">mjml.helpers.</span>defaultUnit (units)](#apidoc.element.mjml.helpers.defaultUnit)
1.  [function <span class="apidocSignatureSpan">mjml.helpers.</span>merge ()](#apidoc.element.mjml.helpers.merge)
1.  [function <span class="apidocSignatureSpan">mjml.helpers.</span>widthParser (width)](#apidoc.element.mjml.helpers.widthParser)
1.  object <span class="apidocSignatureSpan">mjml.helpers.</span>dom
1.  string <span class="apidocSignatureSpan">mjml.helpers.</span>endConditionalTag
1.  string <span class="apidocSignatureSpan">mjml.helpers.</span>endNegationConditionalTag
1.  string <span class="apidocSignatureSpan">mjml.helpers.</span>startConditionalTag
1.  string <span class="apidocSignatureSpan">mjml.helpers.</span>startNegationConditionalTag

#### [module mjml.helpers.dom](#apidoc.module.mjml.helpers.dom)
1.  [function <span class="apidocSignatureSpan">mjml.helpers.dom.</span>getAttributes (element)](#apidoc.element.mjml.helpers.dom.getAttributes)
1.  [function <span class="apidocSignatureSpan">mjml.helpers.dom.</span>getChildren (element)](#apidoc.element.mjml.helpers.dom.getChildren)
1.  [function <span class="apidocSignatureSpan">mjml.helpers.dom.</span>getHTML ($)](#apidoc.element.mjml.helpers.dom.getHTML)
1.  [function <span class="apidocSignatureSpan">mjml.helpers.dom.</span>parseHTML (str)](#apidoc.element.mjml.helpers.dom.parseHTML)
1.  [function <span class="apidocSignatureSpan">mjml.helpers.dom.</span>parseXML (str)](#apidoc.element.mjml.helpers.dom.parseXML)
1.  [function <span class="apidocSignatureSpan">mjml.helpers.dom.</span>replaceContentByCdata (tag)](#apidoc.element.mjml.helpers.dom.replaceContentByCdata)

#### [module mjml.rulesCollection](#apidoc.module.mjml.rulesCollection)
1.  [function <span class="apidocSignatureSpan">mjml.rulesCollection.</span>validChildren (element)](#apidoc.element.mjml.rulesCollection.validChildren)
1.  [function <span class="apidocSignatureSpan">mjml.rulesCollection.</span>validateAttribute (element)](#apidoc.element.mjml.rulesCollection.validateAttribute)
1.  [function <span class="apidocSignatureSpan">mjml.rulesCollection.</span>validateTag (element)](#apidoc.element.mjml.rulesCollection.validateTag)



# <a name="apidoc.module.mjml"></a>[module mjml](#apidoc.module.mjml)

#### <a name="apidoc.element.mjml.MJMLElement"></a>[function <span class="apidocSignatureSpan">mjml.</span>MJMLElement (ComposedComponent)](#apidoc.element.mjml.MJMLElement)
- description and source-code
```javascript
function createComponent(ComposedComponent) {

  var baseStyles = {
    td: {
      wordBreak: 'break-word'
    }
  };

  var MJMLElement = function (_Component) {
    _inherits(MJMLElement, _Component);

    function MJMLElement(props) {
      _classCallCheck(this, MJMLElement);

      var _this = _possibleConstructorReturn(this, (MJMLElement.__proto__ || Object.getPrototypeOf(MJMLElement)).call(this, props
));

      _this.mjAttribute = function (name) {
        return _this.mjml.getIn(['attributes', name]);
      };

      _this.mjName = function () {
        return _this.constructor.tagName;
      };

      _this.mjContent = function () {
        var content = _this.mjml.get('content');

        if (content) {
          return (0, _trim2.default)(content);
        }

        return _react2.default.Children.map(_this.props.children, function (child) {
          if (typeof child === 'string') {
            return child;
          }
          return _server2.default.renderToStaticMarkup(child);
        });
      };

      _this.isInheritedAttributes = function (name) {
        return _this.mjml.get('inheritedAttributes') && _this.mjml.get('inheritedAttributes').includes(name);
      };

      _this.getWidth = function () {
        return _this.mjAttribute('rawPxWidth') || _this.mjAttribute('width');
      };

      _this.getParentWidth = function () {
        return _this.mjAttribute('parentWidth');
      };

      _this.renderWrappedOutlookChildren = function (children) {
        children = _react2.default.Children.toArray(children);

        var realChildren = children.filter(function (child) {
          return !child.props.mjml || child.props.mjml.get('tagName') !== 'mj-raw';
        });

        var prefix = _this.mjName() + '-outlook';
        var parentWidth = _this.getWidth();
        var siblings = realChildren.length;
        var elementsWidth = realChildren.map(function (element) {
          if (_this.isInheritedAttributes('width')) {
            return parseInt(parentWidth);
          }

          return getElementWidth({ element: element, siblings: siblings, parentWidth: parentWidth });
        });

        var wrappedElements = [];

        if (siblings == 0) {
          return wrappedElements;
        }

        wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-open', className: prefix + '-open', 'data-width
': elementsWidth[0] }));

        var i = 0;

        children.forEach(function (child) {
          var childProps = Object.assign({}, child.props);

          if (childProps.mjml) {
            childProps.mjml = childProps.mjml.setIn(['attributes', 'rawPxWidth'], elementsWidth[i]);

            if (_this.mjml.get('inheritedAttributes')) {
              childProps.mjml = childProps.mjml.mergeIn(['attributes', _this.inheritedAttributes()]);
            }
          } else {
            Object.assign(childProps, { rawPxWidth: elementsWidth[i] });

            if (_this.mjml.get('inheritedAttributes')) {
              Object.assign(childProps, _this.inheritedAttributes());
            }
          }

          var childWithProps = _react2.default.cloneElement(child, childProps);

          wrappedElements.push(childWithProps);
          if (!childWithProps.type.rawElement && i < realChildren.length - 1) {
            wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-' + i, className: prefix + '-line', 'data-
width': elementsWidth[++i] }));
          }
        });

        wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-close', className: prefix + '-close' }));

        return wrappedElements;
      };

      _this.paddingParser = function (direction) {
        var prefix = arguments.length > 1 && arguments[1] !== undefined ? arguments[1] : '';

        var paddingDirection = _this.mjAttribute(prefix + 'padding-' + direction);
        var padding = _this.mjAttribute(prefix + 'padding');

        if (paddingDirection != null) {
          return parseInt(paddingDirection);
        }

        if (!padding) {
          return 0;
        } ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mjml.MJMLRenderer"></a>[function <span class="apidocSignatureSpan">mjml.</span>MJMLRenderer (content)](#apidoc.element.mjml.MJMLRenderer)
- description and source-code
```javascript
function MJMLRenderer(content) {
  var options = arguments.length > 1 && arguments[1] !== undefined ? arguments[1] : {};

  _classCallCheck(this, MJMLRenderer);

  if (!(0, _isBrowser2.default)()) {
    (0, _config2.default)();
  }

  this.attributes = {
    container: (0, _defaultContainer2.default)(),
    defaultAttributes: {},
    cssClasses: {},
    css: [],
    inlineCSS: [],
    fonts: (0, _cloneDeep2.default)(_listFontsImports2.default)
  };

  this.content = content;
  this.options = (0, _defaults2.default)(options, { level: "soft", disableMjStyle: false, disableMjInclude: false, disableMinify
: false });

  if (typeof this.content === 'string') {
    this.parseDocument();
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mjml.MJMLValidator"></a>[function <span class="apidocSignatureSpan">mjml.</span>MJMLValidator (element)](#apidoc.element.mjml.MJMLValidator)
- description and source-code
```javascript
function validateNode(element) {
  var children = element.children;


  var errors = _concat2.default.apply(undefined, [errors].concat(_toConsumableArray((0, _values2.default)(_MJMLRulesCollection2.
default).map(function (rule) {
    return rule(element);
  }))));

  if (children && children.length > 0) {
    errors = _concat2.default.apply(undefined, [errors].concat(_toConsumableArray(children.map(function (child) {
      return validateNode(child);
    }))));
  }

  return (0, _filter2.default)(errors);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mjml.documentParser"></a>[function <span class="apidocSignatureSpan">mjml.</span>documentParser (content, attributes)](#apidoc.element.mjml.documentParser)
- description and source-code
```javascript
function documentParser(content, attributes) {
  var documentParser = require('./parsers/document').default;

  return documentParser(content, attributes);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mjml.elements.mj-accordion"></a>[function <span class="apidocSignatureSpan">mjml.</span>elements.mj-accordion (props)](#apidoc.element.mjml.elements.mj-accordion)
- description and source-code
```javascript
function MJMLElement(props) {
  _classCallCheck(this, MJMLElement);

  var _this = _possibleConstructorReturn(this, (MJMLElement.__proto__ || Object.getPrototypeOf(MJMLElement)).call(this, props));

  _this.mjAttribute = function (name) {
    return _this.mjml.getIn(['attributes', name]);
  };

  _this.mjName = function () {
    return _this.constructor.tagName;
  };

  _this.mjContent = function () {
    var content = _this.mjml.get('content');

    if (content) {
      return (0, _trim2.default)(content);
    }

    return _react2.default.Children.map(_this.props.children, function (child) {
      if (typeof child === 'string') {
        return child;
      }
      return _server2.default.renderToStaticMarkup(child);
    });
  };

  _this.isInheritedAttributes = function (name) {
    return _this.mjml.get('inheritedAttributes') && _this.mjml.get('inheritedAttributes').includes(name);
  };

  _this.getWidth = function () {
    return _this.mjAttribute('rawPxWidth') || _this.mjAttribute('width');
  };

  _this.getParentWidth = function () {
    return _this.mjAttribute('parentWidth');
  };

  _this.renderWrappedOutlookChildren = function (children) {
    children = _react2.default.Children.toArray(children);

    var realChildren = children.filter(function (child) {
      return !child.props.mjml || child.props.mjml.get('tagName') !== 'mj-raw';
    });

    var prefix = _this.mjName() + '-outlook';
    var parentWidth = _this.getWidth();
    var siblings = realChildren.length;
    var elementsWidth = realChildren.map(function (element) {
      if (_this.isInheritedAttributes('width')) {
        return parseInt(parentWidth);
      }

      return getElementWidth({ element: element, siblings: siblings, parentWidth: parentWidth });
    });

    var wrappedElements = [];

    if (siblings == 0) {
      return wrappedElements;
    }

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-open', className: prefix + '-open', 'data-width':
elementsWidth[0] }));

    var i = 0;

    children.forEach(function (child) {
      var childProps = Object.assign({}, child.props);

      if (childProps.mjml) {
        childProps.mjml = childProps.mjml.setIn(['attributes', 'rawPxWidth'], elementsWidth[i]);

        if (_this.mjml.get('inheritedAttributes')) {
          childProps.mjml = childProps.mjml.mergeIn(['attributes', _this.inheritedAttributes()]);
        }
      } else {
        Object.assign(childProps, { rawPxWidth: elementsWidth[i] });

        if (_this.mjml.get('inheritedAttributes')) {
          Object.assign(childProps, _this.inheritedAttributes());
        }
      }

      var childWithProps = _react2.default.cloneElement(child, childProps);

      wrappedElements.push(childWithProps);
      if (!childWithProps.type.rawElement && i < realChildren.length - 1) {
        wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-' + i, className: prefix + '-line', 'data-width
': elementsWidth[++i] }));
      }
    });

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-close', className: prefix + '-close' }));

    return wrappedElements;
  };

  _this.paddingParser = function (direction) {
    var prefix = arguments.length > 1 && arguments[1] !== undefined ? arguments[1] : '';

    var paddingDirection = _this.mjAttribute(prefix + 'padding-' + direction);
    var padding = _this.mjAttribute(prefix + 'padding');

    if (paddingDirection != null) {
      return parseInt(paddingDirection);
    }

    if (!padding) {
      return 0;
    }

    var paddings = padding.split(' ');
    var directions = {};

    switch (paddings.length) {
      case 1:
        return parseInt(padding);
      case 2:
        directions = { top: 0, bottom: 0, left: 1, right: 1 };
        break;
      case 3:
        directions = { top: 0, left: 1, right: 1, bottom: 2 };
        break;
      case 4:
        directions = { top: 0, right: 1, bottom: 2, left: 3 };
        break;
    }

    return parseInt(paddings[directions[direction]] || 0);
  };

  _this.mjml = props.mjml || _immutable2. ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mjml.elements.mj-carousel"></a>[function <span class="apidocSignatureSpan">mjml.</span>elements.mj-carousel (props)](#apidoc.element.mjml.elements.mj-carousel)
- description and source-code
```javascript
function MJMLElement(props) {
  _classCallCheck(this, MJMLElement);

  var _this = _possibleConstructorReturn(this, (MJMLElement.__proto__ || Object.getPrototypeOf(MJMLElement)).call(this, props));

  _this.mjAttribute = function (name) {
    return _this.mjml.getIn(['attributes', name]);
  };

  _this.mjName = function () {
    return _this.constructor.tagName;
  };

  _this.mjContent = function () {
    var content = _this.mjml.get('content');

    if (content) {
      return (0, _trim2.default)(content);
    }

    return _react2.default.Children.map(_this.props.children, function (child) {
      if (typeof child === 'string') {
        return child;
      }
      return _server2.default.renderToStaticMarkup(child);
    });
  };

  _this.isInheritedAttributes = function (name) {
    return _this.mjml.get('inheritedAttributes') && _this.mjml.get('inheritedAttributes').includes(name);
  };

  _this.getWidth = function () {
    return _this.mjAttribute('rawPxWidth') || _this.mjAttribute('width');
  };

  _this.getParentWidth = function () {
    return _this.mjAttribute('parentWidth');
  };

  _this.renderWrappedOutlookChildren = function (children) {
    children = _react2.default.Children.toArray(children);

    var realChildren = children.filter(function (child) {
      return !child.props.mjml || child.props.mjml.get('tagName') !== 'mj-raw';
    });

    var prefix = _this.mjName() + '-outlook';
    var parentWidth = _this.getWidth();
    var siblings = realChildren.length;
    var elementsWidth = realChildren.map(function (element) {
      if (_this.isInheritedAttributes('width')) {
        return parseInt(parentWidth);
      }

      return getElementWidth({ element: element, siblings: siblings, parentWidth: parentWidth });
    });

    var wrappedElements = [];

    if (siblings == 0) {
      return wrappedElements;
    }

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-open', className: prefix + '-open', 'data-width':
elementsWidth[0] }));

    var i = 0;

    children.forEach(function (child) {
      var childProps = Object.assign({}, child.props);

      if (childProps.mjml) {
        childProps.mjml = childProps.mjml.setIn(['attributes', 'rawPxWidth'], elementsWidth[i]);

        if (_this.mjml.get('inheritedAttributes')) {
          childProps.mjml = childProps.mjml.mergeIn(['attributes', _this.inheritedAttributes()]);
        }
      } else {
        Object.assign(childProps, { rawPxWidth: elementsWidth[i] });

        if (_this.mjml.get('inheritedAttributes')) {
          Object.assign(childProps, _this.inheritedAttributes());
        }
      }

      var childWithProps = _react2.default.cloneElement(child, childProps);

      wrappedElements.push(childWithProps);
      if (!childWithProps.type.rawElement && i < realChildren.length - 1) {
        wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-' + i, className: prefix + '-line', 'data-width
': elementsWidth[++i] }));
      }
    });

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-close', className: prefix + '-close' }));

    return wrappedElements;
  };

  _this.paddingParser = function (direction) {
    var prefix = arguments.length > 1 && arguments[1] !== undefined ? arguments[1] : '';

    var paddingDirection = _this.mjAttribute(prefix + 'padding-' + direction);
    var padding = _this.mjAttribute(prefix + 'padding');

    if (paddingDirection != null) {
      return parseInt(paddingDirection);
    }

    if (!padding) {
      return 0;
    }

    var paddings = padding.split(' ');
    var directions = {};

    switch (paddings.length) {
      case 1:
        return parseInt(padding);
      case 2:
        directions = { top: 0, bottom: 0, left: 1, right: 1 };
        break;
      case 3:
        directions = { top: 0, left: 1, right: 1, bottom: 2 };
        break;
      case 4:
        directions = { top: 0, right: 1, bottom: 2, left: 3 };
        break;
    }

    return parseInt(paddings[directions[direction]] || 0);
  };

  _this.mjml = props.mjml || _immutable2. ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mjml.elements.mj-column"></a>[function <span class="apidocSignatureSpan">mjml.</span>elements.mj-column (props)](#apidoc.element.mjml.elements.mj-column)
- description and source-code
```javascript
function MJMLElement(props) {
  _classCallCheck(this, MJMLElement);

  var _this = _possibleConstructorReturn(this, (MJMLElement.__proto__ || Object.getPrototypeOf(MJMLElement)).call(this, props));

  _this.mjAttribute = function (name) {
    return _this.mjml.getIn(['attributes', name]);
  };

  _this.mjName = function () {
    return _this.constructor.tagName;
  };

  _this.mjContent = function () {
    var content = _this.mjml.get('content');

    if (content) {
      return (0, _trim2.default)(content);
    }

    return _react2.default.Children.map(_this.props.children, function (child) {
      if (typeof child === 'string') {
        return child;
      }
      return _server2.default.renderToStaticMarkup(child);
    });
  };

  _this.isInheritedAttributes = function (name) {
    return _this.mjml.get('inheritedAttributes') && _this.mjml.get('inheritedAttributes').includes(name);
  };

  _this.getWidth = function () {
    return _this.mjAttribute('rawPxWidth') || _this.mjAttribute('width');
  };

  _this.getParentWidth = function () {
    return _this.mjAttribute('parentWidth');
  };

  _this.renderWrappedOutlookChildren = function (children) {
    children = _react2.default.Children.toArray(children);

    var realChildren = children.filter(function (child) {
      return !child.props.mjml || child.props.mjml.get('tagName') !== 'mj-raw';
    });

    var prefix = _this.mjName() + '-outlook';
    var parentWidth = _this.getWidth();
    var siblings = realChildren.length;
    var elementsWidth = realChildren.map(function (element) {
      if (_this.isInheritedAttributes('width')) {
        return parseInt(parentWidth);
      }

      return getElementWidth({ element: element, siblings: siblings, parentWidth: parentWidth });
    });

    var wrappedElements = [];

    if (siblings == 0) {
      return wrappedElements;
    }

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-open', className: prefix + '-open', 'data-width':
elementsWidth[0] }));

    var i = 0;

    children.forEach(function (child) {
      var childProps = Object.assign({}, child.props);

      if (childProps.mjml) {
        childProps.mjml = childProps.mjml.setIn(['attributes', 'rawPxWidth'], elementsWidth[i]);

        if (_this.mjml.get('inheritedAttributes')) {
          childProps.mjml = childProps.mjml.mergeIn(['attributes', _this.inheritedAttributes()]);
        }
      } else {
        Object.assign(childProps, { rawPxWidth: elementsWidth[i] });

        if (_this.mjml.get('inheritedAttributes')) {
          Object.assign(childProps, _this.inheritedAttributes());
        }
      }

      var childWithProps = _react2.default.cloneElement(child, childProps);

      wrappedElements.push(childWithProps);
      if (!childWithProps.type.rawElement && i < realChildren.length - 1) {
        wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-' + i, className: prefix + '-line', 'data-width
': elementsWidth[++i] }));
      }
    });

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-close', className: prefix + '-close' }));

    return wrappedElements;
  };

  _this.paddingParser = function (direction) {
    var prefix = arguments.length > 1 && arguments[1] !== undefined ? arguments[1] : '';

    var paddingDirection = _this.mjAttribute(prefix + 'padding-' + direction);
    var padding = _this.mjAttribute(prefix + 'padding');

    if (paddingDirection != null) {
      return parseInt(paddingDirection);
    }

    if (!padding) {
      return 0;
    }

    var paddings = padding.split(' ');
    var directions = {};

    switch (paddings.length) {
      case 1:
        return parseInt(padding);
      case 2:
        directions = { top: 0, bottom: 0, left: 1, right: 1 };
        break;
      case 3:
        directions = { top: 0, left: 1, right: 1, bottom: 2 };
        break;
      case 4:
        directions = { top: 0, right: 1, bottom: 2, left: 3 };
        break;
    }

    return parseInt(paddings[directions[direction]] || 0);
  };

  _this.mjml = props.mjml || _immutable2. ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mjml.elements.mj-container"></a>[function <span class="apidocSignatureSpan">mjml.</span>elements.mj-container (props)](#apidoc.element.mjml.elements.mj-container)
- description and source-code
```javascript
function MJMLElement(props) {
  _classCallCheck(this, MJMLElement);

  var _this = _possibleConstructorReturn(this, (MJMLElement.__proto__ || Object.getPrototypeOf(MJMLElement)).call(this, props));

  _this.mjAttribute = function (name) {
    return _this.mjml.getIn(['attributes', name]);
  };

  _this.mjName = function () {
    return _this.constructor.tagName;
  };

  _this.mjContent = function () {
    var content = _this.mjml.get('content');

    if (content) {
      return (0, _trim2.default)(content);
    }

    return _react2.default.Children.map(_this.props.children, function (child) {
      if (typeof child === 'string') {
        return child;
      }
      return _server2.default.renderToStaticMarkup(child);
    });
  };

  _this.isInheritedAttributes = function (name) {
    return _this.mjml.get('inheritedAttributes') && _this.mjml.get('inheritedAttributes').includes(name);
  };

  _this.getWidth = function () {
    return _this.mjAttribute('rawPxWidth') || _this.mjAttribute('width');
  };

  _this.getParentWidth = function () {
    return _this.mjAttribute('parentWidth');
  };

  _this.renderWrappedOutlookChildren = function (children) {
    children = _react2.default.Children.toArray(children);

    var realChildren = children.filter(function (child) {
      return !child.props.mjml || child.props.mjml.get('tagName') !== 'mj-raw';
    });

    var prefix = _this.mjName() + '-outlook';
    var parentWidth = _this.getWidth();
    var siblings = realChildren.length;
    var elementsWidth = realChildren.map(function (element) {
      if (_this.isInheritedAttributes('width')) {
        return parseInt(parentWidth);
      }

      return getElementWidth({ element: element, siblings: siblings, parentWidth: parentWidth });
    });

    var wrappedElements = [];

    if (siblings == 0) {
      return wrappedElements;
    }

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-open', className: prefix + '-open', 'data-width':
elementsWidth[0] }));

    var i = 0;

    children.forEach(function (child) {
      var childProps = Object.assign({}, child.props);

      if (childProps.mjml) {
        childProps.mjml = childProps.mjml.setIn(['attributes', 'rawPxWidth'], elementsWidth[i]);

        if (_this.mjml.get('inheritedAttributes')) {
          childProps.mjml = childProps.mjml.mergeIn(['attributes', _this.inheritedAttributes()]);
        }
      } else {
        Object.assign(childProps, { rawPxWidth: elementsWidth[i] });

        if (_this.mjml.get('inheritedAttributes')) {
          Object.assign(childProps, _this.inheritedAttributes());
        }
      }

      var childWithProps = _react2.default.cloneElement(child, childProps);

      wrappedElements.push(childWithProps);
      if (!childWithProps.type.rawElement && i < realChildren.length - 1) {
        wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-' + i, className: prefix + '-line', 'data-width
': elementsWidth[++i] }));
      }
    });

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-close', className: prefix + '-close' }));

    return wrappedElements;
  };

  _this.paddingParser = function (direction) {
    var prefix = arguments.length > 1 && arguments[1] !== undefined ? arguments[1] : '';

    var paddingDirection = _this.mjAttribute(prefix + 'padding-' + direction);
    var padding = _this.mjAttribute(prefix + 'padding');

    if (paddingDirection != null) {
      return parseInt(paddingDirection);
    }

    if (!padding) {
      return 0;
    }

    var paddings = padding.split(' ');
    var directions = {};

    switch (paddings.length) {
      case 1:
        return parseInt(padding);
      case 2:
        directions = { top: 0, bottom: 0, left: 1, right: 1 };
        break;
      case 3:
        directions = { top: 0, left: 1, right: 1, bottom: 2 };
        break;
      case 4:
        directions = { top: 0, right: 1, bottom: 2, left: 3 };
        break;
    }

    return parseInt(paddings[directions[direction]] || 0);
  };

  _this.mjml = props.mjml || _immutable2. ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mjml.elements.mj-divider"></a>[function <span class="apidocSignatureSpan">mjml.</span>elements.mj-divider (props)](#apidoc.element.mjml.elements.mj-divider)
- description and source-code
```javascript
function MJMLElement(props) {
  _classCallCheck(this, MJMLElement);

  var _this = _possibleConstructorReturn(this, (MJMLElement.__proto__ || Object.getPrototypeOf(MJMLElement)).call(this, props));

  _this.mjAttribute = function (name) {
    return _this.mjml.getIn(['attributes', name]);
  };

  _this.mjName = function () {
    return _this.constructor.tagName;
  };

  _this.mjContent = function () {
    var content = _this.mjml.get('content');

    if (content) {
      return (0, _trim2.default)(content);
    }

    return _react2.default.Children.map(_this.props.children, function (child) {
      if (typeof child === 'string') {
        return child;
      }
      return _server2.default.renderToStaticMarkup(child);
    });
  };

  _this.isInheritedAttributes = function (name) {
    return _this.mjml.get('inheritedAttributes') && _this.mjml.get('inheritedAttributes').includes(name);
  };

  _this.getWidth = function () {
    return _this.mjAttribute('rawPxWidth') || _this.mjAttribute('width');
  };

  _this.getParentWidth = function () {
    return _this.mjAttribute('parentWidth');
  };

  _this.renderWrappedOutlookChildren = function (children) {
    children = _react2.default.Children.toArray(children);

    var realChildren = children.filter(function (child) {
      return !child.props.mjml || child.props.mjml.get('tagName') !== 'mj-raw';
    });

    var prefix = _this.mjName() + '-outlook';
    var parentWidth = _this.getWidth();
    var siblings = realChildren.length;
    var elementsWidth = realChildren.map(function (element) {
      if (_this.isInheritedAttributes('width')) {
        return parseInt(parentWidth);
      }

      return getElementWidth({ element: element, siblings: siblings, parentWidth: parentWidth });
    });

    var wrappedElements = [];

    if (siblings == 0) {
      return wrappedElements;
    }

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-open', className: prefix + '-open', 'data-width':
elementsWidth[0] }));

    var i = 0;

    children.forEach(function (child) {
      var childProps = Object.assign({}, child.props);

      if (childProps.mjml) {
        childProps.mjml = childProps.mjml.setIn(['attributes', 'rawPxWidth'], elementsWidth[i]);

        if (_this.mjml.get('inheritedAttributes')) {
          childProps.mjml = childProps.mjml.mergeIn(['attributes', _this.inheritedAttributes()]);
        }
      } else {
        Object.assign(childProps, { rawPxWidth: elementsWidth[i] });

        if (_this.mjml.get('inheritedAttributes')) {
          Object.assign(childProps, _this.inheritedAttributes());
        }
      }

      var childWithProps = _react2.default.cloneElement(child, childProps);

      wrappedElements.push(childWithProps);
      if (!childWithProps.type.rawElement && i < realChildren.length - 1) {
        wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-' + i, className: prefix + '-line', 'data-width
': elementsWidth[++i] }));
      }
    });

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-close', className: prefix + '-close' }));

    return wrappedElements;
  };

  _this.paddingParser = function (direction) {
    var prefix = arguments.length > 1 && arguments[1] !== undefined ? arguments[1] : '';

    var paddingDirection = _this.mjAttribute(prefix + 'padding-' + direction);
    var padding = _this.mjAttribute(prefix + 'padding');

    if (paddingDirection != null) {
      return parseInt(paddingDirection);
    }

    if (!padding) {
      return 0;
    }

    var paddings = padding.split(' ');
    var directions = {};

    switch (paddings.length) {
      case 1:
        return parseInt(padding);
      case 2:
        directions = { top: 0, bottom: 0, left: 1, right: 1 };
        break;
      case 3:
        directions = { top: 0, left: 1, right: 1, bottom: 2 };
        break;
      case 4:
        directions = { top: 0, right: 1, bottom: 2, left: 3 };
        break;
    }

    return parseInt(paddings[directions[direction]] || 0);
  };

  _this.mjml = props.mjml || _immutable2. ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mjml.elements.mj-group"></a>[function <span class="apidocSignatureSpan">mjml.</span>elements.mj-group (props)](#apidoc.element.mjml.elements.mj-group)
- description and source-code
```javascript
function MJMLElement(props) {
  _classCallCheck(this, MJMLElement);

  var _this = _possibleConstructorReturn(this, (MJMLElement.__proto__ || Object.getPrototypeOf(MJMLElement)).call(this, props));

  _this.mjAttribute = function (name) {
    return _this.mjml.getIn(['attributes', name]);
  };

  _this.mjName = function () {
    return _this.constructor.tagName;
  };

  _this.mjContent = function () {
    var content = _this.mjml.get('content');

    if (content) {
      return (0, _trim2.default)(content);
    }

    return _react2.default.Children.map(_this.props.children, function (child) {
      if (typeof child === 'string') {
        return child;
      }
      return _server2.default.renderToStaticMarkup(child);
    });
  };

  _this.isInheritedAttributes = function (name) {
    return _this.mjml.get('inheritedAttributes') && _this.mjml.get('inheritedAttributes').includes(name);
  };

  _this.getWidth = function () {
    return _this.mjAttribute('rawPxWidth') || _this.mjAttribute('width');
  };

  _this.getParentWidth = function () {
    return _this.mjAttribute('parentWidth');
  };

  _this.renderWrappedOutlookChildren = function (children) {
    children = _react2.default.Children.toArray(children);

    var realChildren = children.filter(function (child) {
      return !child.props.mjml || child.props.mjml.get('tagName') !== 'mj-raw';
    });

    var prefix = _this.mjName() + '-outlook';
    var parentWidth = _this.getWidth();
    var siblings = realChildren.length;
    var elementsWidth = realChildren.map(function (element) {
      if (_this.isInheritedAttributes('width')) {
        return parseInt(parentWidth);
      }

      return getElementWidth({ element: element, siblings: siblings, parentWidth: parentWidth });
    });

    var wrappedElements = [];

    if (siblings == 0) {
      return wrappedElements;
    }

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-open', className: prefix + '-open', 'data-width':
elementsWidth[0] }));

    var i = 0;

    children.forEach(function (child) {
      var childProps = Object.assign({}, child.props);

      if (childProps.mjml) {
        childProps.mjml = childProps.mjml.setIn(['attributes', 'rawPxWidth'], elementsWidth[i]);

        if (_this.mjml.get('inheritedAttributes')) {
          childProps.mjml = childProps.mjml.mergeIn(['attributes', _this.inheritedAttributes()]);
        }
      } else {
        Object.assign(childProps, { rawPxWidth: elementsWidth[i] });

        if (_this.mjml.get('inheritedAttributes')) {
          Object.assign(childProps, _this.inheritedAttributes());
        }
      }

      var childWithProps = _react2.default.cloneElement(child, childProps);

      wrappedElements.push(childWithProps);
      if (!childWithProps.type.rawElement && i < realChildren.length - 1) {
        wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-' + i, className: prefix + '-line', 'data-width
': elementsWidth[++i] }));
      }
    });

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-close', className: prefix + '-close' }));

    return wrappedElements;
  };

  _this.paddingParser = function (direction) {
    var prefix = arguments.length > 1 && arguments[1] !== undefined ? arguments[1] : '';

    var paddingDirection = _this.mjAttribute(prefix + 'padding-' + direction);
    var padding = _this.mjAttribute(prefix + 'padding');

    if (paddingDirection != null) {
      return parseInt(paddingDirection);
    }

    if (!padding) {
      return 0;
    }

    var paddings = padding.split(' ');
    var directions = {};

    switch (paddings.length) {
      case 1:
        return parseInt(padding);
      case 2:
        directions = { top: 0, bottom: 0, left: 1, right: 1 };
        break;
      case 3:
        directions = { top: 0, left: 1, right: 1, bottom: 2 };
        break;
      case 4:
        directions = { top: 0, right: 1, bottom: 2, left: 3 };
        break;
    }

    return parseInt(paddings[directions[direction]] || 0);
  };

  _this.mjml = props.mjml || _immutable2. ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mjml.elements.mj-hero"></a>[function <span class="apidocSignatureSpan">mjml.</span>elements.mj-hero (props)](#apidoc.element.mjml.elements.mj-hero)
- description and source-code
```javascript
function MJMLElement(props) {
  _classCallCheck(this, MJMLElement);

  var _this = _possibleConstructorReturn(this, (MJMLElement.__proto__ || Object.getPrototypeOf(MJMLElement)).call(this, props));

  _this.mjAttribute = function (name) {
    return _this.mjml.getIn(['attributes', name]);
  };

  _this.mjName = function () {
    return _this.constructor.tagName;
  };

  _this.mjContent = function () {
    var content = _this.mjml.get('content');

    if (content) {
      return (0, _trim2.default)(content);
    }

    return _react2.default.Children.map(_this.props.children, function (child) {
      if (typeof child === 'string') {
        return child;
      }
      return _server2.default.renderToStaticMarkup(child);
    });
  };

  _this.isInheritedAttributes = function (name) {
    return _this.mjml.get('inheritedAttributes') && _this.mjml.get('inheritedAttributes').includes(name);
  };

  _this.getWidth = function () {
    return _this.mjAttribute('rawPxWidth') || _this.mjAttribute('width');
  };

  _this.getParentWidth = function () {
    return _this.mjAttribute('parentWidth');
  };

  _this.renderWrappedOutlookChildren = function (children) {
    children = _react2.default.Children.toArray(children);

    var realChildren = children.filter(function (child) {
      return !child.props.mjml || child.props.mjml.get('tagName') !== 'mj-raw';
    });

    var prefix = _this.mjName() + '-outlook';
    var parentWidth = _this.getWidth();
    var siblings = realChildren.length;
    var elementsWidth = realChildren.map(function (element) {
      if (_this.isInheritedAttributes('width')) {
        return parseInt(parentWidth);
      }

      return getElementWidth({ element: element, siblings: siblings, parentWidth: parentWidth });
    });

    var wrappedElements = [];

    if (siblings == 0) {
      return wrappedElements;
    }

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-open', className: prefix + '-open', 'data-width':
elementsWidth[0] }));

    var i = 0;

    children.forEach(function (child) {
      var childProps = Object.assign({}, child.props);

      if (childProps.mjml) {
        childProps.mjml = childProps.mjml.setIn(['attributes', 'rawPxWidth'], elementsWidth[i]);

        if (_this.mjml.get('inheritedAttributes')) {
          childProps.mjml = childProps.mjml.mergeIn(['attributes', _this.inheritedAttributes()]);
        }
      } else {
        Object.assign(childProps, { rawPxWidth: elementsWidth[i] });

        if (_this.mjml.get('inheritedAttributes')) {
          Object.assign(childProps, _this.inheritedAttributes());
        }
      }

      var childWithProps = _react2.default.cloneElement(child, childProps);

      wrappedElements.push(childWithProps);
      if (!childWithProps.type.rawElement && i < realChildren.length - 1) {
        wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-' + i, className: prefix + '-line', 'data-width
': elementsWidth[++i] }));
      }
    });

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-close', className: prefix + '-close' }));

    return wrappedElements;
  };

  _this.paddingParser = function (direction) {
    var prefix = arguments.length > 1 && arguments[1] !== undefined ? arguments[1] : '';

    var paddingDirection = _this.mjAttribute(prefix + 'padding-' + direction);
    var padding = _this.mjAttribute(prefix + 'padding');

    if (paddingDirection != null) {
      return parseInt(paddingDirection);
    }

    if (!padding) {
      return 0;
    }

    var paddings = padding.split(' ');
    var directions = {};

    switch (paddings.length) {
      case 1:
        return parseInt(padding);
      case 2:
        directions = { top: 0, bottom: 0, left: 1, right: 1 };
        break;
      case 3:
        directions = { top: 0, left: 1, right: 1, bottom: 2 };
        break;
      case 4:
        directions = { top: 0, right: 1, bottom: 2, left: 3 };
        break;
    }

    return parseInt(paddings[directions[direction]] || 0);
  };

  _this.mjml = props.mjml || _immutable2. ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mjml.elements.mj-hero-content"></a>[function <span class="apidocSignatureSpan">mjml.</span>elements.mj-hero-content (props)](#apidoc.element.mjml.elements.mj-hero-content)
- description and source-code
```javascript
function MJMLElement(props) {
  _classCallCheck(this, MJMLElement);

  var _this = _possibleConstructorReturn(this, (MJMLElement.__proto__ || Object.getPrototypeOf(MJMLElement)).call(this, props));

  _this.mjAttribute = function (name) {
    return _this.mjml.getIn(['attributes', name]);
  };

  _this.mjName = function () {
    return _this.constructor.tagName;
  };

  _this.mjContent = function () {
    var content = _this.mjml.get('content');

    if (content) {
      return (0, _trim2.default)(content);
    }

    return _react2.default.Children.map(_this.props.children, function (child) {
      if (typeof child === 'string') {
        return child;
      }
      return _server2.default.renderToStaticMarkup(child);
    });
  };

  _this.isInheritedAttributes = function (name) {
    return _this.mjml.get('inheritedAttributes') && _this.mjml.get('inheritedAttributes').includes(name);
  };

  _this.getWidth = function () {
    return _this.mjAttribute('rawPxWidth') || _this.mjAttribute('width');
  };

  _this.getParentWidth = function () {
    return _this.mjAttribute('parentWidth');
  };

  _this.renderWrappedOutlookChildren = function (children) {
    children = _react2.default.Children.toArray(children);

    var realChildren = children.filter(function (child) {
      return !child.props.mjml || child.props.mjml.get('tagName') !== 'mj-raw';
    });

    var prefix = _this.mjName() + '-outlook';
    var parentWidth = _this.getWidth();
    var siblings = realChildren.length;
    var elementsWidth = realChildren.map(function (element) {
      if (_this.isInheritedAttributes('width')) {
        return parseInt(parentWidth);
      }

      return getElementWidth({ element: element, siblings: siblings, parentWidth: parentWidth });
    });

    var wrappedElements = [];

    if (siblings == 0) {
      return wrappedElements;
    }

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-open', className: prefix + '-open', 'data-width':
elementsWidth[0] }));

    var i = 0;

    children.forEach(function (child) {
      var childProps = Object.assign({}, child.props);

      if (childProps.mjml) {
        childProps.mjml = childProps.mjml.setIn(['attributes', 'rawPxWidth'], elementsWidth[i]);

        if (_this.mjml.get('inheritedAttributes')) {
          childProps.mjml = childProps.mjml.mergeIn(['attributes', _this.inheritedAttributes()]);
        }
      } else {
        Object.assign(childProps, { rawPxWidth: elementsWidth[i] });

        if (_this.mjml.get('inheritedAttributes')) {
          Object.assign(childProps, _this.inheritedAttributes());
        }
      }

      var childWithProps = _react2.default.cloneElement(child, childProps);

      wrappedElements.push(childWithProps);
      if (!childWithProps.type.rawElement && i < realChildren.length - 1) {
        wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-' + i, className: prefix + '-line', 'data-width
': elementsWidth[++i] }));
      }
    });

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-close', className: prefix + '-close' }));

    return wrappedElements;
  };

  _this.paddingParser = function (direction) {
    var prefix = arguments.length > 1 && arguments[1] !== undefined ? arguments[1] : '';

    var paddingDirection = _this.mjAttribute(prefix + 'padding-' + direction);
    var padding = _this.mjAttribute(prefix + 'padding');

    if (paddingDirection != null) {
      return parseInt(paddingDirection);
    }

    if (!padding) {
      return 0;
    }

    var paddings = padding.split(' ');
    var directions = {};

    switch (paddings.length) {
      case 1:
        return parseInt(padding);
      case 2:
        directions = { top: 0, bottom: 0, left: 1, right: 1 };
        break;
      case 3:
        directions = { top: 0, left: 1, right: 1, bottom: 2 };
        break;
      case 4:
        directions = { top: 0, right: 1, bottom: 2, left: 3 };
        break;
    }

    return parseInt(paddings[directions[direction]] || 0);
  };

  _this.mjml = props.mjml || _immutable2. ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mjml.elements.mj-inline-links"></a>[function <span class="apidocSignatureSpan">mjml.</span>elements.mj-inline-links (props)](#apidoc.element.mjml.elements.mj-inline-links)
- description and source-code
```javascript
function MJMLElement(props) {
  _classCallCheck(this, MJMLElement);

  var _this = _possibleConstructorReturn(this, (MJMLElement.__proto__ || Object.getPrototypeOf(MJMLElement)).call(this, props));

  _this.mjAttribute = function (name) {
    return _this.mjml.getIn(['attributes', name]);
  };

  _this.mjName = function () {
    return _this.constructor.tagName;
  };

  _this.mjContent = function () {
    var content = _this.mjml.get('content');

    if (content) {
      return (0, _trim2.default)(content);
    }

    return _react2.default.Children.map(_this.props.children, function (child) {
      if (typeof child === 'string') {
        return child;
      }
      return _server2.default.renderToStaticMarkup(child);
    });
  };

  _this.isInheritedAttributes = function (name) {
    return _this.mjml.get('inheritedAttributes') && _this.mjml.get('inheritedAttributes').includes(name);
  };

  _this.getWidth = function () {
    return _this.mjAttribute('rawPxWidth') || _this.mjAttribute('width');
  };

  _this.getParentWidth = function () {
    return _this.mjAttribute('parentWidth');
  };

  _this.renderWrappedOutlookChildren = function (children) {
    children = _react2.default.Children.toArray(children);

    var realChildren = children.filter(function (child) {
      return !child.props.mjml || child.props.mjml.get('tagName') !== 'mj-raw';
    });

    var prefix = _this.mjName() + '-outlook';
    var parentWidth = _this.getWidth();
    var siblings = realChildren.length;
    var elementsWidth = realChildren.map(function (element) {
      if (_this.isInheritedAttributes('width')) {
        return parseInt(parentWidth);
      }

      return getElementWidth({ element: element, siblings: siblings, parentWidth: parentWidth });
    });

    var wrappedElements = [];

    if (siblings == 0) {
      return wrappedElements;
    }

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-open', className: prefix + '-open', 'data-width':
elementsWidth[0] }));

    var i = 0;

    children.forEach(function (child) {
      var childProps = Object.assign({}, child.props);

      if (childProps.mjml) {
        childProps.mjml = childProps.mjml.setIn(['attributes', 'rawPxWidth'], elementsWidth[i]);

        if (_this.mjml.get('inheritedAttributes')) {
          childProps.mjml = childProps.mjml.mergeIn(['attributes', _this.inheritedAttributes()]);
        }
      } else {
        Object.assign(childProps, { rawPxWidth: elementsWidth[i] });

        if (_this.mjml.get('inheritedAttributes')) {
          Object.assign(childProps, _this.inheritedAttributes());
        }
      }

      var childWithProps = _react2.default.cloneElement(child, childProps);

      wrappedElements.push(childWithProps);
      if (!childWithProps.type.rawElement && i < realChildren.length - 1) {
        wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-' + i, className: prefix + '-line', 'data-width
': elementsWidth[++i] }));
      }
    });

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-close', className: prefix + '-close' }));

    return wrappedElements;
  };

  _this.paddingParser = function (direction) {
    var prefix = arguments.length > 1 && arguments[1] !== undefined ? arguments[1] : '';

    var paddingDirection = _this.mjAttribute(prefix + 'padding-' + direction);
    var padding = _this.mjAttribute(prefix + 'padding');

    if (paddingDirection != null) {
      return parseInt(paddingDirection);
    }

    if (!padding) {
      return 0;
    }

    var paddings = padding.split(' ');
    var directions = {};

    switch (paddings.length) {
      case 1:
        return parseInt(padding);
      case 2:
        directions = { top: 0, bottom: 0, left: 1, right: 1 };
        break;
      case 3:
        directions = { top: 0, left: 1, right: 1, bottom: 2 };
        break;
      case 4:
        directions = { top: 0, right: 1, bottom: 2, left: 3 };
        break;
    }

    return parseInt(paddings[directions[direction]] || 0);
  };

  _this.mjml = props.mjml || _immutable2. ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mjml.elements.mj-link"></a>[function <span class="apidocSignatureSpan">mjml.</span>elements.mj-link (props)](#apidoc.element.mjml.elements.mj-link)
- description and source-code
```javascript
function MJMLElement(props) {
  _classCallCheck(this, MJMLElement);

  var _this = _possibleConstructorReturn(this, (MJMLElement.__proto__ || Object.getPrototypeOf(MJMLElement)).call(this, props));

  _this.mjAttribute = function (name) {
    return _this.mjml.getIn(['attributes', name]);
  };

  _this.mjName = function () {
    return _this.constructor.tagName;
  };

  _this.mjContent = function () {
    var content = _this.mjml.get('content');

    if (content) {
      return (0, _trim2.default)(content);
    }

    return _react2.default.Children.map(_this.props.children, function (child) {
      if (typeof child === 'string') {
        return child;
      }
      return _server2.default.renderToStaticMarkup(child);
    });
  };

  _this.isInheritedAttributes = function (name) {
    return _this.mjml.get('inheritedAttributes') && _this.mjml.get('inheritedAttributes').includes(name);
  };

  _this.getWidth = function () {
    return _this.mjAttribute('rawPxWidth') || _this.mjAttribute('width');
  };

  _this.getParentWidth = function () {
    return _this.mjAttribute('parentWidth');
  };

  _this.renderWrappedOutlookChildren = function (children) {
    children = _react2.default.Children.toArray(children);

    var realChildren = children.filter(function (child) {
      return !child.props.mjml || child.props.mjml.get('tagName') !== 'mj-raw';
    });

    var prefix = _this.mjName() + '-outlook';
    var parentWidth = _this.getWidth();
    var siblings = realChildren.length;
    var elementsWidth = realChildren.map(function (element) {
      if (_this.isInheritedAttributes('width')) {
        return parseInt(parentWidth);
      }

      return getElementWidth({ element: element, siblings: siblings, parentWidth: parentWidth });
    });

    var wrappedElements = [];

    if (siblings == 0) {
      return wrappedElements;
    }

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-open', className: prefix + '-open', 'data-width':
elementsWidth[0] }));

    var i = 0;

    children.forEach(function (child) {
      var childProps = Object.assign({}, child.props);

      if (childProps.mjml) {
        childProps.mjml = childProps.mjml.setIn(['attributes', 'rawPxWidth'], elementsWidth[i]);

        if (_this.mjml.get('inheritedAttributes')) {
          childProps.mjml = childProps.mjml.mergeIn(['attributes', _this.inheritedAttributes()]);
        }
      } else {
        Object.assign(childProps, { rawPxWidth: elementsWidth[i] });

        if (_this.mjml.get('inheritedAttributes')) {
          Object.assign(childProps, _this.inheritedAttributes());
        }
      }

      var childWithProps = _react2.default.cloneElement(child, childProps);

      wrappedElements.push(childWithProps);
      if (!childWithProps.type.rawElement && i < realChildren.length - 1) {
        wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-' + i, className: prefix + '-line', 'data-width
': elementsWidth[++i] }));
      }
    });

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-close', className: prefix + '-close' }));

    return wrappedElements;
  };

  _this.paddingParser = function (direction) {
    var prefix = arguments.length > 1 && arguments[1] !== undefined ? arguments[1] : '';

    var paddingDirection = _this.mjAttribute(prefix + 'padding-' + direction);
    var padding = _this.mjAttribute(prefix + 'padding');

    if (paddingDirection != null) {
      return parseInt(paddingDirection);
    }

    if (!padding) {
      return 0;
    }

    var paddings = padding.split(' ');
    var directions = {};

    switch (paddings.length) {
      case 1:
        return parseInt(padding);
      case 2:
        directions = { top: 0, bottom: 0, left: 1, right: 1 };
        break;
      case 3:
        directions = { top: 0, left: 1, right: 1, bottom: 2 };
        break;
      case 4:
        directions = { top: 0, right: 1, bottom: 2, left: 3 };
        break;
    }

    return parseInt(paddings[directions[direction]] || 0);
  };

  _this.mjml = props.mjml || _immutable2. ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mjml.elements.mj-raw"></a>[function <span class="apidocSignatureSpan">mjml.</span>elements.mj-raw (props)](#apidoc.element.mjml.elements.mj-raw)
- description and source-code
```javascript
function MJMLElement(props) {
  _classCallCheck(this, MJMLElement);

  var _this = _possibleConstructorReturn(this, (MJMLElement.__proto__ || Object.getPrototypeOf(MJMLElement)).call(this, props));

  _this.mjAttribute = function (name) {
    return _this.mjml.getIn(['attributes', name]);
  };

  _this.mjName = function () {
    return _this.constructor.tagName;
  };

  _this.mjContent = function () {
    var content = _this.mjml.get('content');

    if (content) {
      return (0, _trim2.default)(content);
    }

    return _react2.default.Children.map(_this.props.children, function (child) {
      if (typeof child === 'string') {
        return child;
      }
      return _server2.default.renderToStaticMarkup(child);
    });
  };

  _this.isInheritedAttributes = function (name) {
    return _this.mjml.get('inheritedAttributes') && _this.mjml.get('inheritedAttributes').includes(name);
  };

  _this.getWidth = function () {
    return _this.mjAttribute('rawPxWidth') || _this.mjAttribute('width');
  };

  _this.getParentWidth = function () {
    return _this.mjAttribute('parentWidth');
  };

  _this.renderWrappedOutlookChildren = function (children) {
    children = _react2.default.Children.toArray(children);

    var realChildren = children.filter(function (child) {
      return !child.props.mjml || child.props.mjml.get('tagName') !== 'mj-raw';
    });

    var prefix = _this.mjName() + '-outlook';
    var parentWidth = _this.getWidth();
    var siblings = realChildren.length;
    var elementsWidth = realChildren.map(function (element) {
      if (_this.isInheritedAttributes('width')) {
        return parseInt(parentWidth);
      }

      return getElementWidth({ element: element, siblings: siblings, parentWidth: parentWidth });
    });

    var wrappedElements = [];

    if (siblings == 0) {
      return wrappedElements;
    }

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-open', className: prefix + '-open', 'data-width':
elementsWidth[0] }));

    var i = 0;

    children.forEach(function (child) {
      var childProps = Object.assign({}, child.props);

      if (childProps.mjml) {
        childProps.mjml = childProps.mjml.setIn(['attributes', 'rawPxWidth'], elementsWidth[i]);

        if (_this.mjml.get('inheritedAttributes')) {
          childProps.mjml = childProps.mjml.mergeIn(['attributes', _this.inheritedAttributes()]);
        }
      } else {
        Object.assign(childProps, { rawPxWidth: elementsWidth[i] });

        if (_this.mjml.get('inheritedAttributes')) {
          Object.assign(childProps, _this.inheritedAttributes());
        }
      }

      var childWithProps = _react2.default.cloneElement(child, childProps);

      wrappedElements.push(childWithProps);
      if (!childWithProps.type.rawElement && i < realChildren.length - 1) {
        wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-' + i, className: prefix + '-line', 'data-width
': elementsWidth[++i] }));
      }
    });

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-close', className: prefix + '-close' }));

    return wrappedElements;
  };

  _this.paddingParser = function (direction) {
    var prefix = arguments.length > 1 && arguments[1] !== undefined ? arguments[1] : '';

    var paddingDirection = _this.mjAttribute(prefix + 'padding-' + direction);
    var padding = _this.mjAttribute(prefix + 'padding');

    if (paddingDirection != null) {
      return parseInt(paddingDirection);
    }

    if (!padding) {
      return 0;
    }

    var paddings = padding.split(' ');
    var directions = {};

    switch (paddings.length) {
      case 1:
        return parseInt(padding);
      case 2:
        directions = { top: 0, bottom: 0, left: 1, right: 1 };
        break;
      case 3:
        directions = { top: 0, left: 1, right: 1, bottom: 2 };
        break;
      case 4:
        directions = { top: 0, right: 1, bottom: 2, left: 3 };
        break;
    }

    return parseInt(paddings[directions[direction]] || 0);
  };

  _this.mjml = props.mjml || _immutable2. ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mjml.elements.mj-section"></a>[function <span class="apidocSignatureSpan">mjml.</span>elements.mj-section (props)](#apidoc.element.mjml.elements.mj-section)
- description and source-code
```javascript
function MJMLElement(props) {
  _classCallCheck(this, MJMLElement);

  var _this = _possibleConstructorReturn(this, (MJMLElement.__proto__ || Object.getPrototypeOf(MJMLElement)).call(this, props));

  _this.mjAttribute = function (name) {
    return _this.mjml.getIn(['attributes', name]);
  };

  _this.mjName = function () {
    return _this.constructor.tagName;
  };

  _this.mjContent = function () {
    var content = _this.mjml.get('content');

    if (content) {
      return (0, _trim2.default)(content);
    }

    return _react2.default.Children.map(_this.props.children, function (child) {
      if (typeof child === 'string') {
        return child;
      }
      return _server2.default.renderToStaticMarkup(child);
    });
  };

  _this.isInheritedAttributes = function (name) {
    return _this.mjml.get('inheritedAttributes') && _this.mjml.get('inheritedAttributes').includes(name);
  };

  _this.getWidth = function () {
    return _this.mjAttribute('rawPxWidth') || _this.mjAttribute('width');
  };

  _this.getParentWidth = function () {
    return _this.mjAttribute('parentWidth');
  };

  _this.renderWrappedOutlookChildren = function (children) {
    children = _react2.default.Children.toArray(children);

    var realChildren = children.filter(function (child) {
      return !child.props.mjml || child.props.mjml.get('tagName') !== 'mj-raw';
    });

    var prefix = _this.mjName() + '-outlook';
    var parentWidth = _this.getWidth();
    var siblings = realChildren.length;
    var elementsWidth = realChildren.map(function (element) {
      if (_this.isInheritedAttributes('width')) {
        return parseInt(parentWidth);
      }

      return getElementWidth({ element: element, siblings: siblings, parentWidth: parentWidth });
    });

    var wrappedElements = [];

    if (siblings == 0) {
      return wrappedElements;
    }

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-open', className: prefix + '-open', 'data-width':
elementsWidth[0] }));

    var i = 0;

    children.forEach(function (child) {
      var childProps = Object.assign({}, child.props);

      if (childProps.mjml) {
        childProps.mjml = childProps.mjml.setIn(['attributes', 'rawPxWidth'], elementsWidth[i]);

        if (_this.mjml.get('inheritedAttributes')) {
          childProps.mjml = childProps.mjml.mergeIn(['attributes', _this.inheritedAttributes()]);
        }
      } else {
        Object.assign(childProps, { rawPxWidth: elementsWidth[i] });

        if (_this.mjml.get('inheritedAttributes')) {
          Object.assign(childProps, _this.inheritedAttributes());
        }
      }

      var childWithProps = _react2.default.cloneElement(child, childProps);

      wrappedElements.push(childWithProps);
      if (!childWithProps.type.rawElement && i < realChildren.length - 1) {
        wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-' + i, className: prefix + '-line', 'data-width
': elementsWidth[++i] }));
      }
    });

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-close', className: prefix + '-close' }));

    return wrappedElements;
  };

  _this.paddingParser = function (direction) {
    var prefix = arguments.length > 1 && arguments[1] !== undefined ? arguments[1] : '';

    var paddingDirection = _this.mjAttribute(prefix + 'padding-' + direction);
    var padding = _this.mjAttribute(prefix + 'padding');

    if (paddingDirection != null) {
      return parseInt(paddingDirection);
    }

    if (!padding) {
      return 0;
    }

    var paddings = padding.split(' ');
    var directions = {};

    switch (paddings.length) {
      case 1:
        return parseInt(padding);
      case 2:
        directions = { top: 0, bottom: 0, left: 1, right: 1 };
        break;
      case 3:
        directions = { top: 0, left: 1, right: 1, bottom: 2 };
        break;
      case 4:
        directions = { top: 0, right: 1, bottom: 2, left: 3 };
        break;
    }

    return parseInt(paddings[directions[direction]] || 0);
  };

  _this.mjml = props.mjml || _immutable2. ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mjml.elements.mj-social"></a>[function <span class="apidocSignatureSpan">mjml.</span>elements.mj-social (props)](#apidoc.element.mjml.elements.mj-social)
- description and source-code
```javascript
function MJMLElement(props) {
  _classCallCheck(this, MJMLElement);

  var _this = _possibleConstructorReturn(this, (MJMLElement.__proto__ || Object.getPrototypeOf(MJMLElement)).call(this, props));

  _this.mjAttribute = function (name) {
    return _this.mjml.getIn(['attributes', name]);
  };

  _this.mjName = function () {
    return _this.constructor.tagName;
  };

  _this.mjContent = function () {
    var content = _this.mjml.get('content');

    if (content) {
      return (0, _trim2.default)(content);
    }

    return _react2.default.Children.map(_this.props.children, function (child) {
      if (typeof child === 'string') {
        return child;
      }
      return _server2.default.renderToStaticMarkup(child);
    });
  };

  _this.isInheritedAttributes = function (name) {
    return _this.mjml.get('inheritedAttributes') && _this.mjml.get('inheritedAttributes').includes(name);
  };

  _this.getWidth = function () {
    return _this.mjAttribute('rawPxWidth') || _this.mjAttribute('width');
  };

  _this.getParentWidth = function () {
    return _this.mjAttribute('parentWidth');
  };

  _this.renderWrappedOutlookChildren = function (children) {
    children = _react2.default.Children.toArray(children);

    var realChildren = children.filter(function (child) {
      return !child.props.mjml || child.props.mjml.get('tagName') !== 'mj-raw';
    });

    var prefix = _this.mjName() + '-outlook';
    var parentWidth = _this.getWidth();
    var siblings = realChildren.length;
    var elementsWidth = realChildren.map(function (element) {
      if (_this.isInheritedAttributes('width')) {
        return parseInt(parentWidth);
      }

      return getElementWidth({ element: element, siblings: siblings, parentWidth: parentWidth });
    });

    var wrappedElements = [];

    if (siblings == 0) {
      return wrappedElements;
    }

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-open', className: prefix + '-open', 'data-width':
elementsWidth[0] }));

    var i = 0;

    children.forEach(function (child) {
      var childProps = Object.assign({}, child.props);

      if (childProps.mjml) {
        childProps.mjml = childProps.mjml.setIn(['attributes', 'rawPxWidth'], elementsWidth[i]);

        if (_this.mjml.get('inheritedAttributes')) {
          childProps.mjml = childProps.mjml.mergeIn(['attributes', _this.inheritedAttributes()]);
        }
      } else {
        Object.assign(childProps, { rawPxWidth: elementsWidth[i] });

        if (_this.mjml.get('inheritedAttributes')) {
          Object.assign(childProps, _this.inheritedAttributes());
        }
      }

      var childWithProps = _react2.default.cloneElement(child, childProps);

      wrappedElements.push(childWithProps);
      if (!childWithProps.type.rawElement && i < realChildren.length - 1) {
        wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-' + i, className: prefix + '-line', 'data-width
': elementsWidth[++i] }));
      }
    });

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-close', className: prefix + '-close' }));

    return wrappedElements;
  };

  _this.paddingParser = function (direction) {
    var prefix = arguments.length > 1 && arguments[1] !== undefined ? arguments[1] : '';

    var paddingDirection = _this.mjAttribute(prefix + 'padding-' + direction);
    var padding = _this.mjAttribute(prefix + 'padding');

    if (paddingDirection != null) {
      return parseInt(paddingDirection);
    }

    if (!padding) {
      return 0;
    }

    var paddings = padding.split(' ');
    var directions = {};

    switch (paddings.length) {
      case 1:
        return parseInt(padding);
      case 2:
        directions = { top: 0, bottom: 0, left: 1, right: 1 };
        break;
      case 3:
        directions = { top: 0, left: 1, right: 1, bottom: 2 };
        break;
      case 4:
        directions = { top: 0, right: 1, bottom: 2, left: 3 };
        break;
    }

    return parseInt(paddings[directions[direction]] || 0);
  };

  _this.mjml = props.mjml || _immutable2. ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mjml.elements.mj-text"></a>[function <span class="apidocSignatureSpan">mjml.</span>elements.mj-text (props)](#apidoc.element.mjml.elements.mj-text)
- description and source-code
```javascript
function MJMLElement(props) {
  _classCallCheck(this, MJMLElement);

  var _this = _possibleConstructorReturn(this, (MJMLElement.__proto__ || Object.getPrototypeOf(MJMLElement)).call(this, props));

  _this.mjAttribute = function (name) {
    return _this.mjml.getIn(['attributes', name]);
  };

  _this.mjName = function () {
    return _this.constructor.tagName;
  };

  _this.mjContent = function () {
    var content = _this.mjml.get('content');

    if (content) {
      return (0, _trim2.default)(content);
    }

    return _react2.default.Children.map(_this.props.children, function (child) {
      if (typeof child === 'string') {
        return child;
      }
      return _server2.default.renderToStaticMarkup(child);
    });
  };

  _this.isInheritedAttributes = function (name) {
    return _this.mjml.get('inheritedAttributes') && _this.mjml.get('inheritedAttributes').includes(name);
  };

  _this.getWidth = function () {
    return _this.mjAttribute('rawPxWidth') || _this.mjAttribute('width');
  };

  _this.getParentWidth = function () {
    return _this.mjAttribute('parentWidth');
  };

  _this.renderWrappedOutlookChildren = function (children) {
    children = _react2.default.Children.toArray(children);

    var realChildren = children.filter(function (child) {
      return !child.props.mjml || child.props.mjml.get('tagName') !== 'mj-raw';
    });

    var prefix = _this.mjName() + '-outlook';
    var parentWidth = _this.getWidth();
    var siblings = realChildren.length;
    var elementsWidth = realChildren.map(function (element) {
      if (_this.isInheritedAttributes('width')) {
        return parseInt(parentWidth);
      }

      return getElementWidth({ element: element, siblings: siblings, parentWidth: parentWidth });
    });

    var wrappedElements = [];

    if (siblings == 0) {
      return wrappedElements;
    }

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-open', className: prefix + '-open', 'data-width':
elementsWidth[0] }));

    var i = 0;

    children.forEach(function (child) {
      var childProps = Object.assign({}, child.props);

      if (childProps.mjml) {
        childProps.mjml = childProps.mjml.setIn(['attributes', 'rawPxWidth'], elementsWidth[i]);

        if (_this.mjml.get('inheritedAttributes')) {
          childProps.mjml = childProps.mjml.mergeIn(['attributes', _this.inheritedAttributes()]);
        }
      } else {
        Object.assign(childProps, { rawPxWidth: elementsWidth[i] });

        if (_this.mjml.get('inheritedAttributes')) {
          Object.assign(childProps, _this.inheritedAttributes());
        }
      }

      var childWithProps = _react2.default.cloneElement(child, childProps);

      wrappedElements.push(childWithProps);
      if (!childWithProps.type.rawElement && i < realChildren.length - 1) {
        wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-' + i, className: prefix + '-line', 'data-width
': elementsWidth[++i] }));
      }
    });

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-close', className: prefix + '-close' }));

    return wrappedElements;
  };

  _this.paddingParser = function (direction) {
    var prefix = arguments.length > 1 && arguments[1] !== undefined ? arguments[1] : '';

    var paddingDirection = _this.mjAttribute(prefix + 'padding-' + direction);
    var padding = _this.mjAttribute(prefix + 'padding');

    if (paddingDirection != null) {
      return parseInt(paddingDirection);
    }

    if (!padding) {
      return 0;
    }

    var paddings = padding.split(' ');
    var directions = {};

    switch (paddings.length) {
      case 1:
        return parseInt(padding);
      case 2:
        directions = { top: 0, bottom: 0, left: 1, right: 1 };
        break;
      case 3:
        directions = { top: 0, left: 1, right: 1, bottom: 2 };
        break;
      case 4:
        directions = { top: 0, right: 1, bottom: 2, left: 3 };
        break;
    }

    return parseInt(paddings[directions[direction]] || 0);
  };

  _this.mjml = props.mjml || _immutable2. ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mjml.elements.mj-wrapper"></a>[function <span class="apidocSignatureSpan">mjml.</span>elements.mj-wrapper ()](#apidoc.element.mjml.elements.mj-wrapper)
- description and source-code
```javascript
function Wrapper() {
  _classCallCheck(this, Wrapper);

  return _possibleConstructorReturn(this, (Wrapper.__proto__ || Object.getPrototypeOf(Wrapper)).apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mjml.formatValidationError"></a>[function <span class="apidocSignatureSpan">mjml.</span>formatValidationError (message, element)](#apidoc.element.mjml.formatValidationError)
- description and source-code
```javascript
formatValidationError = function (message, element) {
  var line = element.lineNumber,
      tagName = element.tagName;


  return {
    line: line,
    message: message,
    tagName: tagName,
    formattedMessage: "Line " + line + " (" + tagName + ") \u2014 " + message
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mjml.mjml2html"></a>[function <span class="apidocSignatureSpan">mjml.</span>mjml2html (mjml)](#apidoc.element.mjml.mjml2html)
- description and source-code
```javascript
function mjml2html(mjml) {
  var options = arguments.length > 1 && arguments[1] !== undefined ? arguments[1] : {};
  return new _MJMLRenderer2.default(mjml, options).render();
}
```
- example usage
```shell
...
      </mj-section>
    </mj-container>
  </mj-body>
</mjml>
'

try {
  const { html, errors } = mjml.mjml2html(inputMJML, { beautify: true, minify: false, level: "soft" })

  if (errors) {
    console.log(errors.map(e => e.formattedMessage).join('\n'))
  }

  console.log(html)
} catch(e) {
...
```

#### <a name="apidoc.element.mjml.registerMJElement"></a>[function <span class="apidocSignatureSpan">mjml.</span>registerMJElement (Component)](#apidoc.element.mjml.registerMJElement)
- description and source-code
```javascript
function registerMJElement(Component) {
  var endingTag = Component.endingTag,
      postRender = Component.postRender,
      tagName = Component.tagName;


  if (!tagName) {
    return (0, _warning2.default)(false, 'Component has no tagName');
  }

  endingTag && !(0, _lodash.includes)(endingTags, tagName) && endingTags.push(tagName);
  postRender && postRenders.push(postRender);

  MJMLElementsCollection[tagName] = Component;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mjml.registerMJHeadElement"></a>[function <span class="apidocSignatureSpan">mjml.</span>registerMJHeadElement ()](#apidoc.element.mjml.registerMJHeadElement)
- description and source-code
```javascript
function registerMJHeadElement() {
  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  var name = void 0,
      endingTag = void 0,
      handler = void 0; // eslint-disable-line

  if (args.length > 1) {
    name = args[0];
    handler = args[1];
    endingTag = args[2];
  } else {
    var _args$ = args[0];
    name = _args$.name;
    handler = _args$.handler;
    endingTag = _args$.endingTag;
  }

  endingTag && !(0, _lodash.includes)(endingTags, name) && endingTags.push(name);

  MJMLHeadElementsCollection[name] = handler;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mjml.registerMJRule"></a>[function <span class="apidocSignatureSpan">mjml.</span>registerMJRule (rule, name)](#apidoc.element.mjml.registerMJRule)
- description and source-code
```javascript
function registerMJRule(rule, name) {

  if (typeof rule != 'function' || rule.length !== 1) {
    return (0, _warning2.default)(false, 'Your rule must be a function and must have one parameter which is the element to validate
');
  }

  if (name) {
    MJMLRulesCollection[name] = rule;
  } else {
    MJMLRulesCollection[rule.name] = rule;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mjml.version"></a>[function <span class="apidocSignatureSpan">mjml.</span>version ()](#apidoc.element.mjml.version)
- description and source-code
```javascript
function version() {
  return '3.3.0';
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mjml.MJMLHeadElements"></a>[module mjml.MJMLHeadElements](#apidoc.module.mjml.MJMLHeadElements)

#### <a name="apidoc.element.mjml.MJMLHeadElements.mj-attributes"></a>[function <span class="apidocSignatureSpan">mjml.MJMLHeadElements.</span>mj-attributes (element, globalAttributes)](#apidoc.element.mjml.MJMLHeadElements.mj-attributes)
- description and source-code
```javascript
function handler(element, globalAttributes) {
  (0, _each2.default)(element.children, function (_ref) {
    var attributes = _ref.attributes,
        tagName = _ref.tagName;

    if (tagName === 'mj-class') {
      return globalAttributes.cssClasses[attributes.name] = (0, _assign2.default)(globalAttributes.cssClasses[attributes.name], (
0, _omit2.default)(attributes, ['name']));
    }

    globalAttributes.defaultAttributes[tagName] = (0, _assign2.default)(globalAttributes.defaultAttributes[tagName], attributes);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mjml.MJMLHeadElements.mj-font"></a>[function <span class="apidocSignatureSpan">mjml.MJMLHeadElements.</span>mj-font (_ref, globalAttributes)](#apidoc.element.mjml.MJMLHeadElements.mj-font)
- description and source-code
```javascript
function handler(_ref, globalAttributes) {
  var attributes = _ref.attributes;

  var font = (0, _find2.default)(globalAttributes.fonts, ['name', attributes.name]);

  if (font) {
    font.url = attributes.href;
  } else {
    globalAttributes.fonts.push({ name: attributes.name, url: attributes.href });
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mjml.MJMLHeadElements.mj-style"></a>[function <span class="apidocSignatureSpan">mjml.MJMLHeadElements.</span>mj-style (_ref, globalAttributes)](#apidoc.element.mjml.MJMLHeadElements.mj-style)
- description and source-code
```javascript
function handler(_ref, globalAttributes) {
  var content = _ref.content,
      attributes = _ref.attributes;

  if (attributes.inline == "inline") {
    globalAttributes.inlineCSS.push(content);
  } else {
    globalAttributes.css.push(content);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mjml.MJMLHeadElements.mj-title"></a>[function <span class="apidocSignatureSpan">mjml.MJMLHeadElements.</span>mj-title (_ref, globalAttributes)](#apidoc.element.mjml.MJMLHeadElements.mj-title)
- description and source-code
```javascript
function handler(_ref, globalAttributes) {
  var content = _ref.content;

  globalAttributes.title = content;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mjml.elements"></a>[module mjml.elements](#apidoc.module.mjml.elements)

#### <a name="apidoc.element.mjml.elements.mj-accordion"></a>[function <span class="apidocSignatureSpan">mjml.elements.</span>mj-accordion (props)](#apidoc.element.mjml.elements.mj-accordion)
- description and source-code
```javascript
function MJMLElement(props) {
  _classCallCheck(this, MJMLElement);

  var _this = _possibleConstructorReturn(this, (MJMLElement.__proto__ || Object.getPrototypeOf(MJMLElement)).call(this, props));

  _this.mjAttribute = function (name) {
    return _this.mjml.getIn(['attributes', name]);
  };

  _this.mjName = function () {
    return _this.constructor.tagName;
  };

  _this.mjContent = function () {
    var content = _this.mjml.get('content');

    if (content) {
      return (0, _trim2.default)(content);
    }

    return _react2.default.Children.map(_this.props.children, function (child) {
      if (typeof child === 'string') {
        return child;
      }
      return _server2.default.renderToStaticMarkup(child);
    });
  };

  _this.isInheritedAttributes = function (name) {
    return _this.mjml.get('inheritedAttributes') && _this.mjml.get('inheritedAttributes').includes(name);
  };

  _this.getWidth = function () {
    return _this.mjAttribute('rawPxWidth') || _this.mjAttribute('width');
  };

  _this.getParentWidth = function () {
    return _this.mjAttribute('parentWidth');
  };

  _this.renderWrappedOutlookChildren = function (children) {
    children = _react2.default.Children.toArray(children);

    var realChildren = children.filter(function (child) {
      return !child.props.mjml || child.props.mjml.get('tagName') !== 'mj-raw';
    });

    var prefix = _this.mjName() + '-outlook';
    var parentWidth = _this.getWidth();
    var siblings = realChildren.length;
    var elementsWidth = realChildren.map(function (element) {
      if (_this.isInheritedAttributes('width')) {
        return parseInt(parentWidth);
      }

      return getElementWidth({ element: element, siblings: siblings, parentWidth: parentWidth });
    });

    var wrappedElements = [];

    if (siblings == 0) {
      return wrappedElements;
    }

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-open', className: prefix + '-open', 'data-width':
elementsWidth[0] }));

    var i = 0;

    children.forEach(function (child) {
      var childProps = Object.assign({}, child.props);

      if (childProps.mjml) {
        childProps.mjml = childProps.mjml.setIn(['attributes', 'rawPxWidth'], elementsWidth[i]);

        if (_this.mjml.get('inheritedAttributes')) {
          childProps.mjml = childProps.mjml.mergeIn(['attributes', _this.inheritedAttributes()]);
        }
      } else {
        Object.assign(childProps, { rawPxWidth: elementsWidth[i] });

        if (_this.mjml.get('inheritedAttributes')) {
          Object.assign(childProps, _this.inheritedAttributes());
        }
      }

      var childWithProps = _react2.default.cloneElement(child, childProps);

      wrappedElements.push(childWithProps);
      if (!childWithProps.type.rawElement && i < realChildren.length - 1) {
        wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-' + i, className: prefix + '-line', 'data-width
': elementsWidth[++i] }));
      }
    });

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-close', className: prefix + '-close' }));

    return wrappedElements;
  };

  _this.paddingParser = function (direction) {
    var prefix = arguments.length > 1 && arguments[1] !== undefined ? arguments[1] : '';

    var paddingDirection = _this.mjAttribute(prefix + 'padding-' + direction);
    var padding = _this.mjAttribute(prefix + 'padding');

    if (paddingDirection != null) {
      return parseInt(paddingDirection);
    }

    if (!padding) {
      return 0;
    }

    var paddings = padding.split(' ');
    var directions = {};

    switch (paddings.length) {
      case 1:
        return parseInt(padding);
      case 2:
        directions = { top: 0, bottom: 0, left: 1, right: 1 };
        break;
      case 3:
        directions = { top: 0, left: 1, right: 1, bottom: 2 };
        break;
      case 4:
        directions = { top: 0, right: 1, bottom: 2, left: 3 };
        break;
    }

    return parseInt(paddings[directions[direction]] || 0);
  };

  _this.mjml = props.mjml || _immutable2. ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mjml.elements.mj-accordion-element"></a>[function <span class="apidocSignatureSpan">mjml.elements.</span>mj-accordion-element (props)](#apidoc.element.mjml.elements.mj-accordion-element)
- description and source-code
```javascript
function MJMLElement(props) {
  _classCallCheck(this, MJMLElement);

  var _this = _possibleConstructorReturn(this, (MJMLElement.__proto__ || Object.getPrototypeOf(MJMLElement)).call(this, props));

  _this.mjAttribute = function (name) {
    return _this.mjml.getIn(['attributes', name]);
  };

  _this.mjName = function () {
    return _this.constructor.tagName;
  };

  _this.mjContent = function () {
    var content = _this.mjml.get('content');

    if (content) {
      return (0, _trim2.default)(content);
    }

    return _react2.default.Children.map(_this.props.children, function (child) {
      if (typeof child === 'string') {
        return child;
      }
      return _server2.default.renderToStaticMarkup(child);
    });
  };

  _this.isInheritedAttributes = function (name) {
    return _this.mjml.get('inheritedAttributes') && _this.mjml.get('inheritedAttributes').includes(name);
  };

  _this.getWidth = function () {
    return _this.mjAttribute('rawPxWidth') || _this.mjAttribute('width');
  };

  _this.getParentWidth = function () {
    return _this.mjAttribute('parentWidth');
  };

  _this.renderWrappedOutlookChildren = function (children) {
    children = _react2.default.Children.toArray(children);

    var realChildren = children.filter(function (child) {
      return !child.props.mjml || child.props.mjml.get('tagName') !== 'mj-raw';
    });

    var prefix = _this.mjName() + '-outlook';
    var parentWidth = _this.getWidth();
    var siblings = realChildren.length;
    var elementsWidth = realChildren.map(function (element) {
      if (_this.isInheritedAttributes('width')) {
        return parseInt(parentWidth);
      }

      return getElementWidth({ element: element, siblings: siblings, parentWidth: parentWidth });
    });

    var wrappedElements = [];

    if (siblings == 0) {
      return wrappedElements;
    }

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-open', className: prefix + '-open', 'data-width':
elementsWidth[0] }));

    var i = 0;

    children.forEach(function (child) {
      var childProps = Object.assign({}, child.props);

      if (childProps.mjml) {
        childProps.mjml = childProps.mjml.setIn(['attributes', 'rawPxWidth'], elementsWidth[i]);

        if (_this.mjml.get('inheritedAttributes')) {
          childProps.mjml = childProps.mjml.mergeIn(['attributes', _this.inheritedAttributes()]);
        }
      } else {
        Object.assign(childProps, { rawPxWidth: elementsWidth[i] });

        if (_this.mjml.get('inheritedAttributes')) {
          Object.assign(childProps, _this.inheritedAttributes());
        }
      }

      var childWithProps = _react2.default.cloneElement(child, childProps);

      wrappedElements.push(childWithProps);
      if (!childWithProps.type.rawElement && i < realChildren.length - 1) {
        wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-' + i, className: prefix + '-line', 'data-width
': elementsWidth[++i] }));
      }
    });

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-close', className: prefix + '-close' }));

    return wrappedElements;
  };

  _this.paddingParser = function (direction) {
    var prefix = arguments.length > 1 && arguments[1] !== undefined ? arguments[1] : '';

    var paddingDirection = _this.mjAttribute(prefix + 'padding-' + direction);
    var padding = _this.mjAttribute(prefix + 'padding');

    if (paddingDirection != null) {
      return parseInt(paddingDirection);
    }

    if (!padding) {
      return 0;
    }

    var paddings = padding.split(' ');
    var directions = {};

    switch (paddings.length) {
      case 1:
        return parseInt(padding);
      case 2:
        directions = { top: 0, bottom: 0, left: 1, right: 1 };
        break;
      case 3:
        directions = { top: 0, left: 1, right: 1, bottom: 2 };
        break;
      case 4:
        directions = { top: 0, right: 1, bottom: 2, left: 3 };
        break;
    }

    return parseInt(paddings[directions[direction]] || 0);
  };

  _this.mjml = props.mjml || _immutable2. ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mjml.elements.mj-accordion-text"></a>[function <span class="apidocSignatureSpan">mjml.elements.</span>mj-accordion-text (props)](#apidoc.element.mjml.elements.mj-accordion-text)
- description and source-code
```javascript
function MJMLElement(props) {
  _classCallCheck(this, MJMLElement);

  var _this = _possibleConstructorReturn(this, (MJMLElement.__proto__ || Object.getPrototypeOf(MJMLElement)).call(this, props));

  _this.mjAttribute = function (name) {
    return _this.mjml.getIn(['attributes', name]);
  };

  _this.mjName = function () {
    return _this.constructor.tagName;
  };

  _this.mjContent = function () {
    var content = _this.mjml.get('content');

    if (content) {
      return (0, _trim2.default)(content);
    }

    return _react2.default.Children.map(_this.props.children, function (child) {
      if (typeof child === 'string') {
        return child;
      }
      return _server2.default.renderToStaticMarkup(child);
    });
  };

  _this.isInheritedAttributes = function (name) {
    return _this.mjml.get('inheritedAttributes') && _this.mjml.get('inheritedAttributes').includes(name);
  };

  _this.getWidth = function () {
    return _this.mjAttribute('rawPxWidth') || _this.mjAttribute('width');
  };

  _this.getParentWidth = function () {
    return _this.mjAttribute('parentWidth');
  };

  _this.renderWrappedOutlookChildren = function (children) {
    children = _react2.default.Children.toArray(children);

    var realChildren = children.filter(function (child) {
      return !child.props.mjml || child.props.mjml.get('tagName') !== 'mj-raw';
    });

    var prefix = _this.mjName() + '-outlook';
    var parentWidth = _this.getWidth();
    var siblings = realChildren.length;
    var elementsWidth = realChildren.map(function (element) {
      if (_this.isInheritedAttributes('width')) {
        return parseInt(parentWidth);
      }

      return getElementWidth({ element: element, siblings: siblings, parentWidth: parentWidth });
    });

    var wrappedElements = [];

    if (siblings == 0) {
      return wrappedElements;
    }

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-open', className: prefix + '-open', 'data-width':
elementsWidth[0] }));

    var i = 0;

    children.forEach(function (child) {
      var childProps = Object.assign({}, child.props);

      if (childProps.mjml) {
        childProps.mjml = childProps.mjml.setIn(['attributes', 'rawPxWidth'], elementsWidth[i]);

        if (_this.mjml.get('inheritedAttributes')) {
          childProps.mjml = childProps.mjml.mergeIn(['attributes', _this.inheritedAttributes()]);
        }
      } else {
        Object.assign(childProps, { rawPxWidth: elementsWidth[i] });

        if (_this.mjml.get('inheritedAttributes')) {
          Object.assign(childProps, _this.inheritedAttributes());
        }
      }

      var childWithProps = _react2.default.cloneElement(child, childProps);

      wrappedElements.push(childWithProps);
      if (!childWithProps.type.rawElement && i < realChildren.length - 1) {
        wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-' + i, className: prefix + '-line', 'data-width
': elementsWidth[++i] }));
      }
    });

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-close', className: prefix + '-close' }));

    return wrappedElements;
  };

  _this.paddingParser = function (direction) {
    var prefix = arguments.length > 1 && arguments[1] !== undefined ? arguments[1] : '';

    var paddingDirection = _this.mjAttribute(prefix + 'padding-' + direction);
    var padding = _this.mjAttribute(prefix + 'padding');

    if (paddingDirection != null) {
      return parseInt(paddingDirection);
    }

    if (!padding) {
      return 0;
    }

    var paddings = padding.split(' ');
    var directions = {};

    switch (paddings.length) {
      case 1:
        return parseInt(padding);
      case 2:
        directions = { top: 0, bottom: 0, left: 1, right: 1 };
        break;
      case 3:
        directions = { top: 0, left: 1, right: 1, bottom: 2 };
        break;
      case 4:
        directions = { top: 0, right: 1, bottom: 2, left: 3 };
        break;
    }

    return parseInt(paddings[directions[direction]] || 0);
  };

  _this.mjml = props.mjml || _immutable2. ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mjml.elements.mj-accordion-title"></a>[function <span class="apidocSignatureSpan">mjml.elements.</span>mj-accordion-title (props)](#apidoc.element.mjml.elements.mj-accordion-title)
- description and source-code
```javascript
function MJMLElement(props) {
  _classCallCheck(this, MJMLElement);

  var _this = _possibleConstructorReturn(this, (MJMLElement.__proto__ || Object.getPrototypeOf(MJMLElement)).call(this, props));

  _this.mjAttribute = function (name) {
    return _this.mjml.getIn(['attributes', name]);
  };

  _this.mjName = function () {
    return _this.constructor.tagName;
  };

  _this.mjContent = function () {
    var content = _this.mjml.get('content');

    if (content) {
      return (0, _trim2.default)(content);
    }

    return _react2.default.Children.map(_this.props.children, function (child) {
      if (typeof child === 'string') {
        return child;
      }
      return _server2.default.renderToStaticMarkup(child);
    });
  };

  _this.isInheritedAttributes = function (name) {
    return _this.mjml.get('inheritedAttributes') && _this.mjml.get('inheritedAttributes').includes(name);
  };

  _this.getWidth = function () {
    return _this.mjAttribute('rawPxWidth') || _this.mjAttribute('width');
  };

  _this.getParentWidth = function () {
    return _this.mjAttribute('parentWidth');
  };

  _this.renderWrappedOutlookChildren = function (children) {
    children = _react2.default.Children.toArray(children);

    var realChildren = children.filter(function (child) {
      return !child.props.mjml || child.props.mjml.get('tagName') !== 'mj-raw';
    });

    var prefix = _this.mjName() + '-outlook';
    var parentWidth = _this.getWidth();
    var siblings = realChildren.length;
    var elementsWidth = realChildren.map(function (element) {
      if (_this.isInheritedAttributes('width')) {
        return parseInt(parentWidth);
      }

      return getElementWidth({ element: element, siblings: siblings, parentWidth: parentWidth });
    });

    var wrappedElements = [];

    if (siblings == 0) {
      return wrappedElements;
    }

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-open', className: prefix + '-open', 'data-width':
elementsWidth[0] }));

    var i = 0;

    children.forEach(function (child) {
      var childProps = Object.assign({}, child.props);

      if (childProps.mjml) {
        childProps.mjml = childProps.mjml.setIn(['attributes', 'rawPxWidth'], elementsWidth[i]);

        if (_this.mjml.get('inheritedAttributes')) {
          childProps.mjml = childProps.mjml.mergeIn(['attributes', _this.inheritedAttributes()]);
        }
      } else {
        Object.assign(childProps, { rawPxWidth: elementsWidth[i] });

        if (_this.mjml.get('inheritedAttributes')) {
          Object.assign(childProps, _this.inheritedAttributes());
        }
      }

      var childWithProps = _react2.default.cloneElement(child, childProps);

      wrappedElements.push(childWithProps);
      if (!childWithProps.type.rawElement && i < realChildren.length - 1) {
        wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-' + i, className: prefix + '-line', 'data-width
': elementsWidth[++i] }));
      }
    });

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-close', className: prefix + '-close' }));

    return wrappedElements;
  };

  _this.paddingParser = function (direction) {
    var prefix = arguments.length > 1 && arguments[1] !== undefined ? arguments[1] : '';

    var paddingDirection = _this.mjAttribute(prefix + 'padding-' + direction);
    var padding = _this.mjAttribute(prefix + 'padding');

    if (paddingDirection != null) {
      return parseInt(paddingDirection);
    }

    if (!padding) {
      return 0;
    }

    var paddings = padding.split(' ');
    var directions = {};

    switch (paddings.length) {
      case 1:
        return parseInt(padding);
      case 2:
        directions = { top: 0, bottom: 0, left: 1, right: 1 };
        break;
      case 3:
        directions = { top: 0, left: 1, right: 1, bottom: 2 };
        break;
      case 4:
        directions = { top: 0, right: 1, bottom: 2, left: 3 };
        break;
    }

    return parseInt(paddings[directions[direction]] || 0);
  };

  _this.mjml = props.mjml || _immutable2. ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mjml.elements.mj-button"></a>[function <span class="apidocSignatureSpan">mjml.elements.</span>mj-button (props)](#apidoc.element.mjml.elements.mj-button)
- description and source-code
```javascript
function MJMLElement(props) {
  _classCallCheck(this, MJMLElement);

  var _this = _possibleConstructorReturn(this, (MJMLElement.__proto__ || Object.getPrototypeOf(MJMLElement)).call(this, props));

  _this.mjAttribute = function (name) {
    return _this.mjml.getIn(['attributes', name]);
  };

  _this.mjName = function () {
    return _this.constructor.tagName;
  };

  _this.mjContent = function () {
    var content = _this.mjml.get('content');

    if (content) {
      return (0, _trim2.default)(content);
    }

    return _react2.default.Children.map(_this.props.children, function (child) {
      if (typeof child === 'string') {
        return child;
      }
      return _server2.default.renderToStaticMarkup(child);
    });
  };

  _this.isInheritedAttributes = function (name) {
    return _this.mjml.get('inheritedAttributes') && _this.mjml.get('inheritedAttributes').includes(name);
  };

  _this.getWidth = function () {
    return _this.mjAttribute('rawPxWidth') || _this.mjAttribute('width');
  };

  _this.getParentWidth = function () {
    return _this.mjAttribute('parentWidth');
  };

  _this.renderWrappedOutlookChildren = function (children) {
    children = _react2.default.Children.toArray(children);

    var realChildren = children.filter(function (child) {
      return !child.props.mjml || child.props.mjml.get('tagName') !== 'mj-raw';
    });

    var prefix = _this.mjName() + '-outlook';
    var parentWidth = _this.getWidth();
    var siblings = realChildren.length;
    var elementsWidth = realChildren.map(function (element) {
      if (_this.isInheritedAttributes('width')) {
        return parseInt(parentWidth);
      }

      return getElementWidth({ element: element, siblings: siblings, parentWidth: parentWidth });
    });

    var wrappedElements = [];

    if (siblings == 0) {
      return wrappedElements;
    }

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-open', className: prefix + '-open', 'data-width':
elementsWidth[0] }));

    var i = 0;

    children.forEach(function (child) {
      var childProps = Object.assign({}, child.props);

      if (childProps.mjml) {
        childProps.mjml = childProps.mjml.setIn(['attributes', 'rawPxWidth'], elementsWidth[i]);

        if (_this.mjml.get('inheritedAttributes')) {
          childProps.mjml = childProps.mjml.mergeIn(['attributes', _this.inheritedAttributes()]);
        }
      } else {
        Object.assign(childProps, { rawPxWidth: elementsWidth[i] });

        if (_this.mjml.get('inheritedAttributes')) {
          Object.assign(childProps, _this.inheritedAttributes());
        }
      }

      var childWithProps = _react2.default.cloneElement(child, childProps);

      wrappedElements.push(childWithProps);
      if (!childWithProps.type.rawElement && i < realChildren.length - 1) {
        wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-' + i, className: prefix + '-line', 'data-width
': elementsWidth[++i] }));
      }
    });

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-close', className: prefix + '-close' }));

    return wrappedElements;
  };

  _this.paddingParser = function (direction) {
    var prefix = arguments.length > 1 && arguments[1] !== undefined ? arguments[1] : '';

    var paddingDirection = _this.mjAttribute(prefix + 'padding-' + direction);
    var padding = _this.mjAttribute(prefix + 'padding');

    if (paddingDirection != null) {
      return parseInt(paddingDirection);
    }

    if (!padding) {
      return 0;
    }

    var paddings = padding.split(' ');
    var directions = {};

    switch (paddings.length) {
      case 1:
        return parseInt(padding);
      case 2:
        directions = { top: 0, bottom: 0, left: 1, right: 1 };
        break;
      case 3:
        directions = { top: 0, left: 1, right: 1, bottom: 2 };
        break;
      case 4:
        directions = { top: 0, right: 1, bottom: 2, left: 3 };
        break;
    }

    return parseInt(paddings[directions[direction]] || 0);
  };

  _this.mjml = props.mjml || _immutable2. ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mjml.elements.mj-carousel"></a>[function <span class="apidocSignatureSpan">mjml.elements.</span>mj-carousel (props)](#apidoc.element.mjml.elements.mj-carousel)
- description and source-code
```javascript
function MJMLElement(props) {
  _classCallCheck(this, MJMLElement);

  var _this = _possibleConstructorReturn(this, (MJMLElement.__proto__ || Object.getPrototypeOf(MJMLElement)).call(this, props));

  _this.mjAttribute = function (name) {
    return _this.mjml.getIn(['attributes', name]);
  };

  _this.mjName = function () {
    return _this.constructor.tagName;
  };

  _this.mjContent = function () {
    var content = _this.mjml.get('content');

    if (content) {
      return (0, _trim2.default)(content);
    }

    return _react2.default.Children.map(_this.props.children, function (child) {
      if (typeof child === 'string') {
        return child;
      }
      return _server2.default.renderToStaticMarkup(child);
    });
  };

  _this.isInheritedAttributes = function (name) {
    return _this.mjml.get('inheritedAttributes') && _this.mjml.get('inheritedAttributes').includes(name);
  };

  _this.getWidth = function () {
    return _this.mjAttribute('rawPxWidth') || _this.mjAttribute('width');
  };

  _this.getParentWidth = function () {
    return _this.mjAttribute('parentWidth');
  };

  _this.renderWrappedOutlookChildren = function (children) {
    children = _react2.default.Children.toArray(children);

    var realChildren = children.filter(function (child) {
      return !child.props.mjml || child.props.mjml.get('tagName') !== 'mj-raw';
    });

    var prefix = _this.mjName() + '-outlook';
    var parentWidth = _this.getWidth();
    var siblings = realChildren.length;
    var elementsWidth = realChildren.map(function (element) {
      if (_this.isInheritedAttributes('width')) {
        return parseInt(parentWidth);
      }

      return getElementWidth({ element: element, siblings: siblings, parentWidth: parentWidth });
    });

    var wrappedElements = [];

    if (siblings == 0) {
      return wrappedElements;
    }

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-open', className: prefix + '-open', 'data-width':
elementsWidth[0] }));

    var i = 0;

    children.forEach(function (child) {
      var childProps = Object.assign({}, child.props);

      if (childProps.mjml) {
        childProps.mjml = childProps.mjml.setIn(['attributes', 'rawPxWidth'], elementsWidth[i]);

        if (_this.mjml.get('inheritedAttributes')) {
          childProps.mjml = childProps.mjml.mergeIn(['attributes', _this.inheritedAttributes()]);
        }
      } else {
        Object.assign(childProps, { rawPxWidth: elementsWidth[i] });

        if (_this.mjml.get('inheritedAttributes')) {
          Object.assign(childProps, _this.inheritedAttributes());
        }
      }

      var childWithProps = _react2.default.cloneElement(child, childProps);

      wrappedElements.push(childWithProps);
      if (!childWithProps.type.rawElement && i < realChildren.length - 1) {
        wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-' + i, className: prefix + '-line', 'data-width
': elementsWidth[++i] }));
      }
    });

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-close', className: prefix + '-close' }));

    return wrappedElements;
  };

  _this.paddingParser = function (direction) {
    var prefix = arguments.length > 1 && arguments[1] !== undefined ? arguments[1] : '';

    var paddingDirection = _this.mjAttribute(prefix + 'padding-' + direction);
    var padding = _this.mjAttribute(prefix + 'padding');

    if (paddingDirection != null) {
      return parseInt(paddingDirection);
    }

    if (!padding) {
      return 0;
    }

    var paddings = padding.split(' ');
    var directions = {};

    switch (paddings.length) {
      case 1:
        return parseInt(padding);
      case 2:
        directions = { top: 0, bottom: 0, left: 1, right: 1 };
        break;
      case 3:
        directions = { top: 0, left: 1, right: 1, bottom: 2 };
        break;
      case 4:
        directions = { top: 0, right: 1, bottom: 2, left: 3 };
        break;
    }

    return parseInt(paddings[directions[direction]] || 0);
  };

  _this.mjml = props.mjml || _immutable2. ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mjml.elements.mj-carousel-image"></a>[function <span class="apidocSignatureSpan">mjml.elements.</span>mj-carousel-image (props)](#apidoc.element.mjml.elements.mj-carousel-image)
- description and source-code
```javascript
function MJMLElement(props) {
  _classCallCheck(this, MJMLElement);

  var _this = _possibleConstructorReturn(this, (MJMLElement.__proto__ || Object.getPrototypeOf(MJMLElement)).call(this, props));

  _this.mjAttribute = function (name) {
    return _this.mjml.getIn(['attributes', name]);
  };

  _this.mjName = function () {
    return _this.constructor.tagName;
  };

  _this.mjContent = function () {
    var content = _this.mjml.get('content');

    if (content) {
      return (0, _trim2.default)(content);
    }

    return _react2.default.Children.map(_this.props.children, function (child) {
      if (typeof child === 'string') {
        return child;
      }
      return _server2.default.renderToStaticMarkup(child);
    });
  };

  _this.isInheritedAttributes = function (name) {
    return _this.mjml.get('inheritedAttributes') && _this.mjml.get('inheritedAttributes').includes(name);
  };

  _this.getWidth = function () {
    return _this.mjAttribute('rawPxWidth') || _this.mjAttribute('width');
  };

  _this.getParentWidth = function () {
    return _this.mjAttribute('parentWidth');
  };

  _this.renderWrappedOutlookChildren = function (children) {
    children = _react2.default.Children.toArray(children);

    var realChildren = children.filter(function (child) {
      return !child.props.mjml || child.props.mjml.get('tagName') !== 'mj-raw';
    });

    var prefix = _this.mjName() + '-outlook';
    var parentWidth = _this.getWidth();
    var siblings = realChildren.length;
    var elementsWidth = realChildren.map(function (element) {
      if (_this.isInheritedAttributes('width')) {
        return parseInt(parentWidth);
      }

      return getElementWidth({ element: element, siblings: siblings, parentWidth: parentWidth });
    });

    var wrappedElements = [];

    if (siblings == 0) {
      return wrappedElements;
    }

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-open', className: prefix + '-open', 'data-width':
elementsWidth[0] }));

    var i = 0;

    children.forEach(function (child) {
      var childProps = Object.assign({}, child.props);

      if (childProps.mjml) {
        childProps.mjml = childProps.mjml.setIn(['attributes', 'rawPxWidth'], elementsWidth[i]);

        if (_this.mjml.get('inheritedAttributes')) {
          childProps.mjml = childProps.mjml.mergeIn(['attributes', _this.inheritedAttributes()]);
        }
      } else {
        Object.assign(childProps, { rawPxWidth: elementsWidth[i] });

        if (_this.mjml.get('inheritedAttributes')) {
          Object.assign(childProps, _this.inheritedAttributes());
        }
      }

      var childWithProps = _react2.default.cloneElement(child, childProps);

      wrappedElements.push(childWithProps);
      if (!childWithProps.type.rawElement && i < realChildren.length - 1) {
        wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-' + i, className: prefix + '-line', 'data-width
': elementsWidth[++i] }));
      }
    });

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-close', className: prefix + '-close' }));

    return wrappedElements;
  };

  _this.paddingParser = function (direction) {
    var prefix = arguments.length > 1 && arguments[1] !== undefined ? arguments[1] : '';

    var paddingDirection = _this.mjAttribute(prefix + 'padding-' + direction);
    var padding = _this.mjAttribute(prefix + 'padding');

    if (paddingDirection != null) {
      return parseInt(paddingDirection);
    }

    if (!padding) {
      return 0;
    }

    var paddings = padding.split(' ');
    var directions = {};

    switch (paddings.length) {
      case 1:
        return parseInt(padding);
      case 2:
        directions = { top: 0, bottom: 0, left: 1, right: 1 };
        break;
      case 3:
        directions = { top: 0, left: 1, right: 1, bottom: 2 };
        break;
      case 4:
        directions = { top: 0, right: 1, bottom: 2, left: 3 };
        break;
    }

    return parseInt(paddings[directions[direction]] || 0);
  };

  _this.mjml = props.mjml || _immutable2. ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mjml.elements.mj-column"></a>[function <span class="apidocSignatureSpan">mjml.elements.</span>mj-column (props)](#apidoc.element.mjml.elements.mj-column)
- description and source-code
```javascript
function MJMLElement(props) {
  _classCallCheck(this, MJMLElement);

  var _this = _possibleConstructorReturn(this, (MJMLElement.__proto__ || Object.getPrototypeOf(MJMLElement)).call(this, props));

  _this.mjAttribute = function (name) {
    return _this.mjml.getIn(['attributes', name]);
  };

  _this.mjName = function () {
    return _this.constructor.tagName;
  };

  _this.mjContent = function () {
    var content = _this.mjml.get('content');

    if (content) {
      return (0, _trim2.default)(content);
    }

    return _react2.default.Children.map(_this.props.children, function (child) {
      if (typeof child === 'string') {
        return child;
      }
      return _server2.default.renderToStaticMarkup(child);
    });
  };

  _this.isInheritedAttributes = function (name) {
    return _this.mjml.get('inheritedAttributes') && _this.mjml.get('inheritedAttributes').includes(name);
  };

  _this.getWidth = function () {
    return _this.mjAttribute('rawPxWidth') || _this.mjAttribute('width');
  };

  _this.getParentWidth = function () {
    return _this.mjAttribute('parentWidth');
  };

  _this.renderWrappedOutlookChildren = function (children) {
    children = _react2.default.Children.toArray(children);

    var realChildren = children.filter(function (child) {
      return !child.props.mjml || child.props.mjml.get('tagName') !== 'mj-raw';
    });

    var prefix = _this.mjName() + '-outlook';
    var parentWidth = _this.getWidth();
    var siblings = realChildren.length;
    var elementsWidth = realChildren.map(function (element) {
      if (_this.isInheritedAttributes('width')) {
        return parseInt(parentWidth);
      }

      return getElementWidth({ element: element, siblings: siblings, parentWidth: parentWidth });
    });

    var wrappedElements = [];

    if (siblings == 0) {
      return wrappedElements;
    }

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-open', className: prefix + '-open', 'data-width':
elementsWidth[0] }));

    var i = 0;

    children.forEach(function (child) {
      var childProps = Object.assign({}, child.props);

      if (childProps.mjml) {
        childProps.mjml = childProps.mjml.setIn(['attributes', 'rawPxWidth'], elementsWidth[i]);

        if (_this.mjml.get('inheritedAttributes')) {
          childProps.mjml = childProps.mjml.mergeIn(['attributes', _this.inheritedAttributes()]);
        }
      } else {
        Object.assign(childProps, { rawPxWidth: elementsWidth[i] });

        if (_this.mjml.get('inheritedAttributes')) {
          Object.assign(childProps, _this.inheritedAttributes());
        }
      }

      var childWithProps = _react2.default.cloneElement(child, childProps);

      wrappedElements.push(childWithProps);
      if (!childWithProps.type.rawElement && i < realChildren.length - 1) {
        wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-' + i, className: prefix + '-line', 'data-width
': elementsWidth[++i] }));
      }
    });

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-close', className: prefix + '-close' }));

    return wrappedElements;
  };

  _this.paddingParser = function (direction) {
    var prefix = arguments.length > 1 && arguments[1] !== undefined ? arguments[1] : '';

    var paddingDirection = _this.mjAttribute(prefix + 'padding-' + direction);
    var padding = _this.mjAttribute(prefix + 'padding');

    if (paddingDirection != null) {
      return parseInt(paddingDirection);
    }

    if (!padding) {
      return 0;
    }

    var paddings = padding.split(' ');
    var directions = {};

    switch (paddings.length) {
      case 1:
        return parseInt(padding);
      case 2:
        directions = { top: 0, bottom: 0, left: 1, right: 1 };
        break;
      case 3:
        directions = { top: 0, left: 1, right: 1, bottom: 2 };
        break;
      case 4:
        directions = { top: 0, right: 1, bottom: 2, left: 3 };
        break;
    }

    return parseInt(paddings[directions[direction]] || 0);
  };

  _this.mjml = props.mjml || _immutable2. ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mjml.elements.mj-container"></a>[function <span class="apidocSignatureSpan">mjml.elements.</span>mj-container (props)](#apidoc.element.mjml.elements.mj-container)
- description and source-code
```javascript
function MJMLElement(props) {
  _classCallCheck(this, MJMLElement);

  var _this = _possibleConstructorReturn(this, (MJMLElement.__proto__ || Object.getPrototypeOf(MJMLElement)).call(this, props));

  _this.mjAttribute = function (name) {
    return _this.mjml.getIn(['attributes', name]);
  };

  _this.mjName = function () {
    return _this.constructor.tagName;
  };

  _this.mjContent = function () {
    var content = _this.mjml.get('content');

    if (content) {
      return (0, _trim2.default)(content);
    }

    return _react2.default.Children.map(_this.props.children, function (child) {
      if (typeof child === 'string') {
        return child;
      }
      return _server2.default.renderToStaticMarkup(child);
    });
  };

  _this.isInheritedAttributes = function (name) {
    return _this.mjml.get('inheritedAttributes') && _this.mjml.get('inheritedAttributes').includes(name);
  };

  _this.getWidth = function () {
    return _this.mjAttribute('rawPxWidth') || _this.mjAttribute('width');
  };

  _this.getParentWidth = function () {
    return _this.mjAttribute('parentWidth');
  };

  _this.renderWrappedOutlookChildren = function (children) {
    children = _react2.default.Children.toArray(children);

    var realChildren = children.filter(function (child) {
      return !child.props.mjml || child.props.mjml.get('tagName') !== 'mj-raw';
    });

    var prefix = _this.mjName() + '-outlook';
    var parentWidth = _this.getWidth();
    var siblings = realChildren.length;
    var elementsWidth = realChildren.map(function (element) {
      if (_this.isInheritedAttributes('width')) {
        return parseInt(parentWidth);
      }

      return getElementWidth({ element: element, siblings: siblings, parentWidth: parentWidth });
    });

    var wrappedElements = [];

    if (siblings == 0) {
      return wrappedElements;
    }

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-open', className: prefix + '-open', 'data-width':
elementsWidth[0] }));

    var i = 0;

    children.forEach(function (child) {
      var childProps = Object.assign({}, child.props);

      if (childProps.mjml) {
        childProps.mjml = childProps.mjml.setIn(['attributes', 'rawPxWidth'], elementsWidth[i]);

        if (_this.mjml.get('inheritedAttributes')) {
          childProps.mjml = childProps.mjml.mergeIn(['attributes', _this.inheritedAttributes()]);
        }
      } else {
        Object.assign(childProps, { rawPxWidth: elementsWidth[i] });

        if (_this.mjml.get('inheritedAttributes')) {
          Object.assign(childProps, _this.inheritedAttributes());
        }
      }

      var childWithProps = _react2.default.cloneElement(child, childProps);

      wrappedElements.push(childWithProps);
      if (!childWithProps.type.rawElement && i < realChildren.length - 1) {
        wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-' + i, className: prefix + '-line', 'data-width
': elementsWidth[++i] }));
      }
    });

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-close', className: prefix + '-close' }));

    return wrappedElements;
  };

  _this.paddingParser = function (direction) {
    var prefix = arguments.length > 1 && arguments[1] !== undefined ? arguments[1] : '';

    var paddingDirection = _this.mjAttribute(prefix + 'padding-' + direction);
    var padding = _this.mjAttribute(prefix + 'padding');

    if (paddingDirection != null) {
      return parseInt(paddingDirection);
    }

    if (!padding) {
      return 0;
    }

    var paddings = padding.split(' ');
    var directions = {};

    switch (paddings.length) {
      case 1:
        return parseInt(padding);
      case 2:
        directions = { top: 0, bottom: 0, left: 1, right: 1 };
        break;
      case 3:
        directions = { top: 0, left: 1, right: 1, bottom: 2 };
        break;
      case 4:
        directions = { top: 0, right: 1, bottom: 2, left: 3 };
        break;
    }

    return parseInt(paddings[directions[direction]] || 0);
  };

  _this.mjml = props.mjml || _immutable2. ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mjml.elements.mj-divider"></a>[function <span class="apidocSignatureSpan">mjml.elements.</span>mj-divider (props)](#apidoc.element.mjml.elements.mj-divider)
- description and source-code
```javascript
function MJMLElement(props) {
  _classCallCheck(this, MJMLElement);

  var _this = _possibleConstructorReturn(this, (MJMLElement.__proto__ || Object.getPrototypeOf(MJMLElement)).call(this, props));

  _this.mjAttribute = function (name) {
    return _this.mjml.getIn(['attributes', name]);
  };

  _this.mjName = function () {
    return _this.constructor.tagName;
  };

  _this.mjContent = function () {
    var content = _this.mjml.get('content');

    if (content) {
      return (0, _trim2.default)(content);
    }

    return _react2.default.Children.map(_this.props.children, function (child) {
      if (typeof child === 'string') {
        return child;
      }
      return _server2.default.renderToStaticMarkup(child);
    });
  };

  _this.isInheritedAttributes = function (name) {
    return _this.mjml.get('inheritedAttributes') && _this.mjml.get('inheritedAttributes').includes(name);
  };

  _this.getWidth = function () {
    return _this.mjAttribute('rawPxWidth') || _this.mjAttribute('width');
  };

  _this.getParentWidth = function () {
    return _this.mjAttribute('parentWidth');
  };

  _this.renderWrappedOutlookChildren = function (children) {
    children = _react2.default.Children.toArray(children);

    var realChildren = children.filter(function (child) {
      return !child.props.mjml || child.props.mjml.get('tagName') !== 'mj-raw';
    });

    var prefix = _this.mjName() + '-outlook';
    var parentWidth = _this.getWidth();
    var siblings = realChildren.length;
    var elementsWidth = realChildren.map(function (element) {
      if (_this.isInheritedAttributes('width')) {
        return parseInt(parentWidth);
      }

      return getElementWidth({ element: element, siblings: siblings, parentWidth: parentWidth });
    });

    var wrappedElements = [];

    if (siblings == 0) {
      return wrappedElements;
    }

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-open', className: prefix + '-open', 'data-width':
elementsWidth[0] }));

    var i = 0;

    children.forEach(function (child) {
      var childProps = Object.assign({}, child.props);

      if (childProps.mjml) {
        childProps.mjml = childProps.mjml.setIn(['attributes', 'rawPxWidth'], elementsWidth[i]);

        if (_this.mjml.get('inheritedAttributes')) {
          childProps.mjml = childProps.mjml.mergeIn(['attributes', _this.inheritedAttributes()]);
        }
      } else {
        Object.assign(childProps, { rawPxWidth: elementsWidth[i] });

        if (_this.mjml.get('inheritedAttributes')) {
          Object.assign(childProps, _this.inheritedAttributes());
        }
      }

      var childWithProps = _react2.default.cloneElement(child, childProps);

      wrappedElements.push(childWithProps);
      if (!childWithProps.type.rawElement && i < realChildren.length - 1) {
        wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-' + i, className: prefix + '-line', 'data-width
': elementsWidth[++i] }));
      }
    });

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-close', className: prefix + '-close' }));

    return wrappedElements;
  };

  _this.paddingParser = function (direction) {
    var prefix = arguments.length > 1 && arguments[1] !== undefined ? arguments[1] : '';

    var paddingDirection = _this.mjAttribute(prefix + 'padding-' + direction);
    var padding = _this.mjAttribute(prefix + 'padding');

    if (paddingDirection != null) {
      return parseInt(paddingDirection);
    }

    if (!padding) {
      return 0;
    }

    var paddings = padding.split(' ');
    var directions = {};

    switch (paddings.length) {
      case 1:
        return parseInt(padding);
      case 2:
        directions = { top: 0, bottom: 0, left: 1, right: 1 };
        break;
      case 3:
        directions = { top: 0, left: 1, right: 1, bottom: 2 };
        break;
      case 4:
        directions = { top: 0, right: 1, bottom: 2, left: 3 };
        break;
    }

    return parseInt(paddings[directions[direction]] || 0);
  };

  _this.mjml = props.mjml || _immutable2. ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mjml.elements.mj-group"></a>[function <span class="apidocSignatureSpan">mjml.elements.</span>mj-group (props)](#apidoc.element.mjml.elements.mj-group)
- description and source-code
```javascript
function MJMLElement(props) {
  _classCallCheck(this, MJMLElement);

  var _this = _possibleConstructorReturn(this, (MJMLElement.__proto__ || Object.getPrototypeOf(MJMLElement)).call(this, props));

  _this.mjAttribute = function (name) {
    return _this.mjml.getIn(['attributes', name]);
  };

  _this.mjName = function () {
    return _this.constructor.tagName;
  };

  _this.mjContent = function () {
    var content = _this.mjml.get('content');

    if (content) {
      return (0, _trim2.default)(content);
    }

    return _react2.default.Children.map(_this.props.children, function (child) {
      if (typeof child === 'string') {
        return child;
      }
      return _server2.default.renderToStaticMarkup(child);
    });
  };

  _this.isInheritedAttributes = function (name) {
    return _this.mjml.get('inheritedAttributes') && _this.mjml.get('inheritedAttributes').includes(name);
  };

  _this.getWidth = function () {
    return _this.mjAttribute('rawPxWidth') || _this.mjAttribute('width');
  };

  _this.getParentWidth = function () {
    return _this.mjAttribute('parentWidth');
  };

  _this.renderWrappedOutlookChildren = function (children) {
    children = _react2.default.Children.toArray(children);

    var realChildren = children.filter(function (child) {
      return !child.props.mjml || child.props.mjml.get('tagName') !== 'mj-raw';
    });

    var prefix = _this.mjName() + '-outlook';
    var parentWidth = _this.getWidth();
    var siblings = realChildren.length;
    var elementsWidth = realChildren.map(function (element) {
      if (_this.isInheritedAttributes('width')) {
        return parseInt(parentWidth);
      }

      return getElementWidth({ element: element, siblings: siblings, parentWidth: parentWidth });
    });

    var wrappedElements = [];

    if (siblings == 0) {
      return wrappedElements;
    }

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-open', className: prefix + '-open', 'data-width':
elementsWidth[0] }));

    var i = 0;

    children.forEach(function (child) {
      var childProps = Object.assign({}, child.props);

      if (childProps.mjml) {
        childProps.mjml = childProps.mjml.setIn(['attributes', 'rawPxWidth'], elementsWidth[i]);

        if (_this.mjml.get('inheritedAttributes')) {
          childProps.mjml = childProps.mjml.mergeIn(['attributes', _this.inheritedAttributes()]);
        }
      } else {
        Object.assign(childProps, { rawPxWidth: elementsWidth[i] });

        if (_this.mjml.get('inheritedAttributes')) {
          Object.assign(childProps, _this.inheritedAttributes());
        }
      }

      var childWithProps = _react2.default.cloneElement(child, childProps);

      wrappedElements.push(childWithProps);
      if (!childWithProps.type.rawElement && i < realChildren.length - 1) {
        wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-' + i, className: prefix + '-line', 'data-width
': elementsWidth[++i] }));
      }
    });

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-close', className: prefix + '-close' }));

    return wrappedElements;
  };

  _this.paddingParser = function (direction) {
    var prefix = arguments.length > 1 && arguments[1] !== undefined ? arguments[1] : '';

    var paddingDirection = _this.mjAttribute(prefix + 'padding-' + direction);
    var padding = _this.mjAttribute(prefix + 'padding');

    if (paddingDirection != null) {
      return parseInt(paddingDirection);
    }

    if (!padding) {
      return 0;
    }

    var paddings = padding.split(' ');
    var directions = {};

    switch (paddings.length) {
      case 1:
        return parseInt(padding);
      case 2:
        directions = { top: 0, bottom: 0, left: 1, right: 1 };
        break;
      case 3:
        directions = { top: 0, left: 1, right: 1, bottom: 2 };
        break;
      case 4:
        directions = { top: 0, right: 1, bottom: 2, left: 3 };
        break;
    }

    return parseInt(paddings[directions[direction]] || 0);
  };

  _this.mjml = props.mjml || _immutable2. ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mjml.elements.mj-hero"></a>[function <span class="apidocSignatureSpan">mjml.elements.</span>mj-hero (props)](#apidoc.element.mjml.elements.mj-hero)
- description and source-code
```javascript
function MJMLElement(props) {
  _classCallCheck(this, MJMLElement);

  var _this = _possibleConstructorReturn(this, (MJMLElement.__proto__ || Object.getPrototypeOf(MJMLElement)).call(this, props));

  _this.mjAttribute = function (name) {
    return _this.mjml.getIn(['attributes', name]);
  };

  _this.mjName = function () {
    return _this.constructor.tagName;
  };

  _this.mjContent = function () {
    var content = _this.mjml.get('content');

    if (content) {
      return (0, _trim2.default)(content);
    }

    return _react2.default.Children.map(_this.props.children, function (child) {
      if (typeof child === 'string') {
        return child;
      }
      return _server2.default.renderToStaticMarkup(child);
    });
  };

  _this.isInheritedAttributes = function (name) {
    return _this.mjml.get('inheritedAttributes') && _this.mjml.get('inheritedAttributes').includes(name);
  };

  _this.getWidth = function () {
    return _this.mjAttribute('rawPxWidth') || _this.mjAttribute('width');
  };

  _this.getParentWidth = function () {
    return _this.mjAttribute('parentWidth');
  };

  _this.renderWrappedOutlookChildren = function (children) {
    children = _react2.default.Children.toArray(children);

    var realChildren = children.filter(function (child) {
      return !child.props.mjml || child.props.mjml.get('tagName') !== 'mj-raw';
    });

    var prefix = _this.mjName() + '-outlook';
    var parentWidth = _this.getWidth();
    var siblings = realChildren.length;
    var elementsWidth = realChildren.map(function (element) {
      if (_this.isInheritedAttributes('width')) {
        return parseInt(parentWidth);
      }

      return getElementWidth({ element: element, siblings: siblings, parentWidth: parentWidth });
    });

    var wrappedElements = [];

    if (siblings == 0) {
      return wrappedElements;
    }

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-open', className: prefix + '-open', 'data-width':
elementsWidth[0] }));

    var i = 0;

    children.forEach(function (child) {
      var childProps = Object.assign({}, child.props);

      if (childProps.mjml) {
        childProps.mjml = childProps.mjml.setIn(['attributes', 'rawPxWidth'], elementsWidth[i]);

        if (_this.mjml.get('inheritedAttributes')) {
          childProps.mjml = childProps.mjml.mergeIn(['attributes', _this.inheritedAttributes()]);
        }
      } else {
        Object.assign(childProps, { rawPxWidth: elementsWidth[i] });

        if (_this.mjml.get('inheritedAttributes')) {
          Object.assign(childProps, _this.inheritedAttributes());
        }
      }

      var childWithProps = _react2.default.cloneElement(child, childProps);

      wrappedElements.push(childWithProps);
      if (!childWithProps.type.rawElement && i < realChildren.length - 1) {
        wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-' + i, className: prefix + '-line', 'data-width
': elementsWidth[++i] }));
      }
    });

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-close', className: prefix + '-close' }));

    return wrappedElements;
  };

  _this.paddingParser = function (direction) {
    var prefix = arguments.length > 1 && arguments[1] !== undefined ? arguments[1] : '';

    var paddingDirection = _this.mjAttribute(prefix + 'padding-' + direction);
    var padding = _this.mjAttribute(prefix + 'padding');

    if (paddingDirection != null) {
      return parseInt(paddingDirection);
    }

    if (!padding) {
      return 0;
    }

    var paddings = padding.split(' ');
    var directions = {};

    switch (paddings.length) {
      case 1:
        return parseInt(padding);
      case 2:
        directions = { top: 0, bottom: 0, left: 1, right: 1 };
        break;
      case 3:
        directions = { top: 0, left: 1, right: 1, bottom: 2 };
        break;
      case 4:
        directions = { top: 0, right: 1, bottom: 2, left: 3 };
        break;
    }

    return parseInt(paddings[directions[direction]] || 0);
  };

  _this.mjml = props.mjml || _immutable2. ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mjml.elements.mj-hero-content"></a>[function <span class="apidocSignatureSpan">mjml.elements.</span>mj-hero-content (props)](#apidoc.element.mjml.elements.mj-hero-content)
- description and source-code
```javascript
function MJMLElement(props) {
  _classCallCheck(this, MJMLElement);

  var _this = _possibleConstructorReturn(this, (MJMLElement.__proto__ || Object.getPrototypeOf(MJMLElement)).call(this, props));

  _this.mjAttribute = function (name) {
    return _this.mjml.getIn(['attributes', name]);
  };

  _this.mjName = function () {
    return _this.constructor.tagName;
  };

  _this.mjContent = function () {
    var content = _this.mjml.get('content');

    if (content) {
      return (0, _trim2.default)(content);
    }

    return _react2.default.Children.map(_this.props.children, function (child) {
      if (typeof child === 'string') {
        return child;
      }
      return _server2.default.renderToStaticMarkup(child);
    });
  };

  _this.isInheritedAttributes = function (name) {
    return _this.mjml.get('inheritedAttributes') && _this.mjml.get('inheritedAttributes').includes(name);
  };

  _this.getWidth = function () {
    return _this.mjAttribute('rawPxWidth') || _this.mjAttribute('width');
  };

  _this.getParentWidth = function () {
    return _this.mjAttribute('parentWidth');
  };

  _this.renderWrappedOutlookChildren = function (children) {
    children = _react2.default.Children.toArray(children);

    var realChildren = children.filter(function (child) {
      return !child.props.mjml || child.props.mjml.get('tagName') !== 'mj-raw';
    });

    var prefix = _this.mjName() + '-outlook';
    var parentWidth = _this.getWidth();
    var siblings = realChildren.length;
    var elementsWidth = realChildren.map(function (element) {
      if (_this.isInheritedAttributes('width')) {
        return parseInt(parentWidth);
      }

      return getElementWidth({ element: element, siblings: siblings, parentWidth: parentWidth });
    });

    var wrappedElements = [];

    if (siblings == 0) {
      return wrappedElements;
    }

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-open', className: prefix + '-open', 'data-width':
elementsWidth[0] }));

    var i = 0;

    children.forEach(function (child) {
      var childProps = Object.assign({}, child.props);

      if (childProps.mjml) {
        childProps.mjml = childProps.mjml.setIn(['attributes', 'rawPxWidth'], elementsWidth[i]);

        if (_this.mjml.get('inheritedAttributes')) {
          childProps.mjml = childProps.mjml.mergeIn(['attributes', _this.inheritedAttributes()]);
        }
      } else {
        Object.assign(childProps, { rawPxWidth: elementsWidth[i] });

        if (_this.mjml.get('inheritedAttributes')) {
          Object.assign(childProps, _this.inheritedAttributes());
        }
      }

      var childWithProps = _react2.default.cloneElement(child, childProps);

      wrappedElements.push(childWithProps);
      if (!childWithProps.type.rawElement && i < realChildren.length - 1) {
        wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-' + i, className: prefix + '-line', 'data-width
': elementsWidth[++i] }));
      }
    });

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-close', className: prefix + '-close' }));

    return wrappedElements;
  };

  _this.paddingParser = function (direction) {
    var prefix = arguments.length > 1 && arguments[1] !== undefined ? arguments[1] : '';

    var paddingDirection = _this.mjAttribute(prefix + 'padding-' + direction);
    var padding = _this.mjAttribute(prefix + 'padding');

    if (paddingDirection != null) {
      return parseInt(paddingDirection);
    }

    if (!padding) {
      return 0;
    }

    var paddings = padding.split(' ');
    var directions = {};

    switch (paddings.length) {
      case 1:
        return parseInt(padding);
      case 2:
        directions = { top: 0, bottom: 0, left: 1, right: 1 };
        break;
      case 3:
        directions = { top: 0, left: 1, right: 1, bottom: 2 };
        break;
      case 4:
        directions = { top: 0, right: 1, bottom: 2, left: 3 };
        break;
    }

    return parseInt(paddings[directions[direction]] || 0);
  };

  _this.mjml = props.mjml || _immutable2. ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mjml.elements.mj-html"></a>[function <span class="apidocSignatureSpan">mjml.elements.</span>mj-html (props)](#apidoc.element.mjml.elements.mj-html)
- description and source-code
```javascript
function MJMLElement(props) {
  _classCallCheck(this, MJMLElement);

  var _this = _possibleConstructorReturn(this, (MJMLElement.__proto__ || Object.getPrototypeOf(MJMLElement)).call(this, props));

  _this.mjAttribute = function (name) {
    return _this.mjml.getIn(['attributes', name]);
  };

  _this.mjName = function () {
    return _this.constructor.tagName;
  };

  _this.mjContent = function () {
    var content = _this.mjml.get('content');

    if (content) {
      return (0, _trim2.default)(content);
    }

    return _react2.default.Children.map(_this.props.children, function (child) {
      if (typeof child === 'string') {
        return child;
      }
      return _server2.default.renderToStaticMarkup(child);
    });
  };

  _this.isInheritedAttributes = function (name) {
    return _this.mjml.get('inheritedAttributes') && _this.mjml.get('inheritedAttributes').includes(name);
  };

  _this.getWidth = function () {
    return _this.mjAttribute('rawPxWidth') || _this.mjAttribute('width');
  };

  _this.getParentWidth = function () {
    return _this.mjAttribute('parentWidth');
  };

  _this.renderWrappedOutlookChildren = function (children) {
    children = _react2.default.Children.toArray(children);

    var realChildren = children.filter(function (child) {
      return !child.props.mjml || child.props.mjml.get('tagName') !== 'mj-raw';
    });

    var prefix = _this.mjName() + '-outlook';
    var parentWidth = _this.getWidth();
    var siblings = realChildren.length;
    var elementsWidth = realChildren.map(function (element) {
      if (_this.isInheritedAttributes('width')) {
        return parseInt(parentWidth);
      }

      return getElementWidth({ element: element, siblings: siblings, parentWidth: parentWidth });
    });

    var wrappedElements = [];

    if (siblings == 0) {
      return wrappedElements;
    }

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-open', className: prefix + '-open', 'data-width':
elementsWidth[0] }));

    var i = 0;

    children.forEach(function (child) {
      var childProps = Object.assign({}, child.props);

      if (childProps.mjml) {
        childProps.mjml = childProps.mjml.setIn(['attributes', 'rawPxWidth'], elementsWidth[i]);

        if (_this.mjml.get('inheritedAttributes')) {
          childProps.mjml = childProps.mjml.mergeIn(['attributes', _this.inheritedAttributes()]);
        }
      } else {
        Object.assign(childProps, { rawPxWidth: elementsWidth[i] });

        if (_this.mjml.get('inheritedAttributes')) {
          Object.assign(childProps, _this.inheritedAttributes());
        }
      }

      var childWithProps = _react2.default.cloneElement(child, childProps);

      wrappedElements.push(childWithProps);
      if (!childWithProps.type.rawElement && i < realChildren.length - 1) {
        wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-' + i, className: prefix + '-line', 'data-width
': elementsWidth[++i] }));
      }
    });

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-close', className: prefix + '-close' }));

    return wrappedElements;
  };

  _this.paddingParser = function (direction) {
    var prefix = arguments.length > 1 && arguments[1] !== undefined ? arguments[1] : '';

    var paddingDirection = _this.mjAttribute(prefix + 'padding-' + direction);
    var padding = _this.mjAttribute(prefix + 'padding');

    if (paddingDirection != null) {
      return parseInt(paddingDirection);
    }

    if (!padding) {
      return 0;
    }

    var paddings = padding.split(' ');
    var directions = {};

    switch (paddings.length) {
      case 1:
        return parseInt(padding);
      case 2:
        directions = { top: 0, bottom: 0, left: 1, right: 1 };
        break;
      case 3:
        directions = { top: 0, left: 1, right: 1, bottom: 2 };
        break;
      case 4:
        directions = { top: 0, right: 1, bottom: 2, left: 3 };
        break;
    }

    return parseInt(paddings[directions[direction]] || 0);
  };

  _this.mjml = props.mjml || _immutable2. ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mjml.elements.mj-image"></a>[function <span class="apidocSignatureSpan">mjml.elements.</span>mj-image (props)](#apidoc.element.mjml.elements.mj-image)
- description and source-code
```javascript
function MJMLElement(props) {
  _classCallCheck(this, MJMLElement);

  var _this = _possibleConstructorReturn(this, (MJMLElement.__proto__ || Object.getPrototypeOf(MJMLElement)).call(this, props));

  _this.mjAttribute = function (name) {
    return _this.mjml.getIn(['attributes', name]);
  };

  _this.mjName = function () {
    return _this.constructor.tagName;
  };

  _this.mjContent = function () {
    var content = _this.mjml.get('content');

    if (content) {
      return (0, _trim2.default)(content);
    }

    return _react2.default.Children.map(_this.props.children, function (child) {
      if (typeof child === 'string') {
        return child;
      }
      return _server2.default.renderToStaticMarkup(child);
    });
  };

  _this.isInheritedAttributes = function (name) {
    return _this.mjml.get('inheritedAttributes') && _this.mjml.get('inheritedAttributes').includes(name);
  };

  _this.getWidth = function () {
    return _this.mjAttribute('rawPxWidth') || _this.mjAttribute('width');
  };

  _this.getParentWidth = function () {
    return _this.mjAttribute('parentWidth');
  };

  _this.renderWrappedOutlookChildren = function (children) {
    children = _react2.default.Children.toArray(children);

    var realChildren = children.filter(function (child) {
      return !child.props.mjml || child.props.mjml.get('tagName') !== 'mj-raw';
    });

    var prefix = _this.mjName() + '-outlook';
    var parentWidth = _this.getWidth();
    var siblings = realChildren.length;
    var elementsWidth = realChildren.map(function (element) {
      if (_this.isInheritedAttributes('width')) {
        return parseInt(parentWidth);
      }

      return getElementWidth({ element: element, siblings: siblings, parentWidth: parentWidth });
    });

    var wrappedElements = [];

    if (siblings == 0) {
      return wrappedElements;
    }

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-open', className: prefix + '-open', 'data-width':
elementsWidth[0] }));

    var i = 0;

    children.forEach(function (child) {
      var childProps = Object.assign({}, child.props);

      if (childProps.mjml) {
        childProps.mjml = childProps.mjml.setIn(['attributes', 'rawPxWidth'], elementsWidth[i]);

        if (_this.mjml.get('inheritedAttributes')) {
          childProps.mjml = childProps.mjml.mergeIn(['attributes', _this.inheritedAttributes()]);
        }
      } else {
        Object.assign(childProps, { rawPxWidth: elementsWidth[i] });

        if (_this.mjml.get('inheritedAttributes')) {
          Object.assign(childProps, _this.inheritedAttributes());
        }
      }

      var childWithProps = _react2.default.cloneElement(child, childProps);

      wrappedElements.push(childWithProps);
      if (!childWithProps.type.rawElement && i < realChildren.length - 1) {
        wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-' + i, className: prefix + '-line', 'data-width
': elementsWidth[++i] }));
      }
    });

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-close', className: prefix + '-close' }));

    return wrappedElements;
  };

  _this.paddingParser = function (direction) {
    var prefix = arguments.length > 1 && arguments[1] !== undefined ? arguments[1] : '';

    var paddingDirection = _this.mjAttribute(prefix + 'padding-' + direction);
    var padding = _this.mjAttribute(prefix + 'padding');

    if (paddingDirection != null) {
      return parseInt(paddingDirection);
    }

    if (!padding) {
      return 0;
    }

    var paddings = padding.split(' ');
    var directions = {};

    switch (paddings.length) {
      case 1:
        return parseInt(padding);
      case 2:
        directions = { top: 0, bottom: 0, left: 1, right: 1 };
        break;
      case 3:
        directions = { top: 0, left: 1, right: 1, bottom: 2 };
        break;
      case 4:
        directions = { top: 0, right: 1, bottom: 2, left: 3 };
        break;
    }

    return parseInt(paddings[directions[direction]] || 0);
  };

  _this.mjml = props.mjml || _immutable2. ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mjml.elements.mj-inline-links"></a>[function <span class="apidocSignatureSpan">mjml.elements.</span>mj-inline-links (props)](#apidoc.element.mjml.elements.mj-inline-links)
- description and source-code
```javascript
function MJMLElement(props) {
  _classCallCheck(this, MJMLElement);

  var _this = _possibleConstructorReturn(this, (MJMLElement.__proto__ || Object.getPrototypeOf(MJMLElement)).call(this, props));

  _this.mjAttribute = function (name) {
    return _this.mjml.getIn(['attributes', name]);
  };

  _this.mjName = function () {
    return _this.constructor.tagName;
  };

  _this.mjContent = function () {
    var content = _this.mjml.get('content');

    if (content) {
      return (0, _trim2.default)(content);
    }

    return _react2.default.Children.map(_this.props.children, function (child) {
      if (typeof child === 'string') {
        return child;
      }
      return _server2.default.renderToStaticMarkup(child);
    });
  };

  _this.isInheritedAttributes = function (name) {
    return _this.mjml.get('inheritedAttributes') && _this.mjml.get('inheritedAttributes').includes(name);
  };

  _this.getWidth = function () {
    return _this.mjAttribute('rawPxWidth') || _this.mjAttribute('width');
  };

  _this.getParentWidth = function () {
    return _this.mjAttribute('parentWidth');
  };

  _this.renderWrappedOutlookChildren = function (children) {
    children = _react2.default.Children.toArray(children);

    var realChildren = children.filter(function (child) {
      return !child.props.mjml || child.props.mjml.get('tagName') !== 'mj-raw';
    });

    var prefix = _this.mjName() + '-outlook';
    var parentWidth = _this.getWidth();
    var siblings = realChildren.length;
    var elementsWidth = realChildren.map(function (element) {
      if (_this.isInheritedAttributes('width')) {
        return parseInt(parentWidth);
      }

      return getElementWidth({ element: element, siblings: siblings, parentWidth: parentWidth });
    });

    var wrappedElements = [];

    if (siblings == 0) {
      return wrappedElements;
    }

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-open', className: prefix + '-open', 'data-width':
elementsWidth[0] }));

    var i = 0;

    children.forEach(function (child) {
      var childProps = Object.assign({}, child.props);

      if (childProps.mjml) {
        childProps.mjml = childProps.mjml.setIn(['attributes', 'rawPxWidth'], elementsWidth[i]);

        if (_this.mjml.get('inheritedAttributes')) {
          childProps.mjml = childProps.mjml.mergeIn(['attributes', _this.inheritedAttributes()]);
        }
      } else {
        Object.assign(childProps, { rawPxWidth: elementsWidth[i] });

        if (_this.mjml.get('inheritedAttributes')) {
          Object.assign(childProps, _this.inheritedAttributes());
        }
      }

      var childWithProps = _react2.default.cloneElement(child, childProps);

      wrappedElements.push(childWithProps);
      if (!childWithProps.type.rawElement && i < realChildren.length - 1) {
        wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-' + i, className: prefix + '-line', 'data-width
': elementsWidth[++i] }));
      }
    });

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-close', className: prefix + '-close' }));

    return wrappedElements;
  };

  _this.paddingParser = function (direction) {
    var prefix = arguments.length > 1 && arguments[1] !== undefined ? arguments[1] : '';

    var paddingDirection = _this.mjAttribute(prefix + 'padding-' + direction);
    var padding = _this.mjAttribute(prefix + 'padding');

    if (paddingDirection != null) {
      return parseInt(paddingDirection);
    }

    if (!padding) {
      return 0;
    }

    var paddings = padding.split(' ');
    var directions = {};

    switch (paddings.length) {
      case 1:
        return parseInt(padding);
      case 2:
        directions = { top: 0, bottom: 0, left: 1, right: 1 };
        break;
      case 3:
        directions = { top: 0, left: 1, right: 1, bottom: 2 };
        break;
      case 4:
        directions = { top: 0, right: 1, bottom: 2, left: 3 };
        break;
    }

    return parseInt(paddings[directions[direction]] || 0);
  };

  _this.mjml = props.mjml || _immutable2. ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mjml.elements.mj-invoice"></a>[function <span class="apidocSignatureSpan">mjml.elements.</span>mj-invoice (props)](#apidoc.element.mjml.elements.mj-invoice)
- description and source-code
```javascript
function MJMLElement(props) {
  _classCallCheck(this, MJMLElement);

  var _this = _possibleConstructorReturn(this, (MJMLElement.__proto__ || Object.getPrototypeOf(MJMLElement)).call(this, props));

  _this.mjAttribute = function (name) {
    return _this.mjml.getIn(['attributes', name]);
  };

  _this.mjName = function () {
    return _this.constructor.tagName;
  };

  _this.mjContent = function () {
    var content = _this.mjml.get('content');

    if (content) {
      return (0, _trim2.default)(content);
    }

    return _react2.default.Children.map(_this.props.children, function (child) {
      if (typeof child === 'string') {
        return child;
      }
      return _server2.default.renderToStaticMarkup(child);
    });
  };

  _this.isInheritedAttributes = function (name) {
    return _this.mjml.get('inheritedAttributes') && _this.mjml.get('inheritedAttributes').includes(name);
  };

  _this.getWidth = function () {
    return _this.mjAttribute('rawPxWidth') || _this.mjAttribute('width');
  };

  _this.getParentWidth = function () {
    return _this.mjAttribute('parentWidth');
  };

  _this.renderWrappedOutlookChildren = function (children) {
    children = _react2.default.Children.toArray(children);

    var realChildren = children.filter(function (child) {
      return !child.props.mjml || child.props.mjml.get('tagName') !== 'mj-raw';
    });

    var prefix = _this.mjName() + '-outlook';
    var parentWidth = _this.getWidth();
    var siblings = realChildren.length;
    var elementsWidth = realChildren.map(function (element) {
      if (_this.isInheritedAttributes('width')) {
        return parseInt(parentWidth);
      }

      return getElementWidth({ element: element, siblings: siblings, parentWidth: parentWidth });
    });

    var wrappedElements = [];

    if (siblings == 0) {
      return wrappedElements;
    }

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-open', className: prefix + '-open', 'data-width':
elementsWidth[0] }));

    var i = 0;

    children.forEach(function (child) {
      var childProps = Object.assign({}, child.props);

      if (childProps.mjml) {
        childProps.mjml = childProps.mjml.setIn(['attributes', 'rawPxWidth'], elementsWidth[i]);

        if (_this.mjml.get('inheritedAttributes')) {
          childProps.mjml = childProps.mjml.mergeIn(['attributes', _this.inheritedAttributes()]);
        }
      } else {
        Object.assign(childProps, { rawPxWidth: elementsWidth[i] });

        if (_this.mjml.get('inheritedAttributes')) {
          Object.assign(childProps, _this.inheritedAttributes());
        }
      }

      var childWithProps = _react2.default.cloneElement(child, childProps);

      wrappedElements.push(childWithProps);
      if (!childWithProps.type.rawElement && i < realChildren.length - 1) {
        wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-' + i, className: prefix + '-line', 'data-width
': elementsWidth[++i] }));
      }
    });

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-close', className: prefix + '-close' }));

    return wrappedElements;
  };

  _this.paddingParser = function (direction) {
    var prefix = arguments.length > 1 && arguments[1] !== undefined ? arguments[1] : '';

    var paddingDirection = _this.mjAttribute(prefix + 'padding-' + direction);
    var padding = _this.mjAttribute(prefix + 'padding');

    if (paddingDirection != null) {
      return parseInt(paddingDirection);
    }

    if (!padding) {
      return 0;
    }

    var paddings = padding.split(' ');
    var directions = {};

    switch (paddings.length) {
      case 1:
        return parseInt(padding);
      case 2:
        directions = { top: 0, bottom: 0, left: 1, right: 1 };
        break;
      case 3:
        directions = { top: 0, left: 1, right: 1, bottom: 2 };
        break;
      case 4:
        directions = { top: 0, right: 1, bottom: 2, left: 3 };
        break;
    }

    return parseInt(paddings[directions[direction]] || 0);
  };

  _this.mjml = props.mjml || _immutable2. ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mjml.elements.mj-invoice-item"></a>[function <span class="apidocSignatureSpan">mjml.elements.</span>mj-invoice-item (props)](#apidoc.element.mjml.elements.mj-invoice-item)
- description and source-code
```javascript
function MJMLElement(props) {
  _classCallCheck(this, MJMLElement);

  var _this = _possibleConstructorReturn(this, (MJMLElement.__proto__ || Object.getPrototypeOf(MJMLElement)).call(this, props));

  _this.mjAttribute = function (name) {
    return _this.mjml.getIn(['attributes', name]);
  };

  _this.mjName = function () {
    return _this.constructor.tagName;
  };

  _this.mjContent = function () {
    var content = _this.mjml.get('content');

    if (content) {
      return (0, _trim2.default)(content);
    }

    return _react2.default.Children.map(_this.props.children, function (child) {
      if (typeof child === 'string') {
        return child;
      }
      return _server2.default.renderToStaticMarkup(child);
    });
  };

  _this.isInheritedAttributes = function (name) {
    return _this.mjml.get('inheritedAttributes') && _this.mjml.get('inheritedAttributes').includes(name);
  };

  _this.getWidth = function () {
    return _this.mjAttribute('rawPxWidth') || _this.mjAttribute('width');
  };

  _this.getParentWidth = function () {
    return _this.mjAttribute('parentWidth');
  };

  _this.renderWrappedOutlookChildren = function (children) {
    children = _react2.default.Children.toArray(children);

    var realChildren = children.filter(function (child) {
      return !child.props.mjml || child.props.mjml.get('tagName') !== 'mj-raw';
    });

    var prefix = _this.mjName() + '-outlook';
    var parentWidth = _this.getWidth();
    var siblings = realChildren.length;
    var elementsWidth = realChildren.map(function (element) {
      if (_this.isInheritedAttributes('width')) {
        return parseInt(parentWidth);
      }

      return getElementWidth({ element: element, siblings: siblings, parentWidth: parentWidth });
    });

    var wrappedElements = [];

    if (siblings == 0) {
      return wrappedElements;
    }

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-open', className: prefix + '-open', 'data-width':
elementsWidth[0] }));

    var i = 0;

    children.forEach(function (child) {
      var childProps = Object.assign({}, child.props);

      if (childProps.mjml) {
        childProps.mjml = childProps.mjml.setIn(['attributes', 'rawPxWidth'], elementsWidth[i]);

        if (_this.mjml.get('inheritedAttributes')) {
          childProps.mjml = childProps.mjml.mergeIn(['attributes', _this.inheritedAttributes()]);
        }
      } else {
        Object.assign(childProps, { rawPxWidth: elementsWidth[i] });

        if (_this.mjml.get('inheritedAttributes')) {
          Object.assign(childProps, _this.inheritedAttributes());
        }
      }

      var childWithProps = _react2.default.cloneElement(child, childProps);

      wrappedElements.push(childWithProps);
      if (!childWithProps.type.rawElement && i < realChildren.length - 1) {
        wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-' + i, className: prefix + '-line', 'data-width
': elementsWidth[++i] }));
      }
    });

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-close', className: prefix + '-close' }));

    return wrappedElements;
  };

  _this.paddingParser = function (direction) {
    var prefix = arguments.length > 1 && arguments[1] !== undefined ? arguments[1] : '';

    var paddingDirection = _this.mjAttribute(prefix + 'padding-' + direction);
    var padding = _this.mjAttribute(prefix + 'padding');

    if (paddingDirection != null) {
      return parseInt(paddingDirection);
    }

    if (!padding) {
      return 0;
    }

    var paddings = padding.split(' ');
    var directions = {};

    switch (paddings.length) {
      case 1:
        return parseInt(padding);
      case 2:
        directions = { top: 0, bottom: 0, left: 1, right: 1 };
        break;
      case 3:
        directions = { top: 0, left: 1, right: 1, bottom: 2 };
        break;
      case 4:
        directions = { top: 0, right: 1, bottom: 2, left: 3 };
        break;
    }

    return parseInt(paddings[directions[direction]] || 0);
  };

  _this.mjml = props.mjml || _immutable2. ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mjml.elements.mj-link"></a>[function <span class="apidocSignatureSpan">mjml.elements.</span>mj-link (props)](#apidoc.element.mjml.elements.mj-link)
- description and source-code
```javascript
function MJMLElement(props) {
  _classCallCheck(this, MJMLElement);

  var _this = _possibleConstructorReturn(this, (MJMLElement.__proto__ || Object.getPrototypeOf(MJMLElement)).call(this, props));

  _this.mjAttribute = function (name) {
    return _this.mjml.getIn(['attributes', name]);
  };

  _this.mjName = function () {
    return _this.constructor.tagName;
  };

  _this.mjContent = function () {
    var content = _this.mjml.get('content');

    if (content) {
      return (0, _trim2.default)(content);
    }

    return _react2.default.Children.map(_this.props.children, function (child) {
      if (typeof child === 'string') {
        return child;
      }
      return _server2.default.renderToStaticMarkup(child);
    });
  };

  _this.isInheritedAttributes = function (name) {
    return _this.mjml.get('inheritedAttributes') && _this.mjml.get('inheritedAttributes').includes(name);
  };

  _this.getWidth = function () {
    return _this.mjAttribute('rawPxWidth') || _this.mjAttribute('width');
  };

  _this.getParentWidth = function () {
    return _this.mjAttribute('parentWidth');
  };

  _this.renderWrappedOutlookChildren = function (children) {
    children = _react2.default.Children.toArray(children);

    var realChildren = children.filter(function (child) {
      return !child.props.mjml || child.props.mjml.get('tagName') !== 'mj-raw';
    });

    var prefix = _this.mjName() + '-outlook';
    var parentWidth = _this.getWidth();
    var siblings = realChildren.length;
    var elementsWidth = realChildren.map(function (element) {
      if (_this.isInheritedAttributes('width')) {
        return parseInt(parentWidth);
      }

      return getElementWidth({ element: element, siblings: siblings, parentWidth: parentWidth });
    });

    var wrappedElements = [];

    if (siblings == 0) {
      return wrappedElements;
    }

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-open', className: prefix + '-open', 'data-width':
elementsWidth[0] }));

    var i = 0;

    children.forEach(function (child) {
      var childProps = Object.assign({}, child.props);

      if (childProps.mjml) {
        childProps.mjml = childProps.mjml.setIn(['attributes', 'rawPxWidth'], elementsWidth[i]);

        if (_this.mjml.get('inheritedAttributes')) {
          childProps.mjml = childProps.mjml.mergeIn(['attributes', _this.inheritedAttributes()]);
        }
      } else {
        Object.assign(childProps, { rawPxWidth: elementsWidth[i] });

        if (_this.mjml.get('inheritedAttributes')) {
          Object.assign(childProps, _this.inheritedAttributes());
        }
      }

      var childWithProps = _react2.default.cloneElement(child, childProps);

      wrappedElements.push(childWithProps);
      if (!childWithProps.type.rawElement && i < realChildren.length - 1) {
        wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-' + i, className: prefix + '-line', 'data-width
': elementsWidth[++i] }));
      }
    });

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-close', className: prefix + '-close' }));

    return wrappedElements;
  };

  _this.paddingParser = function (direction) {
    var prefix = arguments.length > 1 && arguments[1] !== undefined ? arguments[1] : '';

    var paddingDirection = _this.mjAttribute(prefix + 'padding-' + direction);
    var padding = _this.mjAttribute(prefix + 'padding');

    if (paddingDirection != null) {
      return parseInt(paddingDirection);
    }

    if (!padding) {
      return 0;
    }

    var paddings = padding.split(' ');
    var directions = {};

    switch (paddings.length) {
      case 1:
        return parseInt(padding);
      case 2:
        directions = { top: 0, bottom: 0, left: 1, right: 1 };
        break;
      case 3:
        directions = { top: 0, left: 1, right: 1, bottom: 2 };
        break;
      case 4:
        directions = { top: 0, right: 1, bottom: 2, left: 3 };
        break;
    }

    return parseInt(paddings[directions[direction]] || 0);
  };

  _this.mjml = props.mjml || _immutable2. ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mjml.elements.mj-list"></a>[function <span class="apidocSignatureSpan">mjml.elements.</span>mj-list (props)](#apidoc.element.mjml.elements.mj-list)
- description and source-code
```javascript
function MJMLElement(props) {
  _classCallCheck(this, MJMLElement);

  var _this = _possibleConstructorReturn(this, (MJMLElement.__proto__ || Object.getPrototypeOf(MJMLElement)).call(this, props));

  _this.mjAttribute = function (name) {
    return _this.mjml.getIn(['attributes', name]);
  };

  _this.mjName = function () {
    return _this.constructor.tagName;
  };

  _this.mjContent = function () {
    var content = _this.mjml.get('content');

    if (content) {
      return (0, _trim2.default)(content);
    }

    return _react2.default.Children.map(_this.props.children, function (child) {
      if (typeof child === 'string') {
        return child;
      }
      return _server2.default.renderToStaticMarkup(child);
    });
  };

  _this.isInheritedAttributes = function (name) {
    return _this.mjml.get('inheritedAttributes') && _this.mjml.get('inheritedAttributes').includes(name);
  };

  _this.getWidth = function () {
    return _this.mjAttribute('rawPxWidth') || _this.mjAttribute('width');
  };

  _this.getParentWidth = function () {
    return _this.mjAttribute('parentWidth');
  };

  _this.renderWrappedOutlookChildren = function (children) {
    children = _react2.default.Children.toArray(children);

    var realChildren = children.filter(function (child) {
      return !child.props.mjml || child.props.mjml.get('tagName') !== 'mj-raw';
    });

    var prefix = _this.mjName() + '-outlook';
    var parentWidth = _this.getWidth();
    var siblings = realChildren.length;
    var elementsWidth = realChildren.map(function (element) {
      if (_this.isInheritedAttributes('width')) {
        return parseInt(parentWidth);
      }

      return getElementWidth({ element: element, siblings: siblings, parentWidth: parentWidth });
    });

    var wrappedElements = [];

    if (siblings == 0) {
      return wrappedElements;
    }

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-open', className: prefix + '-open', 'data-width':
elementsWidth[0] }));

    var i = 0;

    children.forEach(function (child) {
      var childProps = Object.assign({}, child.props);

      if (childProps.mjml) {
        childProps.mjml = childProps.mjml.setIn(['attributes', 'rawPxWidth'], elementsWidth[i]);

        if (_this.mjml.get('inheritedAttributes')) {
          childProps.mjml = childProps.mjml.mergeIn(['attributes', _this.inheritedAttributes()]);
        }
      } else {
        Object.assign(childProps, { rawPxWidth: elementsWidth[i] });

        if (_this.mjml.get('inheritedAttributes')) {
          Object.assign(childProps, _this.inheritedAttributes());
        }
      }

      var childWithProps = _react2.default.cloneElement(child, childProps);

      wrappedElements.push(childWithProps);
      if (!childWithProps.type.rawElement && i < realChildren.length - 1) {
        wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-' + i, className: prefix + '-line', 'data-width
': elementsWidth[++i] }));
      }
    });

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-close', className: prefix + '-close' }));

    return wrappedElements;
  };

  _this.paddingParser = function (direction) {
    var prefix = arguments.length > 1 && arguments[1] !== undefined ? arguments[1] : '';

    var paddingDirection = _this.mjAttribute(prefix + 'padding-' + direction);
    var padding = _this.mjAttribute(prefix + 'padding');

    if (paddingDirection != null) {
      return parseInt(paddingDirection);
    }

    if (!padding) {
      return 0;
    }

    var paddings = padding.split(' ');
    var directions = {};

    switch (paddings.length) {
      case 1:
        return parseInt(padding);
      case 2:
        directions = { top: 0, bottom: 0, left: 1, right: 1 };
        break;
      case 3:
        directions = { top: 0, left: 1, right: 1, bottom: 2 };
        break;
      case 4:
        directions = { top: 0, right: 1, bottom: 2, left: 3 };
        break;
    }

    return parseInt(paddings[directions[direction]] || 0);
  };

  _this.mjml = props.mjml || _immutable2. ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mjml.elements.mj-location"></a>[function <span class="apidocSignatureSpan">mjml.elements.</span>mj-location (props)](#apidoc.element.mjml.elements.mj-location)
- description and source-code
```javascript
function MJMLElement(props) {
  _classCallCheck(this, MJMLElement);

  var _this = _possibleConstructorReturn(this, (MJMLElement.__proto__ || Object.getPrototypeOf(MJMLElement)).call(this, props));

  _this.mjAttribute = function (name) {
    return _this.mjml.getIn(['attributes', name]);
  };

  _this.mjName = function () {
    return _this.constructor.tagName;
  };

  _this.mjContent = function () {
    var content = _this.mjml.get('content');

    if (content) {
      return (0, _trim2.default)(content);
    }

    return _react2.default.Children.map(_this.props.children, function (child) {
      if (typeof child === 'string') {
        return child;
      }
      return _server2.default.renderToStaticMarkup(child);
    });
  };

  _this.isInheritedAttributes = function (name) {
    return _this.mjml.get('inheritedAttributes') && _this.mjml.get('inheritedAttributes').includes(name);
  };

  _this.getWidth = function () {
    return _this.mjAttribute('rawPxWidth') || _this.mjAttribute('width');
  };

  _this.getParentWidth = function () {
    return _this.mjAttribute('parentWidth');
  };

  _this.renderWrappedOutlookChildren = function (children) {
    children = _react2.default.Children.toArray(children);

    var realChildren = children.filter(function (child) {
      return !child.props.mjml || child.props.mjml.get('tagName') !== 'mj-raw';
    });

    var prefix = _this.mjName() + '-outlook';
    var parentWidth = _this.getWidth();
    var siblings = realChildren.length;
    var elementsWidth = realChildren.map(function (element) {
      if (_this.isInheritedAttributes('width')) {
        return parseInt(parentWidth);
      }

      return getElementWidth({ element: element, siblings: siblings, parentWidth: parentWidth });
    });

    var wrappedElements = [];

    if (siblings == 0) {
      return wrappedElements;
    }

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-open', className: prefix + '-open', 'data-width':
elementsWidth[0] }));

    var i = 0;

    children.forEach(function (child) {
      var childProps = Object.assign({}, child.props);

      if (childProps.mjml) {
        childProps.mjml = childProps.mjml.setIn(['attributes', 'rawPxWidth'], elementsWidth[i]);

        if (_this.mjml.get('inheritedAttributes')) {
          childProps.mjml = childProps.mjml.mergeIn(['attributes', _this.inheritedAttributes()]);
        }
      } else {
        Object.assign(childProps, { rawPxWidth: elementsWidth[i] });

        if (_this.mjml.get('inheritedAttributes')) {
          Object.assign(childProps, _this.inheritedAttributes());
        }
      }

      var childWithProps = _react2.default.cloneElement(child, childProps);

      wrappedElements.push(childWithProps);
      if (!childWithProps.type.rawElement && i < realChildren.length - 1) {
        wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-' + i, className: prefix + '-line', 'data-width
': elementsWidth[++i] }));
      }
    });

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-close', className: prefix + '-close' }));

    return wrappedElements;
  };

  _this.paddingParser = function (direction) {
    var prefix = arguments.length > 1 && arguments[1] !== undefined ? arguments[1] : '';

    var paddingDirection = _this.mjAttribute(prefix + 'padding-' + direction);
    var padding = _this.mjAttribute(prefix + 'padding');

    if (paddingDirection != null) {
      return parseInt(paddingDirection);
    }

    if (!padding) {
      return 0;
    }

    var paddings = padding.split(' ');
    var directions = {};

    switch (paddings.length) {
      case 1:
        return parseInt(padding);
      case 2:
        directions = { top: 0, bottom: 0, left: 1, right: 1 };
        break;
      case 3:
        directions = { top: 0, left: 1, right: 1, bottom: 2 };
        break;
      case 4:
        directions = { top: 0, right: 1, bottom: 2, left: 3 };
        break;
    }

    return parseInt(paddings[directions[direction]] || 0);
  };

  _this.mjml = props.mjml || _immutable2. ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mjml.elements.mj-navbar"></a>[function <span class="apidocSignatureSpan">mjml.elements.</span>mj-navbar (props)](#apidoc.element.mjml.elements.mj-navbar)
- description and source-code
```javascript
function MJMLElement(props) {
  _classCallCheck(this, MJMLElement);

  var _this = _possibleConstructorReturn(this, (MJMLElement.__proto__ || Object.getPrototypeOf(MJMLElement)).call(this, props));

  _this.mjAttribute = function (name) {
    return _this.mjml.getIn(['attributes', name]);
  };

  _this.mjName = function () {
    return _this.constructor.tagName;
  };

  _this.mjContent = function () {
    var content = _this.mjml.get('content');

    if (content) {
      return (0, _trim2.default)(content);
    }

    return _react2.default.Children.map(_this.props.children, function (child) {
      if (typeof child === 'string') {
        return child;
      }
      return _server2.default.renderToStaticMarkup(child);
    });
  };

  _this.isInheritedAttributes = function (name) {
    return _this.mjml.get('inheritedAttributes') && _this.mjml.get('inheritedAttributes').includes(name);
  };

  _this.getWidth = function () {
    return _this.mjAttribute('rawPxWidth') || _this.mjAttribute('width');
  };

  _this.getParentWidth = function () {
    return _this.mjAttribute('parentWidth');
  };

  _this.renderWrappedOutlookChildren = function (children) {
    children = _react2.default.Children.toArray(children);

    var realChildren = children.filter(function (child) {
      return !child.props.mjml || child.props.mjml.get('tagName') !== 'mj-raw';
    });

    var prefix = _this.mjName() + '-outlook';
    var parentWidth = _this.getWidth();
    var siblings = realChildren.length;
    var elementsWidth = realChildren.map(function (element) {
      if (_this.isInheritedAttributes('width')) {
        return parseInt(parentWidth);
      }

      return getElementWidth({ element: element, siblings: siblings, parentWidth: parentWidth });
    });

    var wrappedElements = [];

    if (siblings == 0) {
      return wrappedElements;
    }

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-open', className: prefix + '-open', 'data-width':
elementsWidth[0] }));

    var i = 0;

    children.forEach(function (child) {
      var childProps = Object.assign({}, child.props);

      if (childProps.mjml) {
        childProps.mjml = childProps.mjml.setIn(['attributes', 'rawPxWidth'], elementsWidth[i]);

        if (_this.mjml.get('inheritedAttributes')) {
          childProps.mjml = childProps.mjml.mergeIn(['attributes', _this.inheritedAttributes()]);
        }
      } else {
        Object.assign(childProps, { rawPxWidth: elementsWidth[i] });

        if (_this.mjml.get('inheritedAttributes')) {
          Object.assign(childProps, _this.inheritedAttributes());
        }
      }

      var childWithProps = _react2.default.cloneElement(child, childProps);

      wrappedElements.push(childWithProps);
      if (!childWithProps.type.rawElement && i < realChildren.length - 1) {
        wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-' + i, className: prefix + '-line', 'data-width
': elementsWidth[++i] }));
      }
    });

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-close', className: prefix + '-close' }));

    return wrappedElements;
  };

  _this.paddingParser = function (direction) {
    var prefix = arguments.length > 1 && arguments[1] !== undefined ? arguments[1] : '';

    var paddingDirection = _this.mjAttribute(prefix + 'padding-' + direction);
    var padding = _this.mjAttribute(prefix + 'padding');

    if (paddingDirection != null) {
      return parseInt(paddingDirection);
    }

    if (!padding) {
      return 0;
    }

    var paddings = padding.split(' ');
    var directions = {};

    switch (paddings.length) {
      case 1:
        return parseInt(padding);
      case 2:
        directions = { top: 0, bottom: 0, left: 1, right: 1 };
        break;
      case 3:
        directions = { top: 0, left: 1, right: 1, bottom: 2 };
        break;
      case 4:
        directions = { top: 0, right: 1, bottom: 2, left: 3 };
        break;
    }

    return parseInt(paddings[directions[direction]] || 0);
  };

  _this.mjml = props.mjml || _immutable2. ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mjml.elements.mj-raw"></a>[function <span class="apidocSignatureSpan">mjml.elements.</span>mj-raw (props)](#apidoc.element.mjml.elements.mj-raw)
- description and source-code
```javascript
function MJMLElement(props) {
  _classCallCheck(this, MJMLElement);

  var _this = _possibleConstructorReturn(this, (MJMLElement.__proto__ || Object.getPrototypeOf(MJMLElement)).call(this, props));

  _this.mjAttribute = function (name) {
    return _this.mjml.getIn(['attributes', name]);
  };

  _this.mjName = function () {
    return _this.constructor.tagName;
  };

  _this.mjContent = function () {
    var content = _this.mjml.get('content');

    if (content) {
      return (0, _trim2.default)(content);
    }

    return _react2.default.Children.map(_this.props.children, function (child) {
      if (typeof child === 'string') {
        return child;
      }
      return _server2.default.renderToStaticMarkup(child);
    });
  };

  _this.isInheritedAttributes = function (name) {
    return _this.mjml.get('inheritedAttributes') && _this.mjml.get('inheritedAttributes').includes(name);
  };

  _this.getWidth = function () {
    return _this.mjAttribute('rawPxWidth') || _this.mjAttribute('width');
  };

  _this.getParentWidth = function () {
    return _this.mjAttribute('parentWidth');
  };

  _this.renderWrappedOutlookChildren = function (children) {
    children = _react2.default.Children.toArray(children);

    var realChildren = children.filter(function (child) {
      return !child.props.mjml || child.props.mjml.get('tagName') !== 'mj-raw';
    });

    var prefix = _this.mjName() + '-outlook';
    var parentWidth = _this.getWidth();
    var siblings = realChildren.length;
    var elementsWidth = realChildren.map(function (element) {
      if (_this.isInheritedAttributes('width')) {
        return parseInt(parentWidth);
      }

      return getElementWidth({ element: element, siblings: siblings, parentWidth: parentWidth });
    });

    var wrappedElements = [];

    if (siblings == 0) {
      return wrappedElements;
    }

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-open', className: prefix + '-open', 'data-width':
elementsWidth[0] }));

    var i = 0;

    children.forEach(function (child) {
      var childProps = Object.assign({}, child.props);

      if (childProps.mjml) {
        childProps.mjml = childProps.mjml.setIn(['attributes', 'rawPxWidth'], elementsWidth[i]);

        if (_this.mjml.get('inheritedAttributes')) {
          childProps.mjml = childProps.mjml.mergeIn(['attributes', _this.inheritedAttributes()]);
        }
      } else {
        Object.assign(childProps, { rawPxWidth: elementsWidth[i] });

        if (_this.mjml.get('inheritedAttributes')) {
          Object.assign(childProps, _this.inheritedAttributes());
        }
      }

      var childWithProps = _react2.default.cloneElement(child, childProps);

      wrappedElements.push(childWithProps);
      if (!childWithProps.type.rawElement && i < realChildren.length - 1) {
        wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-' + i, className: prefix + '-line', 'data-width
': elementsWidth[++i] }));
      }
    });

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-close', className: prefix + '-close' }));

    return wrappedElements;
  };

  _this.paddingParser = function (direction) {
    var prefix = arguments.length > 1 && arguments[1] !== undefined ? arguments[1] : '';

    var paddingDirection = _this.mjAttribute(prefix + 'padding-' + direction);
    var padding = _this.mjAttribute(prefix + 'padding');

    if (paddingDirection != null) {
      return parseInt(paddingDirection);
    }

    if (!padding) {
      return 0;
    }

    var paddings = padding.split(' ');
    var directions = {};

    switch (paddings.length) {
      case 1:
        return parseInt(padding);
      case 2:
        directions = { top: 0, bottom: 0, left: 1, right: 1 };
        break;
      case 3:
        directions = { top: 0, left: 1, right: 1, bottom: 2 };
        break;
      case 4:
        directions = { top: 0, right: 1, bottom: 2, left: 3 };
        break;
    }

    return parseInt(paddings[directions[direction]] || 0);
  };

  _this.mjml = props.mjml || _immutable2. ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mjml.elements.mj-section"></a>[function <span class="apidocSignatureSpan">mjml.elements.</span>mj-section (props)](#apidoc.element.mjml.elements.mj-section)
- description and source-code
```javascript
function MJMLElement(props) {
  _classCallCheck(this, MJMLElement);

  var _this = _possibleConstructorReturn(this, (MJMLElement.__proto__ || Object.getPrototypeOf(MJMLElement)).call(this, props));

  _this.mjAttribute = function (name) {
    return _this.mjml.getIn(['attributes', name]);
  };

  _this.mjName = function () {
    return _this.constructor.tagName;
  };

  _this.mjContent = function () {
    var content = _this.mjml.get('content');

    if (content) {
      return (0, _trim2.default)(content);
    }

    return _react2.default.Children.map(_this.props.children, function (child) {
      if (typeof child === 'string') {
        return child;
      }
      return _server2.default.renderToStaticMarkup(child);
    });
  };

  _this.isInheritedAttributes = function (name) {
    return _this.mjml.get('inheritedAttributes') && _this.mjml.get('inheritedAttributes').includes(name);
  };

  _this.getWidth = function () {
    return _this.mjAttribute('rawPxWidth') || _this.mjAttribute('width');
  };

  _this.getParentWidth = function () {
    return _this.mjAttribute('parentWidth');
  };

  _this.renderWrappedOutlookChildren = function (children) {
    children = _react2.default.Children.toArray(children);

    var realChildren = children.filter(function (child) {
      return !child.props.mjml || child.props.mjml.get('tagName') !== 'mj-raw';
    });

    var prefix = _this.mjName() + '-outlook';
    var parentWidth = _this.getWidth();
    var siblings = realChildren.length;
    var elementsWidth = realChildren.map(function (element) {
      if (_this.isInheritedAttributes('width')) {
        return parseInt(parentWidth);
      }

      return getElementWidth({ element: element, siblings: siblings, parentWidth: parentWidth });
    });

    var wrappedElements = [];

    if (siblings == 0) {
      return wrappedElements;
    }

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-open', className: prefix + '-open', 'data-width':
elementsWidth[0] }));

    var i = 0;

    children.forEach(function (child) {
      var childProps = Object.assign({}, child.props);

      if (childProps.mjml) {
        childProps.mjml = childProps.mjml.setIn(['attributes', 'rawPxWidth'], elementsWidth[i]);

        if (_this.mjml.get('inheritedAttributes')) {
          childProps.mjml = childProps.mjml.mergeIn(['attributes', _this.inheritedAttributes()]);
        }
      } else {
        Object.assign(childProps, { rawPxWidth: elementsWidth[i] });

        if (_this.mjml.get('inheritedAttributes')) {
          Object.assign(childProps, _this.inheritedAttributes());
        }
      }

      var childWithProps = _react2.default.cloneElement(child, childProps);

      wrappedElements.push(childWithProps);
      if (!childWithProps.type.rawElement && i < realChildren.length - 1) {
        wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-' + i, className: prefix + '-line', 'data-width
': elementsWidth[++i] }));
      }
    });

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-close', className: prefix + '-close' }));

    return wrappedElements;
  };

  _this.paddingParser = function (direction) {
    var prefix = arguments.length > 1 && arguments[1] !== undefined ? arguments[1] : '';

    var paddingDirection = _this.mjAttribute(prefix + 'padding-' + direction);
    var padding = _this.mjAttribute(prefix + 'padding');

    if (paddingDirection != null) {
      return parseInt(paddingDirection);
    }

    if (!padding) {
      return 0;
    }

    var paddings = padding.split(' ');
    var directions = {};

    switch (paddings.length) {
      case 1:
        return parseInt(padding);
      case 2:
        directions = { top: 0, bottom: 0, left: 1, right: 1 };
        break;
      case 3:
        directions = { top: 0, left: 1, right: 1, bottom: 2 };
        break;
      case 4:
        directions = { top: 0, right: 1, bottom: 2, left: 3 };
        break;
    }

    return parseInt(paddings[directions[direction]] || 0);
  };

  _this.mjml = props.mjml || _immutable2. ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mjml.elements.mj-social"></a>[function <span class="apidocSignatureSpan">mjml.elements.</span>mj-social (props)](#apidoc.element.mjml.elements.mj-social)
- description and source-code
```javascript
function MJMLElement(props) {
  _classCallCheck(this, MJMLElement);

  var _this = _possibleConstructorReturn(this, (MJMLElement.__proto__ || Object.getPrototypeOf(MJMLElement)).call(this, props));

  _this.mjAttribute = function (name) {
    return _this.mjml.getIn(['attributes', name]);
  };

  _this.mjName = function () {
    return _this.constructor.tagName;
  };

  _this.mjContent = function () {
    var content = _this.mjml.get('content');

    if (content) {
      return (0, _trim2.default)(content);
    }

    return _react2.default.Children.map(_this.props.children, function (child) {
      if (typeof child === 'string') {
        return child;
      }
      return _server2.default.renderToStaticMarkup(child);
    });
  };

  _this.isInheritedAttributes = function (name) {
    return _this.mjml.get('inheritedAttributes') && _this.mjml.get('inheritedAttributes').includes(name);
  };

  _this.getWidth = function () {
    return _this.mjAttribute('rawPxWidth') || _this.mjAttribute('width');
  };

  _this.getParentWidth = function () {
    return _this.mjAttribute('parentWidth');
  };

  _this.renderWrappedOutlookChildren = function (children) {
    children = _react2.default.Children.toArray(children);

    var realChildren = children.filter(function (child) {
      return !child.props.mjml || child.props.mjml.get('tagName') !== 'mj-raw';
    });

    var prefix = _this.mjName() + '-outlook';
    var parentWidth = _this.getWidth();
    var siblings = realChildren.length;
    var elementsWidth = realChildren.map(function (element) {
      if (_this.isInheritedAttributes('width')) {
        return parseInt(parentWidth);
      }

      return getElementWidth({ element: element, siblings: siblings, parentWidth: parentWidth });
    });

    var wrappedElements = [];

    if (siblings == 0) {
      return wrappedElements;
    }

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-open', className: prefix + '-open', 'data-width':
elementsWidth[0] }));

    var i = 0;

    children.forEach(function (child) {
      var childProps = Object.assign({}, child.props);

      if (childProps.mjml) {
        childProps.mjml = childProps.mjml.setIn(['attributes', 'rawPxWidth'], elementsWidth[i]);

        if (_this.mjml.get('inheritedAttributes')) {
          childProps.mjml = childProps.mjml.mergeIn(['attributes', _this.inheritedAttributes()]);
        }
      } else {
        Object.assign(childProps, { rawPxWidth: elementsWidth[i] });

        if (_this.mjml.get('inheritedAttributes')) {
          Object.assign(childProps, _this.inheritedAttributes());
        }
      }

      var childWithProps = _react2.default.cloneElement(child, childProps);

      wrappedElements.push(childWithProps);
      if (!childWithProps.type.rawElement && i < realChildren.length - 1) {
        wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-' + i, className: prefix + '-line', 'data-width
': elementsWidth[++i] }));
      }
    });

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-close', className: prefix + '-close' }));

    return wrappedElements;
  };

  _this.paddingParser = function (direction) {
    var prefix = arguments.length > 1 && arguments[1] !== undefined ? arguments[1] : '';

    var paddingDirection = _this.mjAttribute(prefix + 'padding-' + direction);
    var padding = _this.mjAttribute(prefix + 'padding');

    if (paddingDirection != null) {
      return parseInt(paddingDirection);
    }

    if (!padding) {
      return 0;
    }

    var paddings = padding.split(' ');
    var directions = {};

    switch (paddings.length) {
      case 1:
        return parseInt(padding);
      case 2:
        directions = { top: 0, bottom: 0, left: 1, right: 1 };
        break;
      case 3:
        directions = { top: 0, left: 1, right: 1, bottom: 2 };
        break;
      case 4:
        directions = { top: 0, right: 1, bottom: 2, left: 3 };
        break;
    }

    return parseInt(paddings[directions[direction]] || 0);
  };

  _this.mjml = props.mjml || _immutable2. ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mjml.elements.mj-spacer"></a>[function <span class="apidocSignatureSpan">mjml.elements.</span>mj-spacer (props)](#apidoc.element.mjml.elements.mj-spacer)
- description and source-code
```javascript
function MJMLElement(props) {
  _classCallCheck(this, MJMLElement);

  var _this = _possibleConstructorReturn(this, (MJMLElement.__proto__ || Object.getPrototypeOf(MJMLElement)).call(this, props));

  _this.mjAttribute = function (name) {
    return _this.mjml.getIn(['attributes', name]);
  };

  _this.mjName = function () {
    return _this.constructor.tagName;
  };

  _this.mjContent = function () {
    var content = _this.mjml.get('content');

    if (content) {
      return (0, _trim2.default)(content);
    }

    return _react2.default.Children.map(_this.props.children, function (child) {
      if (typeof child === 'string') {
        return child;
      }
      return _server2.default.renderToStaticMarkup(child);
    });
  };

  _this.isInheritedAttributes = function (name) {
    return _this.mjml.get('inheritedAttributes') && _this.mjml.get('inheritedAttributes').includes(name);
  };

  _this.getWidth = function () {
    return _this.mjAttribute('rawPxWidth') || _this.mjAttribute('width');
  };

  _this.getParentWidth = function () {
    return _this.mjAttribute('parentWidth');
  };

  _this.renderWrappedOutlookChildren = function (children) {
    children = _react2.default.Children.toArray(children);

    var realChildren = children.filter(function (child) {
      return !child.props.mjml || child.props.mjml.get('tagName') !== 'mj-raw';
    });

    var prefix = _this.mjName() + '-outlook';
    var parentWidth = _this.getWidth();
    var siblings = realChildren.length;
    var elementsWidth = realChildren.map(function (element) {
      if (_this.isInheritedAttributes('width')) {
        return parseInt(parentWidth);
      }

      return getElementWidth({ element: element, siblings: siblings, parentWidth: parentWidth });
    });

    var wrappedElements = [];

    if (siblings == 0) {
      return wrappedElements;
    }

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-open', className: prefix + '-open', 'data-width':
elementsWidth[0] }));

    var i = 0;

    children.forEach(function (child) {
      var childProps = Object.assign({}, child.props);

      if (childProps.mjml) {
        childProps.mjml = childProps.mjml.setIn(['attributes', 'rawPxWidth'], elementsWidth[i]);

        if (_this.mjml.get('inheritedAttributes')) {
          childProps.mjml = childProps.mjml.mergeIn(['attributes', _this.inheritedAttributes()]);
        }
      } else {
        Object.assign(childProps, { rawPxWidth: elementsWidth[i] });

        if (_this.mjml.get('inheritedAttributes')) {
          Object.assign(childProps, _this.inheritedAttributes());
        }
      }

      var childWithProps = _react2.default.cloneElement(child, childProps);

      wrappedElements.push(childWithProps);
      if (!childWithProps.type.rawElement && i < realChildren.length - 1) {
        wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-' + i, className: prefix + '-line', 'data-width
': elementsWidth[++i] }));
      }
    });

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-close', className: prefix + '-close' }));

    return wrappedElements;
  };

  _this.paddingParser = function (direction) {
    var prefix = arguments.length > 1 && arguments[1] !== undefined ? arguments[1] : '';

    var paddingDirection = _this.mjAttribute(prefix + 'padding-' + direction);
    var padding = _this.mjAttribute(prefix + 'padding');

    if (paddingDirection != null) {
      return parseInt(paddingDirection);
    }

    if (!padding) {
      return 0;
    }

    var paddings = padding.split(' ');
    var directions = {};

    switch (paddings.length) {
      case 1:
        return parseInt(padding);
      case 2:
        directions = { top: 0, bottom: 0, left: 1, right: 1 };
        break;
      case 3:
        directions = { top: 0, left: 1, right: 1, bottom: 2 };
        break;
      case 4:
        directions = { top: 0, right: 1, bottom: 2, left: 3 };
        break;
    }

    return parseInt(paddings[directions[direction]] || 0);
  };

  _this.mjml = props.mjml || _immutable2. ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mjml.elements.mj-table"></a>[function <span class="apidocSignatureSpan">mjml.elements.</span>mj-table (props)](#apidoc.element.mjml.elements.mj-table)
- description and source-code
```javascript
function MJMLElement(props) {
  _classCallCheck(this, MJMLElement);

  var _this = _possibleConstructorReturn(this, (MJMLElement.__proto__ || Object.getPrototypeOf(MJMLElement)).call(this, props));

  _this.mjAttribute = function (name) {
    return _this.mjml.getIn(['attributes', name]);
  };

  _this.mjName = function () {
    return _this.constructor.tagName;
  };

  _this.mjContent = function () {
    var content = _this.mjml.get('content');

    if (content) {
      return (0, _trim2.default)(content);
    }

    return _react2.default.Children.map(_this.props.children, function (child) {
      if (typeof child === 'string') {
        return child;
      }
      return _server2.default.renderToStaticMarkup(child);
    });
  };

  _this.isInheritedAttributes = function (name) {
    return _this.mjml.get('inheritedAttributes') && _this.mjml.get('inheritedAttributes').includes(name);
  };

  _this.getWidth = function () {
    return _this.mjAttribute('rawPxWidth') || _this.mjAttribute('width');
  };

  _this.getParentWidth = function () {
    return _this.mjAttribute('parentWidth');
  };

  _this.renderWrappedOutlookChildren = function (children) {
    children = _react2.default.Children.toArray(children);

    var realChildren = children.filter(function (child) {
      return !child.props.mjml || child.props.mjml.get('tagName') !== 'mj-raw';
    });

    var prefix = _this.mjName() + '-outlook';
    var parentWidth = _this.getWidth();
    var siblings = realChildren.length;
    var elementsWidth = realChildren.map(function (element) {
      if (_this.isInheritedAttributes('width')) {
        return parseInt(parentWidth);
      }

      return getElementWidth({ element: element, siblings: siblings, parentWidth: parentWidth });
    });

    var wrappedElements = [];

    if (siblings == 0) {
      return wrappedElements;
    }

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-open', className: prefix + '-open', 'data-width':
elementsWidth[0] }));

    var i = 0;

    children.forEach(function (child) {
      var childProps = Object.assign({}, child.props);

      if (childProps.mjml) {
        childProps.mjml = childProps.mjml.setIn(['attributes', 'rawPxWidth'], elementsWidth[i]);

        if (_this.mjml.get('inheritedAttributes')) {
          childProps.mjml = childProps.mjml.mergeIn(['attributes', _this.inheritedAttributes()]);
        }
      } else {
        Object.assign(childProps, { rawPxWidth: elementsWidth[i] });

        if (_this.mjml.get('inheritedAttributes')) {
          Object.assign(childProps, _this.inheritedAttributes());
        }
      }

      var childWithProps = _react2.default.cloneElement(child, childProps);

      wrappedElements.push(childWithProps);
      if (!childWithProps.type.rawElement && i < realChildren.length - 1) {
        wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-' + i, className: prefix + '-line', 'data-width
': elementsWidth[++i] }));
      }
    });

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-close', className: prefix + '-close' }));

    return wrappedElements;
  };

  _this.paddingParser = function (direction) {
    var prefix = arguments.length > 1 && arguments[1] !== undefined ? arguments[1] : '';

    var paddingDirection = _this.mjAttribute(prefix + 'padding-' + direction);
    var padding = _this.mjAttribute(prefix + 'padding');

    if (paddingDirection != null) {
      return parseInt(paddingDirection);
    }

    if (!padding) {
      return 0;
    }

    var paddings = padding.split(' ');
    var directions = {};

    switch (paddings.length) {
      case 1:
        return parseInt(padding);
      case 2:
        directions = { top: 0, bottom: 0, left: 1, right: 1 };
        break;
      case 3:
        directions = { top: 0, left: 1, right: 1, bottom: 2 };
        break;
      case 4:
        directions = { top: 0, right: 1, bottom: 2, left: 3 };
        break;
    }

    return parseInt(paddings[directions[direction]] || 0);
  };

  _this.mjml = props.mjml || _immutable2. ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mjml.elements.mj-text"></a>[function <span class="apidocSignatureSpan">mjml.elements.</span>mj-text (props)](#apidoc.element.mjml.elements.mj-text)
- description and source-code
```javascript
function MJMLElement(props) {
  _classCallCheck(this, MJMLElement);

  var _this = _possibleConstructorReturn(this, (MJMLElement.__proto__ || Object.getPrototypeOf(MJMLElement)).call(this, props));

  _this.mjAttribute = function (name) {
    return _this.mjml.getIn(['attributes', name]);
  };

  _this.mjName = function () {
    return _this.constructor.tagName;
  };

  _this.mjContent = function () {
    var content = _this.mjml.get('content');

    if (content) {
      return (0, _trim2.default)(content);
    }

    return _react2.default.Children.map(_this.props.children, function (child) {
      if (typeof child === 'string') {
        return child;
      }
      return _server2.default.renderToStaticMarkup(child);
    });
  };

  _this.isInheritedAttributes = function (name) {
    return _this.mjml.get('inheritedAttributes') && _this.mjml.get('inheritedAttributes').includes(name);
  };

  _this.getWidth = function () {
    return _this.mjAttribute('rawPxWidth') || _this.mjAttribute('width');
  };

  _this.getParentWidth = function () {
    return _this.mjAttribute('parentWidth');
  };

  _this.renderWrappedOutlookChildren = function (children) {
    children = _react2.default.Children.toArray(children);

    var realChildren = children.filter(function (child) {
      return !child.props.mjml || child.props.mjml.get('tagName') !== 'mj-raw';
    });

    var prefix = _this.mjName() + '-outlook';
    var parentWidth = _this.getWidth();
    var siblings = realChildren.length;
    var elementsWidth = realChildren.map(function (element) {
      if (_this.isInheritedAttributes('width')) {
        return parseInt(parentWidth);
      }

      return getElementWidth({ element: element, siblings: siblings, parentWidth: parentWidth });
    });

    var wrappedElements = [];

    if (siblings == 0) {
      return wrappedElements;
    }

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-open', className: prefix + '-open', 'data-width':
elementsWidth[0] }));

    var i = 0;

    children.forEach(function (child) {
      var childProps = Object.assign({}, child.props);

      if (childProps.mjml) {
        childProps.mjml = childProps.mjml.setIn(['attributes', 'rawPxWidth'], elementsWidth[i]);

        if (_this.mjml.get('inheritedAttributes')) {
          childProps.mjml = childProps.mjml.mergeIn(['attributes', _this.inheritedAttributes()]);
        }
      } else {
        Object.assign(childProps, { rawPxWidth: elementsWidth[i] });

        if (_this.mjml.get('inheritedAttributes')) {
          Object.assign(childProps, _this.inheritedAttributes());
        }
      }

      var childWithProps = _react2.default.cloneElement(child, childProps);

      wrappedElements.push(childWithProps);
      if (!childWithProps.type.rawElement && i < realChildren.length - 1) {
        wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-' + i, className: prefix + '-line', 'data-width
': elementsWidth[++i] }));
      }
    });

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-close', className: prefix + '-close' }));

    return wrappedElements;
  };

  _this.paddingParser = function (direction) {
    var prefix = arguments.length > 1 && arguments[1] !== undefined ? arguments[1] : '';

    var paddingDirection = _this.mjAttribute(prefix + 'padding-' + direction);
    var padding = _this.mjAttribute(prefix + 'padding');

    if (paddingDirection != null) {
      return parseInt(paddingDirection);
    }

    if (!padding) {
      return 0;
    }

    var paddings = padding.split(' ');
    var directions = {};

    switch (paddings.length) {
      case 1:
        return parseInt(padding);
      case 2:
        directions = { top: 0, bottom: 0, left: 1, right: 1 };
        break;
      case 3:
        directions = { top: 0, left: 1, right: 1, bottom: 2 };
        break;
      case 4:
        directions = { top: 0, right: 1, bottom: 2, left: 3 };
        break;
    }

    return parseInt(paddings[directions[direction]] || 0);
  };

  _this.mjml = props.mjml || _immutable2. ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mjml.elements.mj-wrapper"></a>[function <span class="apidocSignatureSpan">mjml.elements.</span>mj-wrapper ()](#apidoc.element.mjml.elements.mj-wrapper)
- description and source-code
```javascript
function Wrapper() {
  _classCallCheck(this, Wrapper);

  return _possibleConstructorReturn(this, (Wrapper.__proto__ || Object.getPrototypeOf(Wrapper)).apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mjml.elements.mj-accordion"></a>[module mjml.elements.mj-accordion](#apidoc.module.mjml.elements.mj-accordion)

#### <a name="apidoc.element.mjml.elements.mj-accordion.mj-accordion"></a>[function <span class="apidocSignatureSpan">mjml.elements.</span>mj-accordion (props)](#apidoc.element.mjml.elements.mj-accordion.mj-accordion)
- description and source-code
```javascript
function MJMLElement(props) {
  _classCallCheck(this, MJMLElement);

  var _this = _possibleConstructorReturn(this, (MJMLElement.__proto__ || Object.getPrototypeOf(MJMLElement)).call(this, props));

  _this.mjAttribute = function (name) {
    return _this.mjml.getIn(['attributes', name]);
  };

  _this.mjName = function () {
    return _this.constructor.tagName;
  };

  _this.mjContent = function () {
    var content = _this.mjml.get('content');

    if (content) {
      return (0, _trim2.default)(content);
    }

    return _react2.default.Children.map(_this.props.children, function (child) {
      if (typeof child === 'string') {
        return child;
      }
      return _server2.default.renderToStaticMarkup(child);
    });
  };

  _this.isInheritedAttributes = function (name) {
    return _this.mjml.get('inheritedAttributes') && _this.mjml.get('inheritedAttributes').includes(name);
  };

  _this.getWidth = function () {
    return _this.mjAttribute('rawPxWidth') || _this.mjAttribute('width');
  };

  _this.getParentWidth = function () {
    return _this.mjAttribute('parentWidth');
  };

  _this.renderWrappedOutlookChildren = function (children) {
    children = _react2.default.Children.toArray(children);

    var realChildren = children.filter(function (child) {
      return !child.props.mjml || child.props.mjml.get('tagName') !== 'mj-raw';
    });

    var prefix = _this.mjName() + '-outlook';
    var parentWidth = _this.getWidth();
    var siblings = realChildren.length;
    var elementsWidth = realChildren.map(function (element) {
      if (_this.isInheritedAttributes('width')) {
        return parseInt(parentWidth);
      }

      return getElementWidth({ element: element, siblings: siblings, parentWidth: parentWidth });
    });

    var wrappedElements = [];

    if (siblings == 0) {
      return wrappedElements;
    }

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-open', className: prefix + '-open', 'data-width':
elementsWidth[0] }));

    var i = 0;

    children.forEach(function (child) {
      var childProps = Object.assign({}, child.props);

      if (childProps.mjml) {
        childProps.mjml = childProps.mjml.setIn(['attributes', 'rawPxWidth'], elementsWidth[i]);

        if (_this.mjml.get('inheritedAttributes')) {
          childProps.mjml = childProps.mjml.mergeIn(['attributes', _this.inheritedAttributes()]);
        }
      } else {
        Object.assign(childProps, { rawPxWidth: elementsWidth[i] });

        if (_this.mjml.get('inheritedAttributes')) {
          Object.assign(childProps, _this.inheritedAttributes());
        }
      }

      var childWithProps = _react2.default.cloneElement(child, childProps);

      wrappedElements.push(childWithProps);
      if (!childWithProps.type.rawElement && i < realChildren.length - 1) {
        wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-' + i, className: prefix + '-line', 'data-width
': elementsWidth[++i] }));
      }
    });

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-close', className: prefix + '-close' }));

    return wrappedElements;
  };

  _this.paddingParser = function (direction) {
    var prefix = arguments.length > 1 && arguments[1] !== undefined ? arguments[1] : '';

    var paddingDirection = _this.mjAttribute(prefix + 'padding-' + direction);
    var padding = _this.mjAttribute(prefix + 'padding');

    if (paddingDirection != null) {
      return parseInt(paddingDirection);
    }

    if (!padding) {
      return 0;
    }

    var paddings = padding.split(' ');
    var directions = {};

    switch (paddings.length) {
      case 1:
        return parseInt(padding);
      case 2:
        directions = { top: 0, bottom: 0, left: 1, right: 1 };
        break;
      case 3:
        directions = { top: 0, left: 1, right: 1, bottom: 2 };
        break;
      case 4:
        directions = { top: 0, right: 1, bottom: 2, left: 3 };
        break;
    }

    return parseInt(paddings[directions[direction]] || 0);
  };

  _this.mjml = props.mjml || _immutable2. ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mjml.elements.mj-accordion.postRender"></a>[function <span class="apidocSignatureSpan">mjml.elements.mj-accordion.</span>postRender ($)](#apidoc.element.mjml.elements.mj-accordion.postRender)
- description and source-code
```javascript
function postRender($) {
  if ($('.mj-accordion').length == 0) {
    return $;
  }

  $('<!--[if !mso | IE]><!-->').insertBefore($('.mj-accordion-ico, .mj-accordion-checkbox'));
  $('<!--<![endif]-->').insertAfter($('.mj-accordion-ico, .mj-accordion-checkbox'));

  $('head').append('\n    <style type="text/css" id="mj-accordion-css">\n      noinput.mj-accordion-checkbox { display:block!important
; }\n\n      @media yahoo, only screen and (min-width:0) {\n        .mj-accordion-element { display:block; }\n        input.mj-accordion-checkbox, .mj-accordion-less { display:none!important; }\n        input.mj-accordion-checkbox + * .mj-accordion-title { cursor:pointer; touch-action:manipulation; -webkit-user-select:none; -moz-user-select:none; user-select:none; }\n        input.mj-accordion-checkbox + * .mj-accordion-content { overflow:hidden; display:none; }\n        input.mj-accordion-checkbox + * .mj-accordion-more { display:block!important; }\n        input.mj-accordion-checkbox:checked + * .mj-accordion-content { display:block; }\n        input.mj-accordion-checkbox:checked + * .mj-accordion-more { display:none!important; }\n        input.mj-accordion-checkbox:checked + * .mj-accordion-less { display:block!important; }\n      }\n\n      @goodbye { @gmail }\n    </style>\n  ');

  return $;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mjml.elements.mj-carousel"></a>[module mjml.elements.mj-carousel](#apidoc.module.mjml.elements.mj-carousel)

#### <a name="apidoc.element.mjml.elements.mj-carousel.mj-carousel"></a>[function <span class="apidocSignatureSpan">mjml.elements.</span>mj-carousel (props)](#apidoc.element.mjml.elements.mj-carousel.mj-carousel)
- description and source-code
```javascript
function MJMLElement(props) {
  _classCallCheck(this, MJMLElement);

  var _this = _possibleConstructorReturn(this, (MJMLElement.__proto__ || Object.getPrototypeOf(MJMLElement)).call(this, props));

  _this.mjAttribute = function (name) {
    return _this.mjml.getIn(['attributes', name]);
  };

  _this.mjName = function () {
    return _this.constructor.tagName;
  };

  _this.mjContent = function () {
    var content = _this.mjml.get('content');

    if (content) {
      return (0, _trim2.default)(content);
    }

    return _react2.default.Children.map(_this.props.children, function (child) {
      if (typeof child === 'string') {
        return child;
      }
      return _server2.default.renderToStaticMarkup(child);
    });
  };

  _this.isInheritedAttributes = function (name) {
    return _this.mjml.get('inheritedAttributes') && _this.mjml.get('inheritedAttributes').includes(name);
  };

  _this.getWidth = function () {
    return _this.mjAttribute('rawPxWidth') || _this.mjAttribute('width');
  };

  _this.getParentWidth = function () {
    return _this.mjAttribute('parentWidth');
  };

  _this.renderWrappedOutlookChildren = function (children) {
    children = _react2.default.Children.toArray(children);

    var realChildren = children.filter(function (child) {
      return !child.props.mjml || child.props.mjml.get('tagName') !== 'mj-raw';
    });

    var prefix = _this.mjName() + '-outlook';
    var parentWidth = _this.getWidth();
    var siblings = realChildren.length;
    var elementsWidth = realChildren.map(function (element) {
      if (_this.isInheritedAttributes('width')) {
        return parseInt(parentWidth);
      }

      return getElementWidth({ element: element, siblings: siblings, parentWidth: parentWidth });
    });

    var wrappedElements = [];

    if (siblings == 0) {
      return wrappedElements;
    }

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-open', className: prefix + '-open', 'data-width':
elementsWidth[0] }));

    var i = 0;

    children.forEach(function (child) {
      var childProps = Object.assign({}, child.props);

      if (childProps.mjml) {
        childProps.mjml = childProps.mjml.setIn(['attributes', 'rawPxWidth'], elementsWidth[i]);

        if (_this.mjml.get('inheritedAttributes')) {
          childProps.mjml = childProps.mjml.mergeIn(['attributes', _this.inheritedAttributes()]);
        }
      } else {
        Object.assign(childProps, { rawPxWidth: elementsWidth[i] });

        if (_this.mjml.get('inheritedAttributes')) {
          Object.assign(childProps, _this.inheritedAttributes());
        }
      }

      var childWithProps = _react2.default.cloneElement(child, childProps);

      wrappedElements.push(childWithProps);
      if (!childWithProps.type.rawElement && i < realChildren.length - 1) {
        wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-' + i, className: prefix + '-line', 'data-width
': elementsWidth[++i] }));
      }
    });

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-close', className: prefix + '-close' }));

    return wrappedElements;
  };

  _this.paddingParser = function (direction) {
    var prefix = arguments.length > 1 && arguments[1] !== undefined ? arguments[1] : '';

    var paddingDirection = _this.mjAttribute(prefix + 'padding-' + direction);
    var padding = _this.mjAttribute(prefix + 'padding');

    if (paddingDirection != null) {
      return parseInt(paddingDirection);
    }

    if (!padding) {
      return 0;
    }

    var paddings = padding.split(' ');
    var directions = {};

    switch (paddings.length) {
      case 1:
        return parseInt(padding);
      case 2:
        directions = { top: 0, bottom: 0, left: 1, right: 1 };
        break;
      case 3:
        directions = { top: 0, left: 1, right: 1, bottom: 2 };
        break;
      case 4:
        directions = { top: 0, right: 1, bottom: 2, left: 3 };
        break;
    }

    return parseInt(paddings[directions[direction]] || 0);
  };

  _this.mjml = props.mjml || _immutable2. ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mjml.elements.mj-carousel.postRender"></a>[function <span class="apidocSignatureSpan">mjml.elements.mj-carousel.</span>postRender ($)](#apidoc.element.mjml.elements.mj-carousel.postRender)
- description and source-code
```javascript
function postRender($) {
  var $mjCarousel = $('.mj-carousel');

  if ($mjCarousel.length === 0) {
    return $;
  }

  var length = $mjCarousel.data('length') * 1;

  var carouselCss = '<style type="text/css">\n  .mj-carousel {\n    -webkit-user-select: none;\n    -moz-user-select: none;\n
user-select: none;\n  }\n\n  .mj-carousel-icons-cell {\n    display: table-cell !important;\n    width: ' + $mjCarousel.data('icon-width') + ' !important;\n  }\n\n  .mj-carousel-radio,\n  .mj-carousel-next,\n  .mj-carousel-previous {\n    display: none !important;\n  }\n\n  .mj-carousel-thumbnail,\n  .mj-carousel-next,\n  .mj-carousel-previous {\n    touch-action: manipulation;\n  }\n\n  ' + (0, _range2.default)(0, length).map(function (i) {
    return '.mj-carousel-radio:checked ' + (0, _repeat2.default)('+ * ', i) + '+ .mj-carousel-content .mj-carousel-image';
  }).join(',') + ' {\n    display: none !important;\n  }\n\n  ' + (0, _range2.default)(0, length).map(function (i) {
    return '.mj-carousel-radio-' + (i + 1) + ':checked ' + (0, _repeat2.default)('+ * ', length - i - 1) + '+ .mj-carousel-content
 .mj-carousel-image-' + (i + 1);
  }).join(',') + ' {\n    display: block !important;\n  }\n\n  .mj-carousel-previous-icons,\n  .mj-carousel-next-icons,\n  ' + (
0, _range2.default)(0, length).map(function (i) {
    return '.mj-carousel-radio-' + (i + 1) + ':checked ' + (0, _repeat2.default)('+ * ', length - i - 1) + '+ .mj-carousel-content
 .mj-carousel-next-' + ((i + 1 % length + length) % length + 1);
  }) + ',\n  ' + (0, _range2.default)(0, length).map(function (i) {
    return '.mj-carousel-radio-' + (i + 1) + ':checked ' + (0, _repeat2.default)('+ * ', length - i - 1) + '+ .mj-carousel-content
 .mj-carousel-previous-' + ((i - 1 % length + length) % length + 1);
  }) + ' {\n    display: block !important;\n  }\n\n  ' + (0, _range2.default)(0, length).map(function (i) {
    return '.mj-carousel-radio-' + (i + 1) + ':checked ' + (0, _repeat2.default)('+ * ', length - i - 1) + '+ .mj-carousel-content
 .mj-carousel-thumbnail-' + (i + 1);
  }).join(',') + ' {\n    border-color: ' + $mjCarousel.data('selected-border-color') + ' !important;\n  }\n\n  .mj-carousel-image
 img + div,\n  .mj-carousel-thumbnail img + div {\n    display: none !important;\n  }\n\n  ' + (0, _range2.default)(0, length).map(function (i) {
    return '.mj-carousel-thumbnail:hover ' + (0, _repeat2.default)('+ * ', length - i - 1) + '+ .mj-carousel-main .mj-carousel-image
';
  }).join(',') + ' {\n    display: none !important;\n  }\n\n  .mj-carousel-thumbnail:hover {\n    border-color: ' + $mjCarousel.
data('hover-border-color') + ' !important;\n  }\n\n  ' + (0, _range2.default)(0, length).map(function (i) {
    return '.mj-carousel-thumbnail-' + (i + 1) + ':hover ' + (0, _repeat2.default)('+ * ', length - i - 1) + '+ .mj-carousel-main
 .mj-carousel-image-' + (i + 1);
  }).join(',') + ' {\n    display: block !important;\n  }\n  </style>';

  var fallback = '\n  <style type="text/css" id="mj-carousel-fallback">\n    .mj-carousel noinput { display:block !important; }\
n    .mj-carousel noinput .mj-carousel-image-1 { display: block !important;  }\n    .mj-carousel noinput .mj-carousel-arrows,\n    .mj-carousel noinput .mj-carousel-thumbnails { display: none !important; }\n\n    [owa] .mj-carousel-thumbnail { display: none !important; }\n\n    @media screen yahoo {\n        .mj-carousel-icons-cell,\n        .mj-carousel-previous-icons,\n        .mj-carousel-next-icons {\n            display: none !important;\n        }\n\n        .mj-carousel-radio-1:checked ' + (0, _repeat2.default)('+ *', length - 1) + '+ .mj-carousel-content .mj-carousel-thumbnail-1 {\n            border-color: transparent;\n        }\n    }\n  </style>';

  $('head').append(carouselCss);
  $('head').append(fallback);

  $('.mj-carousel').before('<!--[if !mso]><!-->');
  $('.mj-carousel').after(_mjmlCore.helpers.endNegationConditionalTag + '\n    <!--[if mso]>\n    ' + $('.mj-carousel-image-1').
html() + '\n    ' + _mjmlCore.helpers.endConditionalTag);

  return $;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mjml.elements.mj-column"></a>[module mjml.elements.mj-column](#apidoc.module.mjml.elements.mj-column)

#### <a name="apidoc.element.mjml.elements.mj-column.mj-column"></a>[function <span class="apidocSignatureSpan">mjml.elements.</span>mj-column (props)](#apidoc.element.mjml.elements.mj-column.mj-column)
- description and source-code
```javascript
function MJMLElement(props) {
  _classCallCheck(this, MJMLElement);

  var _this = _possibleConstructorReturn(this, (MJMLElement.__proto__ || Object.getPrototypeOf(MJMLElement)).call(this, props));

  _this.mjAttribute = function (name) {
    return _this.mjml.getIn(['attributes', name]);
  };

  _this.mjName = function () {
    return _this.constructor.tagName;
  };

  _this.mjContent = function () {
    var content = _this.mjml.get('content');

    if (content) {
      return (0, _trim2.default)(content);
    }

    return _react2.default.Children.map(_this.props.children, function (child) {
      if (typeof child === 'string') {
        return child;
      }
      return _server2.default.renderToStaticMarkup(child);
    });
  };

  _this.isInheritedAttributes = function (name) {
    return _this.mjml.get('inheritedAttributes') && _this.mjml.get('inheritedAttributes').includes(name);
  };

  _this.getWidth = function () {
    return _this.mjAttribute('rawPxWidth') || _this.mjAttribute('width');
  };

  _this.getParentWidth = function () {
    return _this.mjAttribute('parentWidth');
  };

  _this.renderWrappedOutlookChildren = function (children) {
    children = _react2.default.Children.toArray(children);

    var realChildren = children.filter(function (child) {
      return !child.props.mjml || child.props.mjml.get('tagName') !== 'mj-raw';
    });

    var prefix = _this.mjName() + '-outlook';
    var parentWidth = _this.getWidth();
    var siblings = realChildren.length;
    var elementsWidth = realChildren.map(function (element) {
      if (_this.isInheritedAttributes('width')) {
        return parseInt(parentWidth);
      }

      return getElementWidth({ element: element, siblings: siblings, parentWidth: parentWidth });
    });

    var wrappedElements = [];

    if (siblings == 0) {
      return wrappedElements;
    }

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-open', className: prefix + '-open', 'data-width':
elementsWidth[0] }));

    var i = 0;

    children.forEach(function (child) {
      var childProps = Object.assign({}, child.props);

      if (childProps.mjml) {
        childProps.mjml = childProps.mjml.setIn(['attributes', 'rawPxWidth'], elementsWidth[i]);

        if (_this.mjml.get('inheritedAttributes')) {
          childProps.mjml = childProps.mjml.mergeIn(['attributes', _this.inheritedAttributes()]);
        }
      } else {
        Object.assign(childProps, { rawPxWidth: elementsWidth[i] });

        if (_this.mjml.get('inheritedAttributes')) {
          Object.assign(childProps, _this.inheritedAttributes());
        }
      }

      var childWithProps = _react2.default.cloneElement(child, childProps);

      wrappedElements.push(childWithProps);
      if (!childWithProps.type.rawElement && i < realChildren.length - 1) {
        wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-' + i, className: prefix + '-line', 'data-width
': elementsWidth[++i] }));
      }
    });

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-close', className: prefix + '-close' }));

    return wrappedElements;
  };

  _this.paddingParser = function (direction) {
    var prefix = arguments.length > 1 && arguments[1] !== undefined ? arguments[1] : '';

    var paddingDirection = _this.mjAttribute(prefix + 'padding-' + direction);
    var padding = _this.mjAttribute(prefix + 'padding');

    if (paddingDirection != null) {
      return parseInt(paddingDirection);
    }

    if (!padding) {
      return 0;
    }

    var paddings = padding.split(' ');
    var directions = {};

    switch (paddings.length) {
      case 1:
        return parseInt(padding);
      case 2:
        directions = { top: 0, bottom: 0, left: 1, right: 1 };
        break;
      case 3:
        directions = { top: 0, left: 1, right: 1, bottom: 2 };
        break;
      case 4:
        directions = { top: 0, right: 1, bottom: 2, left: 3 };
        break;
    }

    return parseInt(paddings[directions[direction]] || 0);
  };

  _this.mjml = props.mjml || _immutable2. ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mjml.elements.mj-column.postRender"></a>[function <span class="apidocSignatureSpan">mjml.elements.mj-column.</span>postRender ($)](#apidoc.element.mjml.elements.mj-column.postRender)
- description and source-code
```javascript
function postRender($) {
  var mediaQueries = [];

  (0, _each2.default)({ 'mj-column-per': '%', 'mj-column-px': 'px' }, function (unit, className) {
    var columnWidths = [];

    $('[class*="' + className + '"]').each(function () {
      columnWidths.push($(this).data('column-width'));
      $(this).removeAttr('data-column-width');
    });

    (0, _uniq2.default)(columnWidths).forEach(function (width) {
      var _helpers$widthParser = _mjmlCore.helpers.widthParser(width, { parseFloatToInt: false }),
          parsedWidth = _helpers$widthParser.width;

      var mediaQueryClass = className + '-' + parseInt(parsedWidth);

      mediaQueries.push('.' + mediaQueryClass + ' { width:' + parsedWidth + unit + '!important; }');
    });
  });

  if (mediaQueries.length > 0) {
    var mediaQuery = '<style type="text/css">\n  @media only screen and (min-width:480px) {\n    ' + mediaQueries.join('\n') + '\n  }\n</style>\n';

    $('head').append(mediaQuery);
  }

  return $;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mjml.elements.mj-container"></a>[module mjml.elements.mj-container](#apidoc.module.mjml.elements.mj-container)

#### <a name="apidoc.element.mjml.elements.mj-container.mj-container"></a>[function <span class="apidocSignatureSpan">mjml.elements.</span>mj-container (props)](#apidoc.element.mjml.elements.mj-container.mj-container)
- description and source-code
```javascript
function MJMLElement(props) {
  _classCallCheck(this, MJMLElement);

  var _this = _possibleConstructorReturn(this, (MJMLElement.__proto__ || Object.getPrototypeOf(MJMLElement)).call(this, props));

  _this.mjAttribute = function (name) {
    return _this.mjml.getIn(['attributes', name]);
  };

  _this.mjName = function () {
    return _this.constructor.tagName;
  };

  _this.mjContent = function () {
    var content = _this.mjml.get('content');

    if (content) {
      return (0, _trim2.default)(content);
    }

    return _react2.default.Children.map(_this.props.children, function (child) {
      if (typeof child === 'string') {
        return child;
      }
      return _server2.default.renderToStaticMarkup(child);
    });
  };

  _this.isInheritedAttributes = function (name) {
    return _this.mjml.get('inheritedAttributes') && _this.mjml.get('inheritedAttributes').includes(name);
  };

  _this.getWidth = function () {
    return _this.mjAttribute('rawPxWidth') || _this.mjAttribute('width');
  };

  _this.getParentWidth = function () {
    return _this.mjAttribute('parentWidth');
  };

  _this.renderWrappedOutlookChildren = function (children) {
    children = _react2.default.Children.toArray(children);

    var realChildren = children.filter(function (child) {
      return !child.props.mjml || child.props.mjml.get('tagName') !== 'mj-raw';
    });

    var prefix = _this.mjName() + '-outlook';
    var parentWidth = _this.getWidth();
    var siblings = realChildren.length;
    var elementsWidth = realChildren.map(function (element) {
      if (_this.isInheritedAttributes('width')) {
        return parseInt(parentWidth);
      }

      return getElementWidth({ element: element, siblings: siblings, parentWidth: parentWidth });
    });

    var wrappedElements = [];

    if (siblings == 0) {
      return wrappedElements;
    }

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-open', className: prefix + '-open', 'data-width':
elementsWidth[0] }));

    var i = 0;

    children.forEach(function (child) {
      var childProps = Object.assign({}, child.props);

      if (childProps.mjml) {
        childProps.mjml = childProps.mjml.setIn(['attributes', 'rawPxWidth'], elementsWidth[i]);

        if (_this.mjml.get('inheritedAttributes')) {
          childProps.mjml = childProps.mjml.mergeIn(['attributes', _this.inheritedAttributes()]);
        }
      } else {
        Object.assign(childProps, { rawPxWidth: elementsWidth[i] });

        if (_this.mjml.get('inheritedAttributes')) {
          Object.assign(childProps, _this.inheritedAttributes());
        }
      }

      var childWithProps = _react2.default.cloneElement(child, childProps);

      wrappedElements.push(childWithProps);
      if (!childWithProps.type.rawElement && i < realChildren.length - 1) {
        wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-' + i, className: prefix + '-line', 'data-width
': elementsWidth[++i] }));
      }
    });

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-close', className: prefix + '-close' }));

    return wrappedElements;
  };

  _this.paddingParser = function (direction) {
    var prefix = arguments.length > 1 && arguments[1] !== undefined ? arguments[1] : '';

    var paddingDirection = _this.mjAttribute(prefix + 'padding-' + direction);
    var padding = _this.mjAttribute(prefix + 'padding');

    if (paddingDirection != null) {
      return parseInt(paddingDirection);
    }

    if (!padding) {
      return 0;
    }

    var paddings = padding.split(' ');
    var directions = {};

    switch (paddings.length) {
      case 1:
        return parseInt(padding);
      case 2:
        directions = { top: 0, bottom: 0, left: 1, right: 1 };
        break;
      case 3:
        directions = { top: 0, left: 1, right: 1, bottom: 2 };
        break;
      case 4:
        directions = { top: 0, right: 1, bottom: 2, left: 3 };
        break;
    }

    return parseInt(paddings[directions[direction]] || 0);
  };

  _this.mjml = props.mjml || _immutable2. ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mjml.elements.mj-container.postRender"></a>[function <span class="apidocSignatureSpan">mjml.elements.mj-container.</span>postRender ($)](#apidoc.element.mjml.elements.mj-container.postRender)
- description and source-code
```javascript
function postRender($) {
  var containerWidth = $('.mj-container').data('width');

  $('.mj-container-outlook-open').each(function () {
    $(this).replaceWith(_mjmlCore.helpers.startConditionalTag + '\n      <table role="presentation" border="0" cellpadding="0" cellspacing
="0" width="' + containerWidth + '" align="center" style="width:' + containerWidth + 'px;">\n        <tr>\n          <td style="line-height:0px;font-size:0px;mso-line-height-rule:exactly;">\n      ' + _mjmlCore.helpers.endConditionalTag);
  });

  $('.mj-container-outlook-line').each(function () {
    $(this).replaceWith(_mjmlCore.helpers.startConditionalTag + '\n      </td></tr></table>\n      ' + _mjmlCore.helpers.endConditionalTag
 + '\n      ' + _mjmlCore.helpers.startConditionalTag + '\n      <table role="presentation" border="0" cellpadding="0" cellspacing="0" width="' + containerWidth + '" align="center" style="width:' + containerWidth + 'px;">\n        <tr>\n          <td style="line-height:0px;font-size:0px;mso-line-height-rule:exactly;">\n      ' + _mjmlCore.helpers.endConditionalTag);
  });

  $('.mj-container-outlook-close').each(function () {
    $(this).replaceWith(_mjmlCore.helpers.startConditionalTag + '\n      </td></tr></table>\n      ' + _mjmlCore.helpers.endConditionalTag
);
  });

  $('body').css({ background: $('.mj-container').data('background-color') }).each(function () {
    if ($(this).attr('style') === '') {
      $(this).removeAttr('style');
    }
  });

  $('.mj-container').removeAttr('data-background-color').removeAttr('data-width').removeAttr('class').each(function () {
    if ($(this).attr('style') === '') {
      $(this).removeAttr('style');
    }
  });

  return $;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mjml.elements.mj-divider"></a>[module mjml.elements.mj-divider](#apidoc.module.mjml.elements.mj-divider)

#### <a name="apidoc.element.mjml.elements.mj-divider.mj-divider"></a>[function <span class="apidocSignatureSpan">mjml.elements.</span>mj-divider (props)](#apidoc.element.mjml.elements.mj-divider.mj-divider)
- description and source-code
```javascript
function MJMLElement(props) {
  _classCallCheck(this, MJMLElement);

  var _this = _possibleConstructorReturn(this, (MJMLElement.__proto__ || Object.getPrototypeOf(MJMLElement)).call(this, props));

  _this.mjAttribute = function (name) {
    return _this.mjml.getIn(['attributes', name]);
  };

  _this.mjName = function () {
    return _this.constructor.tagName;
  };

  _this.mjContent = function () {
    var content = _this.mjml.get('content');

    if (content) {
      return (0, _trim2.default)(content);
    }

    return _react2.default.Children.map(_this.props.children, function (child) {
      if (typeof child === 'string') {
        return child;
      }
      return _server2.default.renderToStaticMarkup(child);
    });
  };

  _this.isInheritedAttributes = function (name) {
    return _this.mjml.get('inheritedAttributes') && _this.mjml.get('inheritedAttributes').includes(name);
  };

  _this.getWidth = function () {
    return _this.mjAttribute('rawPxWidth') || _this.mjAttribute('width');
  };

  _this.getParentWidth = function () {
    return _this.mjAttribute('parentWidth');
  };

  _this.renderWrappedOutlookChildren = function (children) {
    children = _react2.default.Children.toArray(children);

    var realChildren = children.filter(function (child) {
      return !child.props.mjml || child.props.mjml.get('tagName') !== 'mj-raw';
    });

    var prefix = _this.mjName() + '-outlook';
    var parentWidth = _this.getWidth();
    var siblings = realChildren.length;
    var elementsWidth = realChildren.map(function (element) {
      if (_this.isInheritedAttributes('width')) {
        return parseInt(parentWidth);
      }

      return getElementWidth({ element: element, siblings: siblings, parentWidth: parentWidth });
    });

    var wrappedElements = [];

    if (siblings == 0) {
      return wrappedElements;
    }

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-open', className: prefix + '-open', 'data-width':
elementsWidth[0] }));

    var i = 0;

    children.forEach(function (child) {
      var childProps = Object.assign({}, child.props);

      if (childProps.mjml) {
        childProps.mjml = childProps.mjml.setIn(['attributes', 'rawPxWidth'], elementsWidth[i]);

        if (_this.mjml.get('inheritedAttributes')) {
          childProps.mjml = childProps.mjml.mergeIn(['attributes', _this.inheritedAttributes()]);
        }
      } else {
        Object.assign(childProps, { rawPxWidth: elementsWidth[i] });

        if (_this.mjml.get('inheritedAttributes')) {
          Object.assign(childProps, _this.inheritedAttributes());
        }
      }

      var childWithProps = _react2.default.cloneElement(child, childProps);

      wrappedElements.push(childWithProps);
      if (!childWithProps.type.rawElement && i < realChildren.length - 1) {
        wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-' + i, className: prefix + '-line', 'data-width
': elementsWidth[++i] }));
      }
    });

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-close', className: prefix + '-close' }));

    return wrappedElements;
  };

  _this.paddingParser = function (direction) {
    var prefix = arguments.length > 1 && arguments[1] !== undefined ? arguments[1] : '';

    var paddingDirection = _this.mjAttribute(prefix + 'padding-' + direction);
    var padding = _this.mjAttribute(prefix + 'padding');

    if (paddingDirection != null) {
      return parseInt(paddingDirection);
    }

    if (!padding) {
      return 0;
    }

    var paddings = padding.split(' ');
    var directions = {};

    switch (paddings.length) {
      case 1:
        return parseInt(padding);
      case 2:
        directions = { top: 0, bottom: 0, left: 1, right: 1 };
        break;
      case 3:
        directions = { top: 0, left: 1, right: 1, bottom: 2 };
        break;
      case 4:
        directions = { top: 0, right: 1, bottom: 2, left: 3 };
        break;
    }

    return parseInt(paddings[directions[direction]] || 0);
  };

  _this.mjml = props.mjml || _immutable2. ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mjml.elements.mj-divider.postRender"></a>[function <span class="apidocSignatureSpan">mjml.elements.mj-divider.</span>postRender ($)](#apidoc.element.mjml.elements.mj-divider.postRender)
- description and source-code
```javascript
function postRender($) {
  $('.mj-divider-outlook').each(function () {
    var insertNode = '<table role="presentation" align="center" border="0" cellpadding="0" cellspacing="0" style="' + $(this).attr
('style') + '" width="' + $(this).data('divider-width') + '"><tr><td style="height:0;line-height:0;">&nbsp;</td></tr></table>';

    $(this).removeAttr('data-divider-width').removeAttr('class').after('' + _mjmlCore.helpers.startConditionalTag + insertNode +
_mjmlCore.helpers.endConditionalTag);
  });

  return $;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mjml.elements.mj-group"></a>[module mjml.elements.mj-group](#apidoc.module.mjml.elements.mj-group)

#### <a name="apidoc.element.mjml.elements.mj-group.mj-group"></a>[function <span class="apidocSignatureSpan">mjml.elements.</span>mj-group (props)](#apidoc.element.mjml.elements.mj-group.mj-group)
- description and source-code
```javascript
function MJMLElement(props) {
  _classCallCheck(this, MJMLElement);

  var _this = _possibleConstructorReturn(this, (MJMLElement.__proto__ || Object.getPrototypeOf(MJMLElement)).call(this, props));

  _this.mjAttribute = function (name) {
    return _this.mjml.getIn(['attributes', name]);
  };

  _this.mjName = function () {
    return _this.constructor.tagName;
  };

  _this.mjContent = function () {
    var content = _this.mjml.get('content');

    if (content) {
      return (0, _trim2.default)(content);
    }

    return _react2.default.Children.map(_this.props.children, function (child) {
      if (typeof child === 'string') {
        return child;
      }
      return _server2.default.renderToStaticMarkup(child);
    });
  };

  _this.isInheritedAttributes = function (name) {
    return _this.mjml.get('inheritedAttributes') && _this.mjml.get('inheritedAttributes').includes(name);
  };

  _this.getWidth = function () {
    return _this.mjAttribute('rawPxWidth') || _this.mjAttribute('width');
  };

  _this.getParentWidth = function () {
    return _this.mjAttribute('parentWidth');
  };

  _this.renderWrappedOutlookChildren = function (children) {
    children = _react2.default.Children.toArray(children);

    var realChildren = children.filter(function (child) {
      return !child.props.mjml || child.props.mjml.get('tagName') !== 'mj-raw';
    });

    var prefix = _this.mjName() + '-outlook';
    var parentWidth = _this.getWidth();
    var siblings = realChildren.length;
    var elementsWidth = realChildren.map(function (element) {
      if (_this.isInheritedAttributes('width')) {
        return parseInt(parentWidth);
      }

      return getElementWidth({ element: element, siblings: siblings, parentWidth: parentWidth });
    });

    var wrappedElements = [];

    if (siblings == 0) {
      return wrappedElements;
    }

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-open', className: prefix + '-open', 'data-width':
elementsWidth[0] }));

    var i = 0;

    children.forEach(function (child) {
      var childProps = Object.assign({}, child.props);

      if (childProps.mjml) {
        childProps.mjml = childProps.mjml.setIn(['attributes', 'rawPxWidth'], elementsWidth[i]);

        if (_this.mjml.get('inheritedAttributes')) {
          childProps.mjml = childProps.mjml.mergeIn(['attributes', _this.inheritedAttributes()]);
        }
      } else {
        Object.assign(childProps, { rawPxWidth: elementsWidth[i] });

        if (_this.mjml.get('inheritedAttributes')) {
          Object.assign(childProps, _this.inheritedAttributes());
        }
      }

      var childWithProps = _react2.default.cloneElement(child, childProps);

      wrappedElements.push(childWithProps);
      if (!childWithProps.type.rawElement && i < realChildren.length - 1) {
        wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-' + i, className: prefix + '-line', 'data-width
': elementsWidth[++i] }));
      }
    });

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-close', className: prefix + '-close' }));

    return wrappedElements;
  };

  _this.paddingParser = function (direction) {
    var prefix = arguments.length > 1 && arguments[1] !== undefined ? arguments[1] : '';

    var paddingDirection = _this.mjAttribute(prefix + 'padding-' + direction);
    var padding = _this.mjAttribute(prefix + 'padding');

    if (paddingDirection != null) {
      return parseInt(paddingDirection);
    }

    if (!padding) {
      return 0;
    }

    var paddings = padding.split(' ');
    var directions = {};

    switch (paddings.length) {
      case 1:
        return parseInt(padding);
      case 2:
        directions = { top: 0, bottom: 0, left: 1, right: 1 };
        break;
      case 3:
        directions = { top: 0, left: 1, right: 1, bottom: 2 };
        break;
      case 4:
        directions = { top: 0, right: 1, bottom: 2, left: 3 };
        break;
    }

    return parseInt(paddings[directions[direction]] || 0);
  };

  _this.mjml = props.mjml || _immutable2. ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mjml.elements.mj-group.postRender"></a>[function <span class="apidocSignatureSpan">mjml.elements.mj-group.</span>postRender ($)](#apidoc.element.mjml.elements.mj-group.postRender)
- description and source-code
```javascript
function postRender($) {
  $('.mj-group-outlook-open').each(function () {
    var $parent = $(this).parent();
    var mjGroupBg = $parent.data('mj-group-background');
    var $columnDiv = $(this).next();
    var bgColor = mjGroupBg ? 'bgcolor="' + mjGroupBg + '"' : '';

    $(this).replaceWith(_mjmlCore.helpers.startConditionalTag + '\n      <table ' + bgColor + ' role="presentation" border="0" cellpadding
="0" cellspacing="0"><tr><td style="vertical-align:' + $columnDiv.data('vertical-align') + ';width:' + parseInt($(this).data('width
')) + 'px;">\n      ' + _mjmlCore.helpers.endConditionalTag);

    $parent.removeAttr('data-mj-group-background');
    $columnDiv.removeAttr('data-vertical-align');
  });

  $('.mj-group-outlook-line').each(function () {
    var $columnDiv = $(this).next();

    $(this).replaceWith(_mjmlCore.helpers.startConditionalTag + '\n    </td><td style="vertical-align:' + $columnDiv.data('vertical
-align') + ';width:' + parseInt($(this).data('width')) + 'px;">\n      ' + _mjmlCore.helpers.endConditionalTag);

    $columnDiv.removeAttr('data-vertical-align');
  });

  $('.mj-group-outlook-close').each(function () {
    $(this).replaceWith(_mjmlCore.helpers.startConditionalTag + '\n      </td></tr></table>\n      ' + _mjmlCore.helpers.endConditionalTag
);
  });

  return $;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mjml.elements.mj-hero"></a>[module mjml.elements.mj-hero](#apidoc.module.mjml.elements.mj-hero)

#### <a name="apidoc.element.mjml.elements.mj-hero.mj-hero"></a>[function <span class="apidocSignatureSpan">mjml.elements.</span>mj-hero (props)](#apidoc.element.mjml.elements.mj-hero.mj-hero)
- description and source-code
```javascript
function MJMLElement(props) {
  _classCallCheck(this, MJMLElement);

  var _this = _possibleConstructorReturn(this, (MJMLElement.__proto__ || Object.getPrototypeOf(MJMLElement)).call(this, props));

  _this.mjAttribute = function (name) {
    return _this.mjml.getIn(['attributes', name]);
  };

  _this.mjName = function () {
    return _this.constructor.tagName;
  };

  _this.mjContent = function () {
    var content = _this.mjml.get('content');

    if (content) {
      return (0, _trim2.default)(content);
    }

    return _react2.default.Children.map(_this.props.children, function (child) {
      if (typeof child === 'string') {
        return child;
      }
      return _server2.default.renderToStaticMarkup(child);
    });
  };

  _this.isInheritedAttributes = function (name) {
    return _this.mjml.get('inheritedAttributes') && _this.mjml.get('inheritedAttributes').includes(name);
  };

  _this.getWidth = function () {
    return _this.mjAttribute('rawPxWidth') || _this.mjAttribute('width');
  };

  _this.getParentWidth = function () {
    return _this.mjAttribute('parentWidth');
  };

  _this.renderWrappedOutlookChildren = function (children) {
    children = _react2.default.Children.toArray(children);

    var realChildren = children.filter(function (child) {
      return !child.props.mjml || child.props.mjml.get('tagName') !== 'mj-raw';
    });

    var prefix = _this.mjName() + '-outlook';
    var parentWidth = _this.getWidth();
    var siblings = realChildren.length;
    var elementsWidth = realChildren.map(function (element) {
      if (_this.isInheritedAttributes('width')) {
        return parseInt(parentWidth);
      }

      return getElementWidth({ element: element, siblings: siblings, parentWidth: parentWidth });
    });

    var wrappedElements = [];

    if (siblings == 0) {
      return wrappedElements;
    }

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-open', className: prefix + '-open', 'data-width':
elementsWidth[0] }));

    var i = 0;

    children.forEach(function (child) {
      var childProps = Object.assign({}, child.props);

      if (childProps.mjml) {
        childProps.mjml = childProps.mjml.setIn(['attributes', 'rawPxWidth'], elementsWidth[i]);

        if (_this.mjml.get('inheritedAttributes')) {
          childProps.mjml = childProps.mjml.mergeIn(['attributes', _this.inheritedAttributes()]);
        }
      } else {
        Object.assign(childProps, { rawPxWidth: elementsWidth[i] });

        if (_this.mjml.get('inheritedAttributes')) {
          Object.assign(childProps, _this.inheritedAttributes());
        }
      }

      var childWithProps = _react2.default.cloneElement(child, childProps);

      wrappedElements.push(childWithProps);
      if (!childWithProps.type.rawElement && i < realChildren.length - 1) {
        wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-' + i, className: prefix + '-line', 'data-width
': elementsWidth[++i] }));
      }
    });

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-close', className: prefix + '-close' }));

    return wrappedElements;
  };

  _this.paddingParser = function (direction) {
    var prefix = arguments.length > 1 && arguments[1] !== undefined ? arguments[1] : '';

    var paddingDirection = _this.mjAttribute(prefix + 'padding-' + direction);
    var padding = _this.mjAttribute(prefix + 'padding');

    if (paddingDirection != null) {
      return parseInt(paddingDirection);
    }

    if (!padding) {
      return 0;
    }

    var paddings = padding.split(' ');
    var directions = {};

    switch (paddings.length) {
      case 1:
        return parseInt(padding);
      case 2:
        directions = { top: 0, bottom: 0, left: 1, right: 1 };
        break;
      case 3:
        directions = { top: 0, left: 1, right: 1, bottom: 2 };
        break;
      case 4:
        directions = { top: 0, right: 1, bottom: 2, left: 3 };
        break;
    }

    return parseInt(paddings[directions[direction]] || 0);
  };

  _this.mjml = props.mjml || _immutable2. ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mjml.elements.mj-hero.postRender"></a>[function <span class="apidocSignatureSpan">mjml.elements.mj-hero.</span>postRender ($)](#apidoc.element.mjml.elements.mj-hero.postRender)
- description and source-code
```javascript
function postRender($) {
  var backgroundCropTop = 0;
  var backgroundCropBottom = 0;
  var dataCrop = '';
  var $element = void 0;
  var backgroundWidth = 0;
  var backgroundHeight = 0;
  var backgroundUrl = '';

  $('.mj-hero-outlook').each(function () {
    backgroundUrl = $(this).data('background-url');
    backgroundWidth = $(this).data('background-width');
    backgroundHeight = $(this).data('background-height');
    backgroundCropTop = 0;
    backgroundCropBottom = 0;
    dataCrop = '';

    $element = $(this).find('.mj-hero-fixed-height').first();

    if ($element.length) {
      dataCrop = $element.data('crop');
      backgroundHeight = $element.data('background-height');

      backgroundCropTop = dataCrop.split(', ')[0].split(':')[1];
      backgroundCropBottom = dataCrop.split(', ')[1].split(':')[1];

      $element.removeAttr('class').removeAttr('data-background-height').removeAttr('data-crop');
    }

    backgroundWidth = parseInt(backgroundWidth.replace('px', '')) * 0.75;
    backgroundHeight = parseInt(backgroundHeight.replace('px', '')) * 0.75;

    $(this).before(_mjmlCore.helpers.startConditionalTag + '\n          <v:image xmlns:v="urn:schemas-microsoft-com:vml" croptop
="' + backgroundCropTop + '" cropbottom="' + backgroundCropBottom + '" style="width:' + backgroundWidth + 'pt;height:' + backgroundHeight
 + 'pt;position:absolute;top:0;mso-position-horizontal:center;border:0;z-index:-3;" src="' + backgroundUrl + '" />\n        ' + _mjmlCore.helpers.endConditionalTag).removeAttr('class').removeAttr('data-background-width').removeAttr('data-background-height').removeAttr('data-background-url');
  });

  return $;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mjml.elements.mj-hero-content"></a>[module mjml.elements.mj-hero-content](#apidoc.module.mjml.elements.mj-hero-content)

#### <a name="apidoc.element.mjml.elements.mj-hero-content.mj-hero-content"></a>[function <span class="apidocSignatureSpan">mjml.elements.</span>mj-hero-content (props)](#apidoc.element.mjml.elements.mj-hero-content.mj-hero-content)
- description and source-code
```javascript
function MJMLElement(props) {
  _classCallCheck(this, MJMLElement);

  var _this = _possibleConstructorReturn(this, (MJMLElement.__proto__ || Object.getPrototypeOf(MJMLElement)).call(this, props));

  _this.mjAttribute = function (name) {
    return _this.mjml.getIn(['attributes', name]);
  };

  _this.mjName = function () {
    return _this.constructor.tagName;
  };

  _this.mjContent = function () {
    var content = _this.mjml.get('content');

    if (content) {
      return (0, _trim2.default)(content);
    }

    return _react2.default.Children.map(_this.props.children, function (child) {
      if (typeof child === 'string') {
        return child;
      }
      return _server2.default.renderToStaticMarkup(child);
    });
  };

  _this.isInheritedAttributes = function (name) {
    return _this.mjml.get('inheritedAttributes') && _this.mjml.get('inheritedAttributes').includes(name);
  };

  _this.getWidth = function () {
    return _this.mjAttribute('rawPxWidth') || _this.mjAttribute('width');
  };

  _this.getParentWidth = function () {
    return _this.mjAttribute('parentWidth');
  };

  _this.renderWrappedOutlookChildren = function (children) {
    children = _react2.default.Children.toArray(children);

    var realChildren = children.filter(function (child) {
      return !child.props.mjml || child.props.mjml.get('tagName') !== 'mj-raw';
    });

    var prefix = _this.mjName() + '-outlook';
    var parentWidth = _this.getWidth();
    var siblings = realChildren.length;
    var elementsWidth = realChildren.map(function (element) {
      if (_this.isInheritedAttributes('width')) {
        return parseInt(parentWidth);
      }

      return getElementWidth({ element: element, siblings: siblings, parentWidth: parentWidth });
    });

    var wrappedElements = [];

    if (siblings == 0) {
      return wrappedElements;
    }

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-open', className: prefix + '-open', 'data-width':
elementsWidth[0] }));

    var i = 0;

    children.forEach(function (child) {
      var childProps = Object.assign({}, child.props);

      if (childProps.mjml) {
        childProps.mjml = childProps.mjml.setIn(['attributes', 'rawPxWidth'], elementsWidth[i]);

        if (_this.mjml.get('inheritedAttributes')) {
          childProps.mjml = childProps.mjml.mergeIn(['attributes', _this.inheritedAttributes()]);
        }
      } else {
        Object.assign(childProps, { rawPxWidth: elementsWidth[i] });

        if (_this.mjml.get('inheritedAttributes')) {
          Object.assign(childProps, _this.inheritedAttributes());
        }
      }

      var childWithProps = _react2.default.cloneElement(child, childProps);

      wrappedElements.push(childWithProps);
      if (!childWithProps.type.rawElement && i < realChildren.length - 1) {
        wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-' + i, className: prefix + '-line', 'data-width
': elementsWidth[++i] }));
      }
    });

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-close', className: prefix + '-close' }));

    return wrappedElements;
  };

  _this.paddingParser = function (direction) {
    var prefix = arguments.length > 1 && arguments[1] !== undefined ? arguments[1] : '';

    var paddingDirection = _this.mjAttribute(prefix + 'padding-' + direction);
    var padding = _this.mjAttribute(prefix + 'padding');

    if (paddingDirection != null) {
      return parseInt(paddingDirection);
    }

    if (!padding) {
      return 0;
    }

    var paddings = padding.split(' ');
    var directions = {};

    switch (paddings.length) {
      case 1:
        return parseInt(padding);
      case 2:
        directions = { top: 0, bottom: 0, left: 1, right: 1 };
        break;
      case 3:
        directions = { top: 0, left: 1, right: 1, bottom: 2 };
        break;
      case 4:
        directions = { top: 0, right: 1, bottom: 2, left: 3 };
        break;
    }

    return parseInt(paddings[directions[direction]] || 0);
  };

  _this.mjml = props.mjml || _immutable2. ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mjml.elements.mj-hero-content.postRender"></a>[function <span class="apidocSignatureSpan">mjml.elements.mj-hero-content.</span>postRender ($)](#apidoc.element.mjml.elements.mj-hero-content.postRender)
- description and source-code
```javascript
function postRender($) {
  var $mjHeroContent = $('.mj-hero-content');

  $mjHeroContent.each(function () {
    var width = $(this).css('width');
    var align = $(this).data('align');
    var backgroundColor = $(this).data('background-color');

    $(this).before(_mjmlCore.helpers.startConditionalTag + '\n      <table role="presentation" border="0" cellpadding="0" cellspacing
="0" align="' + align + '" width="' + width.replace('px', '') + '" style="width:' + width + ';"><tr><td style="padding:0;background
-color:' + backgroundColor + ';">\n      ' + _mjmlCore.helpers.endConditionalTag).after(_mjmlCore.helpers.startConditionalTag + '\n      </td></tr></table>\n      ' + _mjmlCore.helpers.endConditionalTag).removeAttr('data-background-color').removeAttr('data-align');
  });

  if ($mjHeroContent.length > 0) {
    $('head').append('<style type="text/css">\n      @media only screen and (max-width:480px) {\n        .mj-hero-content {\n
width: 100% !important;\n        }\n      }\n    </style>');
  }

  return $;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mjml.elements.mj-inline-links"></a>[module mjml.elements.mj-inline-links](#apidoc.module.mjml.elements.mj-inline-links)

#### <a name="apidoc.element.mjml.elements.mj-inline-links.mj-inline-links"></a>[function <span class="apidocSignatureSpan">mjml.elements.</span>mj-inline-links (props)](#apidoc.element.mjml.elements.mj-inline-links.mj-inline-links)
- description and source-code
```javascript
function MJMLElement(props) {
  _classCallCheck(this, MJMLElement);

  var _this = _possibleConstructorReturn(this, (MJMLElement.__proto__ || Object.getPrototypeOf(MJMLElement)).call(this, props));

  _this.mjAttribute = function (name) {
    return _this.mjml.getIn(['attributes', name]);
  };

  _this.mjName = function () {
    return _this.constructor.tagName;
  };

  _this.mjContent = function () {
    var content = _this.mjml.get('content');

    if (content) {
      return (0, _trim2.default)(content);
    }

    return _react2.default.Children.map(_this.props.children, function (child) {
      if (typeof child === 'string') {
        return child;
      }
      return _server2.default.renderToStaticMarkup(child);
    });
  };

  _this.isInheritedAttributes = function (name) {
    return _this.mjml.get('inheritedAttributes') && _this.mjml.get('inheritedAttributes').includes(name);
  };

  _this.getWidth = function () {
    return _this.mjAttribute('rawPxWidth') || _this.mjAttribute('width');
  };

  _this.getParentWidth = function () {
    return _this.mjAttribute('parentWidth');
  };

  _this.renderWrappedOutlookChildren = function (children) {
    children = _react2.default.Children.toArray(children);

    var realChildren = children.filter(function (child) {
      return !child.props.mjml || child.props.mjml.get('tagName') !== 'mj-raw';
    });

    var prefix = _this.mjName() + '-outlook';
    var parentWidth = _this.getWidth();
    var siblings = realChildren.length;
    var elementsWidth = realChildren.map(function (element) {
      if (_this.isInheritedAttributes('width')) {
        return parseInt(parentWidth);
      }

      return getElementWidth({ element: element, siblings: siblings, parentWidth: parentWidth });
    });

    var wrappedElements = [];

    if (siblings == 0) {
      return wrappedElements;
    }

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-open', className: prefix + '-open', 'data-width':
elementsWidth[0] }));

    var i = 0;

    children.forEach(function (child) {
      var childProps = Object.assign({}, child.props);

      if (childProps.mjml) {
        childProps.mjml = childProps.mjml.setIn(['attributes', 'rawPxWidth'], elementsWidth[i]);

        if (_this.mjml.get('inheritedAttributes')) {
          childProps.mjml = childProps.mjml.mergeIn(['attributes', _this.inheritedAttributes()]);
        }
      } else {
        Object.assign(childProps, { rawPxWidth: elementsWidth[i] });

        if (_this.mjml.get('inheritedAttributes')) {
          Object.assign(childProps, _this.inheritedAttributes());
        }
      }

      var childWithProps = _react2.default.cloneElement(child, childProps);

      wrappedElements.push(childWithProps);
      if (!childWithProps.type.rawElement && i < realChildren.length - 1) {
        wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-' + i, className: prefix + '-line', 'data-width
': elementsWidth[++i] }));
      }
    });

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-close', className: prefix + '-close' }));

    return wrappedElements;
  };

  _this.paddingParser = function (direction) {
    var prefix = arguments.length > 1 && arguments[1] !== undefined ? arguments[1] : '';

    var paddingDirection = _this.mjAttribute(prefix + 'padding-' + direction);
    var padding = _this.mjAttribute(prefix + 'padding');

    if (paddingDirection != null) {
      return parseInt(paddingDirection);
    }

    if (!padding) {
      return 0;
    }

    var paddings = padding.split(' ');
    var directions = {};

    switch (paddings.length) {
      case 1:
        return parseInt(padding);
      case 2:
        directions = { top: 0, bottom: 0, left: 1, right: 1 };
        break;
      case 3:
        directions = { top: 0, left: 1, right: 1, bottom: 2 };
        break;
      case 4:
        directions = { top: 0, right: 1, bottom: 2, left: 3 };
        break;
    }

    return parseInt(paddings[directions[direction]] || 0);
  };

  _this.mjml = props.mjml || _immutable2. ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mjml.elements.mj-inline-links.postRender"></a>[function <span class="apidocSignatureSpan">mjml.elements.mj-inline-links.</span>postRender ($)](#apidoc.element.mjml.elements.mj-inline-links.postRender)
- description and source-code
```javascript
function postRender($) {
  $('.mj-inline-links').each(function () {
    $(this).prepend('<!--[if gte mso 9]>\n          <table role="presentation" border="0" cellpadding="0" cellspacing="0" align="' + $(
this).data('align') + '">\n            <tr>\n        <![endif]-->').append('<!--[if gte mso 9]>\n            </tr>\n          </table>\n        <![endif]-->').removeAttr('data-align');
  });

  $('.mj-menu-trigger').each(function () {
    var id = $(this).children('label').attr('for');

    $(this).before('<!--[if !mso]><!-->\n          <input type="checkbox" id="' + id + '" class="mj-menu-checkbox" style="display
:none !important; max-height:0; visibility:hidden;" />\n        <!--<![endif]-->');
  });

  if ($('.mj-menu-trigger').length) {
    $('head').append('<style type="text/css">\n        noinput.mj-menu-checkbox { display:block!important; max-height:none!important
; visibility:visible!important; }\n\n        @media only screen and (max-width:480px) {\n          .mj-menu-checkbox[type="checkbox"] ~ .mj-inline-links { display:none!important; }\n          .mj-menu-checkbox[type="checkbox"]:checked ~ .mj-inline-links,\n          .mj-menu-checkbox[type="checkbox"] ~ .mj-menu-trigger { display:block!important; max-width:none!important; max-height:none!important; font-size:inherit!important; }\n          .mj-menu-checkbox[type="checkbox"] ~ .mj-inline-links > a { display:block!important; }\n          .mj-menu-checkbox[type="checkbox"]:checked ~ .mj-menu-trigger .mj-menu-icon-close { display:block!important; }\n          .mj-menu-checkbox[type="checkbox"]:checked ~ .mj-menu-trigger .mj-menu-icon-open { display:none!important; }\n        }\n      </style>');
  }

  return $;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mjml.elements.mj-link"></a>[module mjml.elements.mj-link](#apidoc.module.mjml.elements.mj-link)

#### <a name="apidoc.element.mjml.elements.mj-link.mj-link"></a>[function <span class="apidocSignatureSpan">mjml.elements.</span>mj-link (props)](#apidoc.element.mjml.elements.mj-link.mj-link)
- description and source-code
```javascript
function MJMLElement(props) {
  _classCallCheck(this, MJMLElement);

  var _this = _possibleConstructorReturn(this, (MJMLElement.__proto__ || Object.getPrototypeOf(MJMLElement)).call(this, props));

  _this.mjAttribute = function (name) {
    return _this.mjml.getIn(['attributes', name]);
  };

  _this.mjName = function () {
    return _this.constructor.tagName;
  };

  _this.mjContent = function () {
    var content = _this.mjml.get('content');

    if (content) {
      return (0, _trim2.default)(content);
    }

    return _react2.default.Children.map(_this.props.children, function (child) {
      if (typeof child === 'string') {
        return child;
      }
      return _server2.default.renderToStaticMarkup(child);
    });
  };

  _this.isInheritedAttributes = function (name) {
    return _this.mjml.get('inheritedAttributes') && _this.mjml.get('inheritedAttributes').includes(name);
  };

  _this.getWidth = function () {
    return _this.mjAttribute('rawPxWidth') || _this.mjAttribute('width');
  };

  _this.getParentWidth = function () {
    return _this.mjAttribute('parentWidth');
  };

  _this.renderWrappedOutlookChildren = function (children) {
    children = _react2.default.Children.toArray(children);

    var realChildren = children.filter(function (child) {
      return !child.props.mjml || child.props.mjml.get('tagName') !== 'mj-raw';
    });

    var prefix = _this.mjName() + '-outlook';
    var parentWidth = _this.getWidth();
    var siblings = realChildren.length;
    var elementsWidth = realChildren.map(function (element) {
      if (_this.isInheritedAttributes('width')) {
        return parseInt(parentWidth);
      }

      return getElementWidth({ element: element, siblings: siblings, parentWidth: parentWidth });
    });

    var wrappedElements = [];

    if (siblings == 0) {
      return wrappedElements;
    }

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-open', className: prefix + '-open', 'data-width':
elementsWidth[0] }));

    var i = 0;

    children.forEach(function (child) {
      var childProps = Object.assign({}, child.props);

      if (childProps.mjml) {
        childProps.mjml = childProps.mjml.setIn(['attributes', 'rawPxWidth'], elementsWidth[i]);

        if (_this.mjml.get('inheritedAttributes')) {
          childProps.mjml = childProps.mjml.mergeIn(['attributes', _this.inheritedAttributes()]);
        }
      } else {
        Object.assign(childProps, { rawPxWidth: elementsWidth[i] });

        if (_this.mjml.get('inheritedAttributes')) {
          Object.assign(childProps, _this.inheritedAttributes());
        }
      }

      var childWithProps = _react2.default.cloneElement(child, childProps);

      wrappedElements.push(childWithProps);
      if (!childWithProps.type.rawElement && i < realChildren.length - 1) {
        wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-' + i, className: prefix + '-line', 'data-width
': elementsWidth[++i] }));
      }
    });

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-close', className: prefix + '-close' }));

    return wrappedElements;
  };

  _this.paddingParser = function (direction) {
    var prefix = arguments.length > 1 && arguments[1] !== undefined ? arguments[1] : '';

    var paddingDirection = _this.mjAttribute(prefix + 'padding-' + direction);
    var padding = _this.mjAttribute(prefix + 'padding');

    if (paddingDirection != null) {
      return parseInt(paddingDirection);
    }

    if (!padding) {
      return 0;
    }

    var paddings = padding.split(' ');
    var directions = {};

    switch (paddings.length) {
      case 1:
        return parseInt(padding);
      case 2:
        directions = { top: 0, bottom: 0, left: 1, right: 1 };
        break;
      case 3:
        directions = { top: 0, left: 1, right: 1, bottom: 2 };
        break;
      case 4:
        directions = { top: 0, right: 1, bottom: 2, left: 3 };
        break;
    }

    return parseInt(paddings[directions[direction]] || 0);
  };

  _this.mjml = props.mjml || _immutable2. ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mjml.elements.mj-link.postRender"></a>[function <span class="apidocSignatureSpan">mjml.elements.mj-link.</span>postRender ($)](#apidoc.element.mjml.elements.mj-link.postRender)
- description and source-code
```javascript
function postRender($) {
  $('.mj-link').each(function () {
    $(this).before('<!--[if gte mso 9]>\n          <td style="padding: ' + $(this).data('padding') + '">\n        <![endif]-->').
after('<!--[if gte mso 9]>\n          </td>\n        <![endif]-->').removeAttr('data-padding').removeAttr('class');
  });

  return $;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mjml.elements.mj-raw"></a>[module mjml.elements.mj-raw](#apidoc.module.mjml.elements.mj-raw)

#### <a name="apidoc.element.mjml.elements.mj-raw.mj-raw"></a>[function <span class="apidocSignatureSpan">mjml.elements.</span>mj-raw (props)](#apidoc.element.mjml.elements.mj-raw.mj-raw)
- description and source-code
```javascript
function MJMLElement(props) {
  _classCallCheck(this, MJMLElement);

  var _this = _possibleConstructorReturn(this, (MJMLElement.__proto__ || Object.getPrototypeOf(MJMLElement)).call(this, props));

  _this.mjAttribute = function (name) {
    return _this.mjml.getIn(['attributes', name]);
  };

  _this.mjName = function () {
    return _this.constructor.tagName;
  };

  _this.mjContent = function () {
    var content = _this.mjml.get('content');

    if (content) {
      return (0, _trim2.default)(content);
    }

    return _react2.default.Children.map(_this.props.children, function (child) {
      if (typeof child === 'string') {
        return child;
      }
      return _server2.default.renderToStaticMarkup(child);
    });
  };

  _this.isInheritedAttributes = function (name) {
    return _this.mjml.get('inheritedAttributes') && _this.mjml.get('inheritedAttributes').includes(name);
  };

  _this.getWidth = function () {
    return _this.mjAttribute('rawPxWidth') || _this.mjAttribute('width');
  };

  _this.getParentWidth = function () {
    return _this.mjAttribute('parentWidth');
  };

  _this.renderWrappedOutlookChildren = function (children) {
    children = _react2.default.Children.toArray(children);

    var realChildren = children.filter(function (child) {
      return !child.props.mjml || child.props.mjml.get('tagName') !== 'mj-raw';
    });

    var prefix = _this.mjName() + '-outlook';
    var parentWidth = _this.getWidth();
    var siblings = realChildren.length;
    var elementsWidth = realChildren.map(function (element) {
      if (_this.isInheritedAttributes('width')) {
        return parseInt(parentWidth);
      }

      return getElementWidth({ element: element, siblings: siblings, parentWidth: parentWidth });
    });

    var wrappedElements = [];

    if (siblings == 0) {
      return wrappedElements;
    }

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-open', className: prefix + '-open', 'data-width':
elementsWidth[0] }));

    var i = 0;

    children.forEach(function (child) {
      var childProps = Object.assign({}, child.props);

      if (childProps.mjml) {
        childProps.mjml = childProps.mjml.setIn(['attributes', 'rawPxWidth'], elementsWidth[i]);

        if (_this.mjml.get('inheritedAttributes')) {
          childProps.mjml = childProps.mjml.mergeIn(['attributes', _this.inheritedAttributes()]);
        }
      } else {
        Object.assign(childProps, { rawPxWidth: elementsWidth[i] });

        if (_this.mjml.get('inheritedAttributes')) {
          Object.assign(childProps, _this.inheritedAttributes());
        }
      }

      var childWithProps = _react2.default.cloneElement(child, childProps);

      wrappedElements.push(childWithProps);
      if (!childWithProps.type.rawElement && i < realChildren.length - 1) {
        wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-' + i, className: prefix + '-line', 'data-width
': elementsWidth[++i] }));
      }
    });

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-close', className: prefix + '-close' }));

    return wrappedElements;
  };

  _this.paddingParser = function (direction) {
    var prefix = arguments.length > 1 && arguments[1] !== undefined ? arguments[1] : '';

    var paddingDirection = _this.mjAttribute(prefix + 'padding-' + direction);
    var padding = _this.mjAttribute(prefix + 'padding');

    if (paddingDirection != null) {
      return parseInt(paddingDirection);
    }

    if (!padding) {
      return 0;
    }

    var paddings = padding.split(' ');
    var directions = {};

    switch (paddings.length) {
      case 1:
        return parseInt(padding);
      case 2:
        directions = { top: 0, bottom: 0, left: 1, right: 1 };
        break;
      case 3:
        directions = { top: 0, left: 1, right: 1, bottom: 2 };
        break;
      case 4:
        directions = { top: 0, right: 1, bottom: 2, left: 3 };
        break;
    }

    return parseInt(paddings[directions[direction]] || 0);
  };

  _this.mjml = props.mjml || _immutable2. ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mjml.elements.mj-raw.postRender"></a>[function <span class="apidocSignatureSpan">mjml.elements.mj-raw.</span>postRender ($)](#apidoc.element.mjml.elements.mj-raw.postRender)
- description and source-code
```javascript
function postRender($) {
  $('.mj-raw').each(function () {
    $(this).replaceWith($(this).html());
  });

  return $;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mjml.elements.mj-section"></a>[module mjml.elements.mj-section](#apidoc.module.mjml.elements.mj-section)

#### <a name="apidoc.element.mjml.elements.mj-section.mj-section"></a>[function <span class="apidocSignatureSpan">mjml.elements.</span>mj-section (props)](#apidoc.element.mjml.elements.mj-section.mj-section)
- description and source-code
```javascript
function MJMLElement(props) {
  _classCallCheck(this, MJMLElement);

  var _this = _possibleConstructorReturn(this, (MJMLElement.__proto__ || Object.getPrototypeOf(MJMLElement)).call(this, props));

  _this.mjAttribute = function (name) {
    return _this.mjml.getIn(['attributes', name]);
  };

  _this.mjName = function () {
    return _this.constructor.tagName;
  };

  _this.mjContent = function () {
    var content = _this.mjml.get('content');

    if (content) {
      return (0, _trim2.default)(content);
    }

    return _react2.default.Children.map(_this.props.children, function (child) {
      if (typeof child === 'string') {
        return child;
      }
      return _server2.default.renderToStaticMarkup(child);
    });
  };

  _this.isInheritedAttributes = function (name) {
    return _this.mjml.get('inheritedAttributes') && _this.mjml.get('inheritedAttributes').includes(name);
  };

  _this.getWidth = function () {
    return _this.mjAttribute('rawPxWidth') || _this.mjAttribute('width');
  };

  _this.getParentWidth = function () {
    return _this.mjAttribute('parentWidth');
  };

  _this.renderWrappedOutlookChildren = function (children) {
    children = _react2.default.Children.toArray(children);

    var realChildren = children.filter(function (child) {
      return !child.props.mjml || child.props.mjml.get('tagName') !== 'mj-raw';
    });

    var prefix = _this.mjName() + '-outlook';
    var parentWidth = _this.getWidth();
    var siblings = realChildren.length;
    var elementsWidth = realChildren.map(function (element) {
      if (_this.isInheritedAttributes('width')) {
        return parseInt(parentWidth);
      }

      return getElementWidth({ element: element, siblings: siblings, parentWidth: parentWidth });
    });

    var wrappedElements = [];

    if (siblings == 0) {
      return wrappedElements;
    }

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-open', className: prefix + '-open', 'data-width':
elementsWidth[0] }));

    var i = 0;

    children.forEach(function (child) {
      var childProps = Object.assign({}, child.props);

      if (childProps.mjml) {
        childProps.mjml = childProps.mjml.setIn(['attributes', 'rawPxWidth'], elementsWidth[i]);

        if (_this.mjml.get('inheritedAttributes')) {
          childProps.mjml = childProps.mjml.mergeIn(['attributes', _this.inheritedAttributes()]);
        }
      } else {
        Object.assign(childProps, { rawPxWidth: elementsWidth[i] });

        if (_this.mjml.get('inheritedAttributes')) {
          Object.assign(childProps, _this.inheritedAttributes());
        }
      }

      var childWithProps = _react2.default.cloneElement(child, childProps);

      wrappedElements.push(childWithProps);
      if (!childWithProps.type.rawElement && i < realChildren.length - 1) {
        wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-' + i, className: prefix + '-line', 'data-width
': elementsWidth[++i] }));
      }
    });

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-close', className: prefix + '-close' }));

    return wrappedElements;
  };

  _this.paddingParser = function (direction) {
    var prefix = arguments.length > 1 && arguments[1] !== undefined ? arguments[1] : '';

    var paddingDirection = _this.mjAttribute(prefix + 'padding-' + direction);
    var padding = _this.mjAttribute(prefix + 'padding');

    if (paddingDirection != null) {
      return parseInt(paddingDirection);
    }

    if (!padding) {
      return 0;
    }

    var paddings = padding.split(' ');
    var directions = {};

    switch (paddings.length) {
      case 1:
        return parseInt(padding);
      case 2:
        directions = { top: 0, bottom: 0, left: 1, right: 1 };
        break;
      case 3:
        directions = { top: 0, left: 1, right: 1, bottom: 2 };
        break;
      case 4:
        directions = { top: 0, right: 1, bottom: 2, left: 3 };
        break;
    }

    return parseInt(paddings[directions[direction]] || 0);
  };

  _this.mjml = props.mjml || _immutable2. ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mjml.elements.mj-section.postRender"></a>[function <span class="apidocSignatureSpan">mjml.elements.mj-section.</span>postRender ($)](#apidoc.element.mjml.elements.mj-section.postRender)
- description and source-code
```javascript
function postRender($) {
  $('.mj-section-outlook-background').each(function () {
    var url = $(this).data('url');
    var width = parseInt($(this).data('width'));

    $(this).removeAttr('class').removeAttr('data-url').removeAttr('data-width');

    if (!url) {
      return;
    }

    $(this).before(_mjmlCore.helpers.startConditionalTag + '\n      <v:rect xmlns:v="urn:schemas-microsoft-com:vml" fill="true"
stroke="false" style="width:' + width + 'px;">\n        <v:fill origin="0.5, 0" position="0.5,0" type="tile" src="' + url + '" />\n        <v:textbox style="mso-fit-shape-to-text:true" inset="0,0,0,0">\n      ' + _mjmlCore.helpers.endConditionalTag);

    $(this).after(_mjmlCore.helpers.startConditionalTag + '\n        </v:textbox>\n      </v:rect>\n      ' + _mjmlCore.helpers.
endConditionalTag);
  });

  $('.mj-section-outlook-open').each(function () {
    var $columnDiv = $(this).next();

    $(this).replaceWith(_mjmlCore.helpers.startConditionalTag + '\n      <table role="presentation" border="0" cellpadding="0" cellspacing
="0"><tr><td style="vertical-align:' + $columnDiv.data('vertical-align') + ';width:' + parseInt($(this).data('width')) + 'px;">\n      ' + _mjmlCore.helpers.endConditionalTag);

    $columnDiv.removeAttr('data-vertical-align');
  });

  $('.mj-section-outlook-line').each(function () {
    var $columnDiv = $(this).next();
    var width = parseInt($(this).data('width'));

    $(this).replaceWith(_mjmlCore.helpers.startConditionalTag + '\n      </td><td style="vertical-align:' + $columnDiv.data('vertical
-align') + ';width:' + width + 'px;">\n      ' + _mjmlCore.helpers.endConditionalTag);

    $columnDiv.removeAttr('data-vertical-align');
  });

  $('.mj-section-outlook-close').each(function () {
    $(this).replaceWith(_mjmlCore.helpers.startConditionalTag + '\n      </td></tr></table>\n      ' + _mjmlCore.helpers.endConditionalTag
);
  });

  return $;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mjml.elements.mj-social"></a>[module mjml.elements.mj-social](#apidoc.module.mjml.elements.mj-social)

#### <a name="apidoc.element.mjml.elements.mj-social.mj-social"></a>[function <span class="apidocSignatureSpan">mjml.elements.</span>mj-social (props)](#apidoc.element.mjml.elements.mj-social.mj-social)
- description and source-code
```javascript
function MJMLElement(props) {
  _classCallCheck(this, MJMLElement);

  var _this = _possibleConstructorReturn(this, (MJMLElement.__proto__ || Object.getPrototypeOf(MJMLElement)).call(this, props));

  _this.mjAttribute = function (name) {
    return _this.mjml.getIn(['attributes', name]);
  };

  _this.mjName = function () {
    return _this.constructor.tagName;
  };

  _this.mjContent = function () {
    var content = _this.mjml.get('content');

    if (content) {
      return (0, _trim2.default)(content);
    }

    return _react2.default.Children.map(_this.props.children, function (child) {
      if (typeof child === 'string') {
        return child;
      }
      return _server2.default.renderToStaticMarkup(child);
    });
  };

  _this.isInheritedAttributes = function (name) {
    return _this.mjml.get('inheritedAttributes') && _this.mjml.get('inheritedAttributes').includes(name);
  };

  _this.getWidth = function () {
    return _this.mjAttribute('rawPxWidth') || _this.mjAttribute('width');
  };

  _this.getParentWidth = function () {
    return _this.mjAttribute('parentWidth');
  };

  _this.renderWrappedOutlookChildren = function (children) {
    children = _react2.default.Children.toArray(children);

    var realChildren = children.filter(function (child) {
      return !child.props.mjml || child.props.mjml.get('tagName') !== 'mj-raw';
    });

    var prefix = _this.mjName() + '-outlook';
    var parentWidth = _this.getWidth();
    var siblings = realChildren.length;
    var elementsWidth = realChildren.map(function (element) {
      if (_this.isInheritedAttributes('width')) {
        return parseInt(parentWidth);
      }

      return getElementWidth({ element: element, siblings: siblings, parentWidth: parentWidth });
    });

    var wrappedElements = [];

    if (siblings == 0) {
      return wrappedElements;
    }

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-open', className: prefix + '-open', 'data-width':
elementsWidth[0] }));

    var i = 0;

    children.forEach(function (child) {
      var childProps = Object.assign({}, child.props);

      if (childProps.mjml) {
        childProps.mjml = childProps.mjml.setIn(['attributes', 'rawPxWidth'], elementsWidth[i]);

        if (_this.mjml.get('inheritedAttributes')) {
          childProps.mjml = childProps.mjml.mergeIn(['attributes', _this.inheritedAttributes()]);
        }
      } else {
        Object.assign(childProps, { rawPxWidth: elementsWidth[i] });

        if (_this.mjml.get('inheritedAttributes')) {
          Object.assign(childProps, _this.inheritedAttributes());
        }
      }

      var childWithProps = _react2.default.cloneElement(child, childProps);

      wrappedElements.push(childWithProps);
      if (!childWithProps.type.rawElement && i < realChildren.length - 1) {
        wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-' + i, className: prefix + '-line', 'data-width
': elementsWidth[++i] }));
      }
    });

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-close', className: prefix + '-close' }));

    return wrappedElements;
  };

  _this.paddingParser = function (direction) {
    var prefix = arguments.length > 1 && arguments[1] !== undefined ? arguments[1] : '';

    var paddingDirection = _this.mjAttribute(prefix + 'padding-' + direction);
    var padding = _this.mjAttribute(prefix + 'padding');

    if (paddingDirection != null) {
      return parseInt(paddingDirection);
    }

    if (!padding) {
      return 0;
    }

    var paddings = padding.split(' ');
    var directions = {};

    switch (paddings.length) {
      case 1:
        return parseInt(padding);
      case 2:
        directions = { top: 0, bottom: 0, left: 1, right: 1 };
        break;
      case 3:
        directions = { top: 0, left: 1, right: 1, bottom: 2 };
        break;
      case 4:
        directions = { top: 0, right: 1, bottom: 2, left: 3 };
        break;
    }

    return parseInt(paddings[directions[direction]] || 0);
  };

  _this.mjml = props.mjml || _immutable2. ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mjml.elements.mj-social.postRender"></a>[function <span class="apidocSignatureSpan">mjml.elements.mj-social.</span>postRender ($)](#apidoc.element.mjml.elements.mj-social.postRender)
- description and source-code
```javascript
function postRender($) {
  $('.mj-social-outlook-open').each(function () {
    $(this).replaceWith(_mjmlCore.helpers.startConditionalTag + '\n      <table role="presentation" border="0" cellpadding="0" cellspacing
="0" align="' + $(this).data('align') + '"><tr><td>\n      ' + _mjmlCore.helpers.endConditionalTag);
  });

  $('.mj-social-outlook-line').each(function () {
    $(this).replaceWith(_mjmlCore.helpers.startConditionalTag + '\n      </td><td>\n      ' + _mjmlCore.helpers.endConditionalTag
);
  });

  $('.mj-social-outlook-close').each(function () {
    $(this).replaceWith(_mjmlCore.helpers.startConditionalTag + '\n      </td></tr></table>\n      ' + _mjmlCore.helpers.endConditionalTag
);
  });

  return $;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mjml.elements.mj-text"></a>[module mjml.elements.mj-text](#apidoc.module.mjml.elements.mj-text)

#### <a name="apidoc.element.mjml.elements.mj-text.mj-text"></a>[function <span class="apidocSignatureSpan">mjml.elements.</span>mj-text (props)](#apidoc.element.mjml.elements.mj-text.mj-text)
- description and source-code
```javascript
function MJMLElement(props) {
  _classCallCheck(this, MJMLElement);

  var _this = _possibleConstructorReturn(this, (MJMLElement.__proto__ || Object.getPrototypeOf(MJMLElement)).call(this, props));

  _this.mjAttribute = function (name) {
    return _this.mjml.getIn(['attributes', name]);
  };

  _this.mjName = function () {
    return _this.constructor.tagName;
  };

  _this.mjContent = function () {
    var content = _this.mjml.get('content');

    if (content) {
      return (0, _trim2.default)(content);
    }

    return _react2.default.Children.map(_this.props.children, function (child) {
      if (typeof child === 'string') {
        return child;
      }
      return _server2.default.renderToStaticMarkup(child);
    });
  };

  _this.isInheritedAttributes = function (name) {
    return _this.mjml.get('inheritedAttributes') && _this.mjml.get('inheritedAttributes').includes(name);
  };

  _this.getWidth = function () {
    return _this.mjAttribute('rawPxWidth') || _this.mjAttribute('width');
  };

  _this.getParentWidth = function () {
    return _this.mjAttribute('parentWidth');
  };

  _this.renderWrappedOutlookChildren = function (children) {
    children = _react2.default.Children.toArray(children);

    var realChildren = children.filter(function (child) {
      return !child.props.mjml || child.props.mjml.get('tagName') !== 'mj-raw';
    });

    var prefix = _this.mjName() + '-outlook';
    var parentWidth = _this.getWidth();
    var siblings = realChildren.length;
    var elementsWidth = realChildren.map(function (element) {
      if (_this.isInheritedAttributes('width')) {
        return parseInt(parentWidth);
      }

      return getElementWidth({ element: element, siblings: siblings, parentWidth: parentWidth });
    });

    var wrappedElements = [];

    if (siblings == 0) {
      return wrappedElements;
    }

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-open', className: prefix + '-open', 'data-width':
elementsWidth[0] }));

    var i = 0;

    children.forEach(function (child) {
      var childProps = Object.assign({}, child.props);

      if (childProps.mjml) {
        childProps.mjml = childProps.mjml.setIn(['attributes', 'rawPxWidth'], elementsWidth[i]);

        if (_this.mjml.get('inheritedAttributes')) {
          childProps.mjml = childProps.mjml.mergeIn(['attributes', _this.inheritedAttributes()]);
        }
      } else {
        Object.assign(childProps, { rawPxWidth: elementsWidth[i] });

        if (_this.mjml.get('inheritedAttributes')) {
          Object.assign(childProps, _this.inheritedAttributes());
        }
      }

      var childWithProps = _react2.default.cloneElement(child, childProps);

      wrappedElements.push(childWithProps);
      if (!childWithProps.type.rawElement && i < realChildren.length - 1) {
        wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-' + i, className: prefix + '-line', 'data-width
': elementsWidth[++i] }));
      }
    });

    wrappedElements.push(_react2.default.createElement('div', { key: 'outlook-close', className: prefix + '-close' }));

    return wrappedElements;
  };

  _this.paddingParser = function (direction) {
    var prefix = arguments.length > 1 && arguments[1] !== undefined ? arguments[1] : '';

    var paddingDirection = _this.mjAttribute(prefix + 'padding-' + direction);
    var padding = _this.mjAttribute(prefix + 'padding');

    if (paddingDirection != null) {
      return parseInt(paddingDirection);
    }

    if (!padding) {
      return 0;
    }

    var paddings = padding.split(' ');
    var directions = {};

    switch (paddings.length) {
      case 1:
        return parseInt(padding);
      case 2:
        directions = { top: 0, bottom: 0, left: 1, right: 1 };
        break;
      case 3:
        directions = { top: 0, left: 1, right: 1, bottom: 2 };
        break;
      case 4:
        directions = { top: 0, right: 1, bottom: 2, left: 3 };
        break;
    }

    return parseInt(paddings[directions[direction]] || 0);
  };

  _this.mjml = props.mjml || _immutable2. ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mjml.elements.mj-text.postRender"></a>[function <span class="apidocSignatureSpan">mjml.elements.mj-text.</span>postRender ($)](#apidoc.element.mjml.elements.mj-text.postRender)
- description and source-code
```javascript
function postRender($) {
  $('.mj-text-height').each(function () {

    var height = parseInt($(this).css('height'));

    $(_mjmlCore.helpers.startConditionalTag + '\n      <table role="presentation" border="0" cellpadding="0" cellspacing="0"><tr
><td height="' + height + '" style="vertical-align:top;height:' + height + 'px;">\n      ' + _mjmlCore.helpers.endConditionalTag).insertBefore($(this));

    $(_mjmlCore.helpers.startConditionalTag + '\n      </td></tr></table>\n      ' + _mjmlCore.helpers.endConditionalTag).insertAfter
($(this));
    $(this).removeClass('mj-text-height').filter('[class=""]').removeAttr('class');
  });
  return $;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mjml.elements.mj-wrapper"></a>[module mjml.elements.mj-wrapper](#apidoc.module.mjml.elements.mj-wrapper)

#### <a name="apidoc.element.mjml.elements.mj-wrapper.mj-wrapper"></a>[function <span class="apidocSignatureSpan">mjml.elements.</span>mj-wrapper ()](#apidoc.element.mjml.elements.mj-wrapper.mj-wrapper)
- description and source-code
```javascript
function Wrapper() {
  _classCallCheck(this, Wrapper);

  return _possibleConstructorReturn(this, (Wrapper.__proto__ || Object.getPrototypeOf(Wrapper)).apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mjml.elements.mj-wrapper.postRender"></a>[function <span class="apidocSignatureSpan">mjml.elements.mj-wrapper.</span>postRender ($)](#apidoc.element.mjml.elements.mj-wrapper.postRender)
- description and source-code
```javascript
function postRender($) {
  $('.mj-wrapper-outlook-open').each(function () {
    $(this).replaceWith(_mjmlCore.helpers.startConditionalTag + '\n      <table role="presentation" border="0" cellpadding="0" cellspacing
="0"><tr><td style="width:' + parseInt($(this).data('width')) + 'px;">\n      ' + _mjmlCore.helpers.endConditionalTag);
  });

  $('.mj-wrapper-outlook-line').each(function () {
    var width = parseInt($(this).data('width'));

    $(this).replaceWith(_mjmlCore.helpers.startConditionalTag + '\n      </td></tr><tr><td style="width:' + width + 'px;">\n      ' +
_mjmlCore.helpers.endConditionalTag);
  });

  $('.mj-wrapper-outlook-close').each(function () {
    $(this).replaceWith(_mjmlCore.helpers.startConditionalTag + '\n      </td></tr></table>\n      ' + _mjmlCore.helpers.endConditionalTag
);
  });

  return $;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mjml.helpers"></a>[module mjml.helpers](#apidoc.module.mjml.helpers)

#### <a name="apidoc.element.mjml.helpers.defaultUnit"></a>[function <span class="apidocSignatureSpan">mjml.helpers.</span>defaultUnit (units)](#apidoc.element.mjml.helpers.defaultUnit)
- description and source-code
```javascript
function defaultUnit(units) {
  var defaultUnit = arguments.length > 1 && arguments[1] !== undefined ? arguments[1] : 'px';

  if (units === undefined || units === '' || units === null) {
    return undefined;
  }

  return units.toString().split(' ').map(function (unit) {
    var parsedUnit = unitRegex.exec(unit.toString())[1];
    return parsedUnit ? unit : unit.toString() + defaultUnit;
  }).join(' ');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mjml.helpers.merge"></a>[function <span class="apidocSignatureSpan">mjml.helpers.</span>merge ()](#apidoc.element.mjml.helpers.merge)
- description and source-code
```javascript
function merge() {
  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _mergeWith2.default.apply(undefined, args.concat([function (prev, next) {
    if (next == undefined) {
      return prev;
    }

    if (prev == undefined) {
      return next;
    }

    if ((typeof prev === 'undefined' ? 'undefined' : _typeof(prev)) == 'object' && (typeof next === 'undefined' ? 'undefined' :
_typeof(next)) == 'object') {
      return merge({}, prev, next);
    }

    return next;
  }]));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mjml.helpers.widthParser"></a>[function <span class="apidocSignatureSpan">mjml.helpers.</span>widthParser (width)](#apidoc.element.mjml.helpers.widthParser)
- description and source-code
```javascript
function widthParser(width) {
  var opts = arguments.length > 1 && arguments[1] !== undefined ? arguments[1] : { parseFloatToInt: true };

  var widthUnit = unitRegex.exec(width.toString())[1];
  var unitParsers = { default: parseInt, px: parseInt, '%': opts.parseFloatToInt ? parseInt : parseFloat };
  var widthParser = unitParsers[widthUnit] || unitParsers['default'];

  return { unit: widthUnit || 'px', width: widthParser(width) };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mjml.helpers.dom"></a>[module mjml.helpers.dom](#apidoc.module.mjml.helpers.dom)

#### <a name="apidoc.element.mjml.helpers.dom.getAttributes"></a>[function <span class="apidocSignatureSpan">mjml.helpers.dom.</span>getAttributes (element)](#apidoc.element.mjml.helpers.dom.getAttributes)
- description and source-code
```javascript
getAttributes = function (element) {
  return element.attribs || {};
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mjml.helpers.dom.getChildren"></a>[function <span class="apidocSignatureSpan">mjml.helpers.dom.</span>getChildren (element)](#apidoc.element.mjml.helpers.dom.getChildren)
- description and source-code
```javascript
getChildren = function (element) {
  return element.childNodes;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mjml.helpers.dom.getHTML"></a>[function <span class="apidocSignatureSpan">mjml.helpers.dom.</span>getHTML ($)](#apidoc.element.mjml.helpers.dom.getHTML)
- description and source-code
```javascript
getHTML = function ($) {
  return $().html();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mjml.helpers.dom.parseHTML"></a>[function <span class="apidocSignatureSpan">mjml.helpers.dom.</span>parseHTML (str)](#apidoc.element.mjml.helpers.dom.parseHTML)
- description and source-code
```javascript
parseHTML = function (str) {
  return _parseMarkup(str, { xmlMode: false, decodeEntities: false });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mjml.helpers.dom.parseXML"></a>[function <span class="apidocSignatureSpan">mjml.helpers.dom.</span>parseXML (str)](#apidoc.element.mjml.helpers.dom.parseXML)
- description and source-code
```javascript
parseXML = function (str) {
  return _parseMarkup(str, { xmlMode: true, decodeEntities: false, withStartIndices: true });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mjml.helpers.dom.replaceContentByCdata"></a>[function <span class="apidocSignatureSpan">mjml.helpers.dom.</span>replaceContentByCdata (tag)](#apidoc.element.mjml.helpers.dom.replaceContentByCdata)
- description and source-code
```javascript
replaceContentByCdata = function (tag) {
  return '<' + tag + '$1><![CDATA[$2]]></' + tag + '>';
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mjml.rulesCollection"></a>[module mjml.rulesCollection](#apidoc.module.mjml.rulesCollection)

#### <a name="apidoc.element.mjml.rulesCollection.validChildren"></a>[function <span class="apidocSignatureSpan">mjml.rulesCollection.</span>validChildren (element)](#apidoc.element.mjml.rulesCollection.validChildren)
- description and source-code
```javascript
function validChildren(element) {
  var children = element.children,
      tagName = element.tagName;

  var Component = _mjmlCore.elements[tagName];

  if (!Component) {
    return;
  }

  if (!children || children.length == 0) {
    return;
  }

  return (0, _filter2.default)(children.map(function (child) {
    var childTagName = child.tagName;
    var ChildComponent = _mjmlCore.elements[childTagName];

    if (!ChildComponent) {
      return null;
    }

    if ((0, _includes2.default)(ChildComponent.parentTag, tagName)) {
      return null;
    }

    return (0, _ruleError2.default)(ChildComponent.tagName + ' cannot be used inside ' + tagName + ', only inside: ' + ChildComponent
.parentTag.join(', '), child);
  }));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mjml.rulesCollection.validateAttribute"></a>[function <span class="apidocSignatureSpan">mjml.rulesCollection.</span>validateAttribute (element)](#apidoc.element.mjml.rulesCollection.validateAttribute)
- description and source-code
```javascript
function validateAttribute(element) {
  var attributes = element.attributes,
      tagName = element.tagName;

  var Component = _mjmlCore.elements[tagName];

  if (!Component) {
    return;
  }

  var availableAttributes = (0, _concat2.default)((0, _keys2.default)(Component.defaultMJMLDefinition.attributes), WHITELIST);
  var unknownAttributes = (0, _filter2.default)((0, _keys2.default)(attributes), function (attribute) {
    return !(0, _includes2.default)(availableAttributes, attribute);
  });

  if (unknownAttributes.length == 0) {
    return;
  }

  return (0, _ruleError2.default)((unknownAttributes.length > 1 ? "Attributes" : "Attribute") + ' ' + unknownAttributes.join(', ') + ' ' + (
unknownAttributes.length > 1 ? "are illegal" : "is illegal"), element);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mjml.rulesCollection.validateTag"></a>[function <span class="apidocSignatureSpan">mjml.rulesCollection.</span>validateTag (element)](#apidoc.element.mjml.rulesCollection.validateTag)
- description and source-code
```javascript
function validateTag(element) {
  var tagName = element.tagName;

  var Component = _mjmlCore.elements[tagName];

  if (!Component) {
    return (0, _ruleError2.default)('Element ' + tagName + ' doesn\'t exist or is not registered', element);
  }
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
