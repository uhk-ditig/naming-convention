# Naming Convention for Document Filing

This repository contains files and instructions to complement the [file naming convention for document filing](https://www.ditig.com/publications/naming-convention) article on the UHK website.


## SYNOPSIS

`DATE`\_`TYPE`\_`CREATOR`\_`RECIPIENT`\_`DESCRIPTION`.`FILE-EXTENSION`


* **DATE**  
  Document creation date `YYYY-MM-DD`.
* **TYPE**  
  [Predefined](#types-and-examples)
* **CREATOR**  
  Creator/issuer/sender of the document
* **RECIPIENT**  
  Recipient of the document (optional)
* **DESCRIPTION**  
  May include subject, invoice numbers, order numbers, customer numbers, etc.
* **FILE EXTENSION**  
  File type extension, e.g. `.pdf`, `.txt`, etc.

All parts of a file name are ...

* chained together using underscores
* written so that spaces are replaced by dashes (`-`)
* written in **all lowercase** UTF-8 character set


## TYPES and Examples

### `invoice`

For all invoice documents.

`yyyy-mm-dd_invoice_creator_recipient_description-invoice-number.pdf`

**Example:**

`2024-10-21_invoice_sofa-king-inc_john-doe_cushy-king-couch-8979803411.pdf`


---


### `receipt`

For all receipt documents, e.g. cash receipts.

`yyyy-mm-dd_receipt_creator_recipient_description-receipt-id.pdf`

**Example:**

`2024-10-12_receipt_thai-tanic_john-doe_dinner-with-acme-inc-89720984.pdf`


---


### `certificate`

For, e.g. Birth certificate, school certificates, etc.

`yyyy-mm-dd_certificate_creator_recipient_description.pdf`

**Example:**

`yyyy-mm-dd_certificate_mirthful-maternity-clinic_recipient_birth-certificate.pdf`


---


### `letter`

For all general communication documents.

`yyyy-mm-dd_letter_creator_recipient_description(-identifier).pdf`

**Example:**

`2024-03-31_letter_penurious-bank-inc_john-doe_bank-account-statement-2024-03-xx75512108001245126199.pdf`


---


### `contract`

For, e.g. rental agreements, employment contracts, mandates, etc.

`yyyy-mm-dd_contract_creator_recipient_description.pdf`

**Example:**

`2020-02-02_contract_gongshow-inc_john-doe_employment-contract.pdf`


---


### `article`

Newspaper articles, blog articles, publications, etc.

`yyyy-mm-dd_article_creator_description.pdf`

**Example:**

`2024-11-06_article_absurdistan-times.com_us-election-results-2024.pdf`


---


### `clippings`

Clippings documents created from, e.g. ebooks, articles, etc.

`yyyy-mm-dd_clippings_description.txt`

**Example:**

`2024-06-27_clippings_barry-schwartz-the-paradox-of-choice-2005.txt`


---


### `diary`

Daily notes, diary documents.

`yyyy-mm-dd_creator_diary.txt`

**Example:**

`2024-04-02_john-doe_diary.txt`


---


### `document`

For documents that do not match any other specific TYPE.

`yyyy-mm-dd_document_creator_recipient_description(-identifier).pdf`

**Example:**

`2024-05-16_document_event-inc_john-doe_midwest-princess-pageant-ticket-1995390976.pdf`


---


### `offer`

For written offers received and made.

`yyyy-mm-dd_offer_creator_recipient_description(-offer-identifier).pdf`

**Example:**

`2023-09-01_offer_john-doe_vibetide-inc_website-redesign-1290.pdf`


---


### `coo`

For order confirmations.

`yyyy-mm-dd_coo_creator_recipient_(description)(-order-identifier).pdf`

**Example:**

`2023-12-27_coo_shiver-daddy-inc_john-doe_refrigerator-coolio-1-53228398.pdf`


---


### `manual` 

Instruction manuals, assembly instructions, etc.

`yyyy-mm-dd_manual_creator_product-name.pdf`

**Example:**

`2024-01-14_manual_shiver-daddy-inc_refrigerator-coolio-1.pdf`


## Character conversion

| Char | Conversion |
| ---  | --- |
| ä | ae |
| ö | oe |
| ü | ue |
| ß | ss |
| ä | ae |
| æ | ae |
| œ | oe |
| ø | oe |
| å | aa |
| ð | eth |
| š | s |
| ž | z |
| õ | oe |
| ë | e |
| α | alpha |
| $ | dollar |
| € | euro |


## Illegal characters

* `#` pound
* `%` percent
* `&` ampersand
* `{` left curly bracket
* `}` right curly bracket
* `\` back slash
* `<` left angle bracket
* `>` right angle bracket
* `*` asterisk
* `?` question mark
* `/` forward slash
* ` ` blank spaces
* `$` dollar sign
* `!` exclamation point
* `'` single quotes
* `"` double quotes
* `:` colon
* `@` at sign
* `+` plus sign
* `\`` backtick
* `|` pipe
* `=` equal sign
* emojis
