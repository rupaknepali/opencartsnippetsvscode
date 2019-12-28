# Opencart Snippets for VScode by [webocreation.com](https://webocreation.com)

This VSCode extension is for OpenCart developer which has a collection of OpenCart snippets. This is just start, Please let us know if need to add more [Contact Us](https://webocreation.com/contact)

## Documentation

All snippets starts with oc. Some of the snippets are:

PHP page supported snippets:

- occ : It creates new Controller class
- ocm : It creates new Method or function
- occm : It creates new starter Model class
- ocl : It creates new variables for language files
- ocprf : It creates print_r with pre
- occacheget: It creates to get the cache
- occacheset: It creates to set the cache
- occachedelete: It creates to delete the cache
- occonfigget: It creates to get the config
- occonfigset: It creates to set the config
- ocdbquery: It creates to query the database
- ocdbescape: It creates to escape the database fields
- ocdbcount: It creates to count the rows affected of the database
- ocdocumentsettitle: $this->document->setTitle(title)
- ocdocumentgettitle: $this->document->getTitle()
- ocdocumentsetdescription: $this->document->setDescription()
- ocdocumentgetdescription: $this->document->getDescription()
- ocdocumentsetkeywords: $this->document->setKeywords()
- ocdocumentgetkeywords: $this->document->getKeywords()
- ocdocumentaddlinks: $this->document->addLinks()
- ocdocumentgetlinks: $this->document->getLinks()
- ocdocumentaddstyles: $this->document->addStyles(....)
- ocdocumentgetstyles: $this->document->getStyles()
- ocdocumentaddscripts: $this->document->addScripts(..)
- ocdocumentgetscripts: $this->document->getScripts(postion)
- ocencryptionencrypt: $this->encryption->encrypt(...)
- ocencryptiondecrypt: $this->encryption->decrypt(...)
- oclanguageset: $this->language->set(...)
- oclanguageget: $this->language->get(key)
- oclanguageall: $this->language->all()
- oclanguageload: $this->language->load(filename)
- oclog: $this->log->write(message)
- ocmail: It creates the new Mail, it parameter, SMTP configuration needed, set to, set from, set subject, set the html type and send code.
- ocpagination: It creates the code for basic pagination needed.
- ocrequestget: $this->request->get[...]
- ocrequestpost: $this->request->post[...]
- ocrequestcookie: $this->request->cookie[cookiename]
- ocrequestfiles: $this->request->files[filename]
- ocrequestserver: $this->request->server[REQUEST_METHOD]
- ocresponseredirect: Response redirect code
- ocresponsesetoutput: Response set output
- ocresponsejson: Response JSON code
- ocsession: Session Data
- ocurllink: URL link
- occart: Cart $this->cart->
- occurrency: Currency format 
- occheckuserpermission: Check user permission

Twig page supported snippets:

- oct : It creates starting template layouts in twig files
- octfor : It creates for loop in twig files
- octif : It creates if statement in twig files
- ocbtn : It creates button markup
- ocimg : It creates image markup
- ocbc : It creates breadcrumbs loop in twig files

OCMOD XML page supported snippets:

- ocmod : It creates OCMOD xml code boilerplate
- ocmodf : It creates OCMOD xml code boilerplate for files only

## Release Notes

Users appreciate release notes as you update your extension.

### [1.5.1]

- Added global methods and updated the Readme
- See all variables in twig [How to see all variables available in twig template in Opencart](https://webocreation.com/blog/how-to-see-all-variables/)

### [1.3.0]

- Added global methods
- Read all [OpenCart 3 Library Global objects Methods](https://webocreation.com/blog/opencart-library-global-methods/)

### [1.2.1]

- Auto folder and file name in controller and model class

### [1.2.0]

- OCMOD support added.
- ocmod - for install.xml boilerplate creation
- ocmodf - OCMOD XML file boilerplate
- ocprf - print_r with pre

### 1.0.0

- Initial release of Opencart Snippets for VScode
- Added some snippets. Others are comming soon.

### For more information

- [Documentation and plans](https://webocreation.com/blog/opencart-code-snippets-vscode-extensions)
- [Support and any kind of OpenCart requests](https://webocreation.com/contact)

**Enjoy!**
