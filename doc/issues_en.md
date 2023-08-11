// E0xx

### [E001] Cannot parse packet.json: <error message>
#### Explanation
Some problem parsing the package.json occured. See error messages added for details.
#### Required step to resolve the problem
Correct the file package.json so that it becomes a valid json file.
#### Technical notes

### [E002] No "ioBroker." found in the name of repository
#### Explanation
The name of the repository must be ioBroker.<adaptername>. ioBroker must be written with an capital B.
#### Required step to resolve the problem
Correct the name of the repository by renaming it to meet standards.
#### Technical notes

### [E003] Repository must have name ioBroker.adaptername, but now io"b"roker is in lowercase
#### Explanation
The name of the repository must be ioBroker.<adaptername>. ioBroker must be written with an capital B.
#### Required step to resolve the problem
Correct the name of the repository by renaming it to meet standards.
#### Technical notes

### [E004] No adapter name found in URL: <url>
#### Explanation
No adapter name could be retrieved from the url passed to the repository checker.
#### Required step to resolve the problem
Please check the url passed. It must refer to the github repository ofthe adapter and normally looks like
https://www.github.com/<owner>/ioBroker.<adaptername>
#### Technical notes

####### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E005] Adapter name must be lowercase
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E006] Invalid characters found in adapter name "${adapterName}". Only lowercase chars, digits, "-" and "_" are allowed`);
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E024] Adapter name "${adapterName}" may not start with '_'`);
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E007] Cannot find author repo in the URL
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E020] Name of adapter in package.json must be lowercase and be equal to "iobroker.${adapterName.toLowerCase()}". Now is "${packageJson.name}"`);
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E009] No version found in the package.json
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E010] No description found in the package.json
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E021] "licenses" in package.json are deprecated. Please use only "license": "NAME" field.
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E013] No author found in the package.json
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E014] NPM information found in package.json. Please remove all attributes starting with "_"
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E015] No license found in package.json
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E016] No SPDX license found in package.json. Please use one of listed here: https://spdx.org/licenses/
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E017] No repository found in the package.json
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E018] Invalid repository type in package.json: ' + context.packageJson.repository.type + '. It should be git
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E019] Invalid repository URL in package.json: ${context.packageJson.repository.url}. Expected: ${context.githubApiData.ssh_url} or ${context.githubApiData.clone_url}`);
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E019] Invalid repository URL in package.json: ${context.packageJson.repository}. Expected: ${context.githubApiData.ssh_url} or ${context.githubApiData.clone_url}`);
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E019] Invalid repository URL in package.json
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E022] Adapter name is reserved!
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E023] Do not include "npm" as dependency!
// max number is E024

// E1xx
console.log('checkIOPackageJson #### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E1xx]
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E100] Cannot parse io-package.json: ' + e);
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E101] io-package.json must have at least empty "native" attribute
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E102] io-package.json must have common object
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E103] "common.name" in io-package.json must be equal to "${context.adapterName.toLowerCase()}'". Now is ${context.ioPackageJson.common.name}`);
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [W171] "common.title" is deprecated in io-package.json
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E104] No "common." found in io-package.json
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E105] "common." must be an object. Now: ' + JSON.stringify(context.ioPackageJson.common.));
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [W105] "common." should be translated into all supported languages (${allowedLanguages.join(', ')})`);
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [W105] "common." should not have ioBroker in the name. It is clear, for what this adapter was created. Now: ' + JSON.stringify(context.ioPackageJson.common.));
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E106] "common." should not contain word "adapter" in the name. It is clear, that this is adapter. Now: ' + JSON.stringify(context.ioPackageJson.common.));
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E107] No "common.version" found in io-package.json
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E118] Versions in package.json and in io-package.json are different
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E108] No "common.desc" found in io-package.json
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E109] "common.desc" in io-package.json should be an object for many languages. Found only ' + context.ioPackageJson.common.desc);
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [W109] "common.desc" should be translated into all supported languages (${allowedLanguages.join(', ')})`);
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E169] "common.keywords" must be an array in the io-package.json
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [W170] "common.keywords" should not contain "${forbiddenKeywords.join(', ')}" io-package.json`);
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E110] Icon not found in the io-package.json
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E111] extIcon not found in the io-package.json
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E112] extIcon must be the same as an icon but with github path
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [W113] Adapter should support compact mode
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E114] No adapter are allowed in the repo without admin support (set "common.noConfig = true" and "common.adminUI.config = none" if adapter has no configuration)
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [W156] Adapter should support admin 5 UI (jsonConfig) if you do not use a React based UI
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [W164] Adapters without config "common.noConfig = true" should also set "common.adminUI.config = none"
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E115] No license found in io-package.json
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E116] No SPDX license found. Please use one of listed here: https://spdx.org/licenses/
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E117] Licenses in package.json and in io-package.json are different
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E165] Node mode found in package.json
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E166] Unknown type found in io-package.json
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E162] onlyWWW should have common.mode "none" in io-package.json
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E167] schedule adapters must have common.schedule property in io-package.json
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E119] No type found in io-package.json
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E120] Unknown type found in io-package.json
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E121] No authors found in io-package.json
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E122] authors must be an Array in io-package.json
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E123] Authors may not be empty in io-package.json
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [W172] "common.localLink" in io-package.json is deprecated. Please define object "common.localLinks": { "_default": "..." }
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E130] No "common.news" found in io-package.json
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E130] Too many "common.news" found in io-package.json. Must be less than 20. Please remove old news.
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E145] No "common.news" found for actual version ${context.ioPackageJson.common.version}`);
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [W145] Each "common.news" should be translated into all supported languages (${allowedLanguages.join(', ')})`);
!context.ioPackageJson.common.onlyWWW && #### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E143] No main found in the package.json
!context.ioPackageJson.common.onlyWWW && #### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E163] common.mode "${context.ioPackageJson.common.mode}" requires JavaScript file for "main" in package.json`);
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E144] common.installedFrom field found in io-package.json. Must be removed.
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E146] instanceObjects must be an Array in io-package.json
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E147] instanceObject type has an invalid type: ' + instanceObject.type);
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E148] instanceObject common.type has an invalid type! Expected "string", received  "${typeof instanceObject.common.type}"`);
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E149] instanceObject common.type has an invalid value: ' + instanceObject.common.type);
!context.ioPackageJson.common.onlyWWW && #### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E150] No common.connectionType found in io-package.json
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E151] common.connectionType type has an invalid value "${context.ioPackageJson.common.connectionType}"`);
!context.ioPackageJson.common.onlyWWW && #### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E152] No common.dataSource found in io-package.json
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E152] common.dataSource type has an invalid value "${context.ioPackageJson.common.dataSource}"`);
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E160] "admin" is not allowed in common.dependencies`);
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E159] common.dependencies "js-controller" dependency should always allow future versions (>=x.x.x) - recommended: {"js-controller": ">=${recommendedJsControllerVersion}"}`);
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E161] "js-controller" is not allowed in common.globalDependencies`);
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E153] common.dependencies must contain {"js-controller": ">=1.5.8"} or later - recommended: {"js-controller": ">=${recommendedJsControllerVersion}"}`);
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E153] common.dependencies must contain {"js-controller": ">=1.5.8"} or later - recommended: {"js-controller": ">=${recommendedJsControllerVersion}"}`);
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E153] common.dependencies must contain {"js-controller": ">=1.5.8"} or later - recommended: {"js-controller": ">=${recommendedJsControllerVersion}"}`);
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E154] common.dependencies must contain #### Explanation
#### Required step to resolve the problem
#### Technical notes

### [{"js-controller": ">=2.0.0"}] or later - recommended: #### Explanation
#### Required step to resolve the problem
#### Technical notes

### [{"js-controller": ">=${recommendedJsControllerVersion}"}]`);
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E154] common.dependencies must contain #### Explanation
#### Required step to resolve the problem
#### Technical notes

### [{"js-controller": ">=2.0.0"}] or later - recommended: #### Explanation
#### Required step to resolve the problem
#### Technical notes

### [{"js-controller": ">=${recommendedJsControllerVersion}"}]`);
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E154] common.dependencies must contain {"js-controller": ">=2.0.0"} or later - recommended: {"js-controller": ">=${recommendedJsControllerVersion}"}`);
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E157] common.protectedNative requires dependency {"js-controller": ">=2.0.2"} or later - recommended: {"js-controller": ">=${recommendedJsControllerVersion}"}`);
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E157] common.protectedNative requires dependency {"js-controller": ">=2.0.2"} or later - recommended: {"js-controller": ">=${recommendedJsControllerVersion}"}`);
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E158] common.encryptedNative requires dependency {"js-controller": ">=3.0.3"} or later - recommended: {"js-controller": ">=${recommendedJsControllerVersion}"}`);
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E158] common.encryptedNative requires dependency {"js-controller": ">=3.0.3"} or later - recommended: {"js-controller": ">=${recommendedJsControllerVersion}"}`);
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E168] common.notifications requires dependency {"js-controller": ">=3.2.0"} or later - recommended: {"js-controller": ">=${recommendedJsControllerVersion}"}`);
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E168] common.notifications requires dependency {"js-controller": ">=3.2.0"} or later - recommended: {"js-controller": ">=${recommendedJsControllerVersion}"}`);
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E155] Invalid tier value: ${context.ioPackageJson.common.tier}. Only 1, 2 or 3 are allowed!`);
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E140] width and height of logo are not equal
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E141] logo is too small. It must be greater or equal than 32x32
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E142] logo is too big. It must be less or equal than 512x512
.catch(() => #### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E124] Main file not found under URL: ${context.githubUrl}/${context.packageJson.main}`))
.catch(() => #### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E125] External icon not found under URL: ${context.ioPackageJson.common.extIcon}`))
// max number is E172
// E2xx
console.log('checkNpm #### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E2xx]
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E200] Not found on npm. Please publish
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E201] Bluefox was not found in the collaborators on NPM!. Please execute in adapter directory: "npm owner add bluefox iobroker.${context.adapterName}"`);
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E200] Not found on npm. Please publish
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E201] Bluefox was not found in the collaborators on NPM!. Please execute in adapter directory: "npm owner add bluefox iobroker.${context.adapterName}"`);
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [W202] Version of package.json (${context.packageJson.version}) doesn't match latest version on NPM (${
// max number is E202
// E3xx
console.log('checkTests #### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E3xx]
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E300] Not found on travis. Please setup travis or use github actions (preferred)
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E300] Not found on travis. Please setup travis or use github actions (preferred)
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E300] Not found on travis. Please setup travis or use github actions (preferred)
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E300] Not found on travis. Please setup travis or use github actions (preferred)
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [W302] Use github actions instead of travis-ci
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E301] Tests on Travis-ci.org are broken. Please fix.
// max number is E302
// E4xx
console.log('checkRepo #### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E4xx]
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E400] Cannot download https://raw.githubusercontent.com/ioBroker/ioBroker.repositories/master/sources-dist.json
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [W400] Cannot find "' + context.adapterName + '" in latest repository
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E402] Types of adapter in latest repository and in io-package.json are different "' + context.latestRepo#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [context.adapterName].type + '" !== "' + context.ioPackageJson.common.type + '"
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E403] Version set in latest repository
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E404] Icon not found in latest repository
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E405] Icon must be in the following path: ' + url);
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E406] Meta URL (latest) not found in latest repository
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E407] Meta URL (latest) must be equal to ${url}io-package.json`);
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E420] Cannot download https://raw.githubusercontent.com/ioBroker/ioBroker.repositories/master/sources-dist-stable.json
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E422] Types of adapter in stable repository and in io-package.json are different "' + context.stableRepo#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [context.adapterName].type + '" !== "' + context.ioPackageJson.common.type + '"
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E423] Adapter was found in stable repository but not in latest repo
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E424] No version set in stable repository
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E425] Icon not found in stable repository
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E426] Icon (stable) must be in the following path: ' + url);
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E427] Meta URL (stable) not found in latest repository
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E428] Meta URL (stable) must be equal to ${url}io-package.json`);
// max number is E428
// E5xx
console.log('checkCode #### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E5xx]
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E500] node_modules found in repo. Please delete it
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E501] Cannot get ${context.branch}.zip on github`);
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E502] "admin/img/info-big.png" not found, but selectID.js used in index_m.html 
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E506] More non translated in german or russian words found in admin/words.js. You can use https://translator.iobroker.in/ for translations`);
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E506] Word "${word}" is not translated to german in admin/words.js. You can use https://translator.iobroker.in/ for translations`);
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E506] Word "${word}" is not translated to russian in admin/words.js. You can use https://translator.iobroker.in/ for translations`);
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E507] Cannot parse "admin/jsonConfig.json${context#### Explanation
#### Required step to resolve the problem
#### Technical notes

### ['/admin/jsonConfig.json'] ? '' : '5'}": ${e}`);
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E508] "admin/jsonConfig.json${context#### Explanation
#### Required step to resolve the problem
#### Technical notes

### ['/admin/jsonConfig.json'] ? '' : '5'}" not found, but admin support is declared`);
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E509] Cannot parse "admin/i18n/${lang}/translations.json": ${e}`);
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E509] Cannot parse "admin/i18n/${lang}.json": ${e}`);
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E510] "/admin/i18n/${lang}/translations.json" or "admin/i18n/${lang}.json" not found, but admin support is declared`);
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [W515] Why you decided to disable i18n support?`);
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E511] Cannot parse "admin/jsonCustom.json${context#### Explanation
#### Required step to resolve the problem
#### Technical notes

### ['/admin/jsonCustom.json'] ? '' : '5'}": ${e}`);
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E512] "admin/jsonCustom.json${context#### Explanation
#### Required step to resolve the problem
#### Technical notes

### ['/admin/jsonCustom.json'] ? '' : '5'}" not found, but custom support is declared`);
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E514] "admin/blockly.js" not found, but blockly support is declared
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E515] JavaScript-Rules support is declared, but no location in property url defined
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E516] "' + context.ioPackageJson.common.javascriptRules.url + '" not found, but JavaScript-Rules support is declared
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E503] "iob_npm.done" found in repo! Remove that file
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [W513] "gulpfile.js" found in repo! Think about migrating to @iobroker/adapter-dev package
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E518] "@alcalzone/release-script" is used, but ".releaseconfig.json" not found
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E504] "${context.packageJson.main}" found in package.json, but not found as file`);
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E504] setInterval found in "${context.packageJson.main}", but no clearInterval detected`);
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [W504] setInterval found in "${context.packageJson.main}", but no clearInterval detected`);
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E505] setTimeout found in "${context.packageJson.main}", but no clearTimeout detected`);
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [W505] setTimeout found in "${context.packageJson.main}", but no clearTimeout detected`);
// max E518
// E8xx
console.log('checkGithubRepo #### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E8xx]
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E801] No repository about text found. Please go to "${context.githubUrlOriginal}", press the settings button beside the about title and add the description.`);
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E802] No topics found in the repository. Please go to "${context.githubUrlOriginal}", press the settings button beside the about title and add some topics.`);
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E803] Archived repositories are not allowed.`);
// max E803
// E6xx
console.log('checkReadme #### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E6xx]
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E601] No README.md found
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E603] NO "## Changelog" found in README.md
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E606] Current adapter version ${context.packageJson.version} not found in README.md`);
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E604] No "## License" found in README.md
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E605] No actual year found in copyright. Please add "Copyright (c) ${m#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [1]}-${year} ${getAuthor(context.packageJson.author)}" at the end of README.md`);
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E605] No actual year found in copyright. Please add "Copyright (c) ${year} ${getAuthor(context.packageJson.author)}" at the end of README.md`);
// max E606
// E7xx
console.log('checkLicenseFile #### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E7xx]
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E701] NO LICENSE file found
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E701] No actual year found in LICENSE. Please add "Copyright (c) ${m#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [1]}-${year} ${getAuthor(context.packageJson.author)}" at the start of LICENSE`);
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E701] No actual year found in LICENSE. Please add "Copyright (c) ${year} ${getAuthor(context.packageJson.author)}" at the start of LICENSE`);
// E8xx
console.log('checkNpmIgnore #### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E8xx]
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [W801] .npmignore not found`);
!check && #### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E804] node_modules not found in .npmignore`);
!check && #### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E803] iob_npm.done not found in .npmignore`);
!check && #### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E8${paddingNum(i + 11)}] file ${file} found in repository, but not found in .npmignore`);
// E9xx
console.log('checkGitIgnore #### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E9xx]
#### Explanation
#### Required step to resolve the problem
#### Technical notes

### [W901] .gitignore not found`);
!check && #### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E902] node_modules not found in .npmignore`);
!check && #### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E903] iob_npm.done not found in .gitignore`);
!check && #### Explanation
#### Required step to resolve the problem
#### Technical notes

### [E9${paddingNum(i + 11)}] file ${file} found in repository, but not found in .gitignore`);
