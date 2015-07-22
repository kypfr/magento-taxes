# magento-taxes

This project provide import files for Magento, especially for taxes rules.

## checkout 

git clone git@github.com:kypfr/magento-taxes.git

## files content

### Europ

* General EU VAT taxes: ([Source](http://fr.wikipedia.org/wiki/TVA_dans_l%27Union_europ%C3%A9enne))
* Monaco VAT rules for Monaco: ([Source]( http://service-public-entreprises.gouv.mc/Fiscalite/TVA/Declarations/TVA))
* Isle of Man VAT rules : ([Source](https://fr.wikipedia.org/wiki/%C3%8Ele_de_Man))
* Gibraltar VAT rules: ([Source](https://en.wikipedia.org/wiki/Taxation_in_Gibraltar))
* Canaries Islands VAT rules  ([Source](http://ec.europa.eu/taxation_customs/taxation/other_taxes/canary_islands/index_fr.htm), [IGIC](http://www.spainbusiness.fr/icex/cda/controller/frances/0,7573,5213352_5214167_5395224_554537_FR,00.html)) 

### USA

* General VAT rates per state: ([Source: summary table content only of this wikipedia article](https://en.wikipedia.org/wiki/Sales_taxes_in_the_United_States))

## usage

* go to your back-office > sales > tax > Import / Export taxes rates
* Change locale to English (US)
* Import required files
* Restore your locale if required

See [this blog post](https://blog.kyp.fr/how-to-solve-message-invalid-file-format-upload-attempt-when-importing-magento-taxes-file/ "Locale usage when importing VAT files") for more information.

## TODO

* Manage VAT for GB mimitary base on Chypre
* Manage custom VAT rules for USA described on the wikipedia article
