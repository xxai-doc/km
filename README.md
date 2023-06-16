<p align="center"><a href="https://xxai.art"><img src="https://cdn.jsdelivr.net/gh/xxai-art/doc/logo.svg"/></a><br/><a href="https://xxai.art"><img src="https://cdn.jsdelivr.net/gh/xxai-art/doc/xxai.svg"/></a></p><p align="center"><a href="https://github.com/xxai-art/doc#readme"><img alt="I18N" src="https://cdn.jsdelivr.net/gh/wactax/img/t.svg"/></a>　<a href="https://groups.google.com/u/0/g/xxai-art"><img alt="Google Groups" src="https://cdn.jsdelivr.net/gh/wactax/img/g-groups.svg"/></a></p>

វាត្រូវបានផ្ដល់អនុសាសន៍ឱ្យដំឡើង nodejs, [direnv](https://direnv.net) , [bun](https://github.com/oven-sh/bun) ជាមុនសិន ហើយបន្ទាប់មក `direnv allow` បន្ទាប់ពីបញ្ចូលថត ( [.envrc](https://github.com/xxai-art/doc/blob/main/.envrc) នឹងត្រូវបានប្រតិបត្តិដោយស្វ័យប្រវត្តិបន្ទាប់ពីបញ្ចូលថត)។

អត្ថន័យគឺ៖ ការបកប្រែចិនទៅជប៉ុន កូរ៉េ អង់គ្លេស អង់គ្លេស បកប្រែទៅគ្រប់ភាសាផ្សេងទៀត។ ប្រសិនបើអ្នកចង់គាំទ្រតែភាសាចិន និងភាសាអង់គ្លេស អ្នកគ្រាន់តែអាចសរសេរ `zh: en` .

អត្ថន័យគឺ៖ បកប្រែចិនទៅជប៉ុន កូរ៉េ អង់គ្លេស អង់គ្លេស បកប្រែទៅគ្រប់ភាសាផ្សេងទៀត។ ប្រសិនបើអ្នកចង់គាំទ្រតែភាសាចិន និងភាសាអង់គ្លេស អ្នកគ្រាន់តែអាចសរសេរ `zh: en` .

* [លេខកូដខាងមុខ](https://github.com/xxai-art/web)
* [កញ្ចប់ភាសាសម្រាប់គេហទំព័រទាំងមូល](https://github.com/xxai-art/web/tree/main/i18n)
* [កញ្ចប់ភាសាសម្រាប់ម៉ូឌុលចូល](https://github.com/wacpkg/user/tree/main/ui.i18n)
* [គេហទំព័រ ឯកសារពហុភាសា](https://github.com/xxai-doc)

ភាសាសរសេរកម្មវិធីផ្នែកខាងមុខគឺ [@w5/coffee_plus](http://npmjs.com/@w5/coffee_plus) ដែលបន្ថែមលក្ខណៈពិសេសមួយចំនួនដោយផ្អែកលើវាក្យសម្ព័ន្ធ coffeescript សូមមើល [./coffee_plus.md](./coffee_plus.md) ។

## អន្តរជាតិនៃគេហទំព័រ និងឯកសារ

បង្កើតគម្រោង 3 ខាងក្រោម

* [@w5/mdt](https://www.npmjs.com/package/@w5/mdt)

  បច្ច័យគឺ `.mdt` អ្នកអាចប្រើវាក្យសម្ព័ន្ធស្រដៀងនឹង `<+ ./coffee_plus/import.js>` ដើម្បីយោងទៅឯកសារខាងក្រៅ ហើយបង្កើតសញ្ញាសម្គាល់ដោយបច្ច័យ `.md` ។

* [@w5/trmd](https://www.npmjs.com/package/@w5/trmd)

  ការបកប្រែ Markdown នឹងមិនបកប្រែលេខកូដ និងតំណភ្ជាប់ទេ ហើយនឹងទុកឃ្លាដែលបានបកប្រែក្នុងឃ្លាំងសម្ងាត់។ ប្រសិនបើការបកប្រែត្រូវបានកែប្រែ ប៉ុន្តែអត្ថបទដើមមិនត្រូវបានកែប្រែទេ ការប្រតិបត្តិវាម្តងទៀតនឹងមិនសរសេរជាន់លើការកែប្រែនៃការបកប្រែនោះទេ។

* [@w5/i18n](https://www.npmjs.com/package/@w5/i18n)

  ឯកសារភាសាសម្រាប់ការបកប្រែគេហទំព័រដែលបានបង្កើត `yaml` ។

### សេចក្តីណែនាំអំពីស្វ័យប្រវត្តិកម្មនៃការបកប្រែឯកសារ

សូមមើលឃ្លាំងកូដ [xxai-art/doc](https://github.com/xxai-art/doc)

វាត្រូវបានផ្ដល់អនុសាសន៍ឱ្យដំឡើង nodejs, [direnv](https://direnv.net) , [bun](https://github.com/oven-sh/bun) ជាមុនសិន ហើយបន្ទាប់មក `direnv allow` បន្ទាប់ពីបញ្ចូលថត ( [.envrc](https://github.com/xxai-art/doc/blob/main/.envrc) នឹងត្រូវបានប្រតិបត្តិដោយស្វ័យប្រវត្តិបន្ទាប់ពីបញ្ចូលថត)។

ដើម្បីជៀសវាងមូលដ្ឋានកូដដ៏ធំដែលត្រូវបានបកប្រែជារាប់រយភាសា ខ្ញុំបានបង្កើតមូលដ្ឋានកូដដាច់ដោយឡែកសម្រាប់ភាសានីមួយៗ ហើយបានបង្កើតស្ថាប័នមួយដើម្បីរក្សាទុកមូលដ្ឋានកូដ។

ការកំណត់អថេរបរិស្ថាន `GITHUB_ACCESS_TOKEN` ហើយបន្ទាប់មកដំណើរការ [create.github.coffee](https://github.com/xxai-art/doc/blob/main/create.github.coffee) នឹងបង្កើតឃ្លាំងកូដដោយស្វ័យប្រវត្តិ។

ជាការពិតណាស់ អ្នកក៏អាចដាក់វានៅក្នុងមូលដ្ឋានកូដផងដែរ។

សេចក្តីយោងស្គ្រីបបកប្រែ [run.sh](https://github.com/xxai-art/doc/blob/main/run.sh)

កូដស្គ្រីបត្រូវបានបកស្រាយដូចខាងក្រោមៈ

[bunx](https://bun.sh/docs/cli/bunx) គឺជាការជំនួសសម្រាប់ npx ដែលលឿនជាង។ ជាការពិតណាស់ ប្រសិនបើអ្នកមិនបានដំឡើងប៊ុនទេ អ្នកអាចប្រើ `npx` ជំនួសវិញ។

`bunx mdt zh` renders `.mdt` ក្នុង zh directory ជា `.md` សូមមើលឯកសារភ្ជាប់ 2 ខាងក្រោម

* [coffee_plus.mdt](https://github.com/xxai-doc/zh/blob/main/coffee_plus.mdt)
* [coffee_plus.md](https://github.com/xxai-doc/zh/blob/main/coffee_plus.md)

`bunx i18n` គឺជាកូដស្នូលសម្រាប់ការបកប្រែ (ប្រសិនបើអ្នកបានដំឡើងតែ `nodejs` ប៉ុន្តែ `bun` និង `direnv` មិនត្រូវបានដំឡើងទេ អ្នកក៏អាចដំណើរការ `npx i18n` ដើម្បីបកប្រែបានដែរ)។

វានឹងញែក [i18n.yml](https://github.com/xxai-art/doc/blob/main/i18n.yml) ការកំណត់រចនាសម្ព័ន្ធនៃ `i18n.yml` ក្នុងឯកសារនេះមានដូចខាងក្រោម៖

```
en:
zh: ja ko en
```

អត្ថន័យគឺ៖ ការបកប្រែចិនទៅជប៉ុន កូរ៉េ អង់គ្លេស អង់គ្លេស បកប្រែទៅគ្រប់ភាសាផ្សេងទៀត។ ប្រសិនបើអ្នកចង់គាំទ្រតែភាសាចិន និងភាសាអង់គ្លេស អ្នកគ្រាន់តែអាចសរសេរ `zh: en` .

ចុងក្រោយគឺ [gen.README.coffee](https://github.com/xxai-art/doc/blob/main/gen.README.coffee) ដែលស្រង់ខ្លឹមសាររវាងចំណងជើងចម្បង និងចំណងជើងរងដំបូងនៃភាសានីមួយៗ `README.md` ដើម្បីបង្កើតធាតុ `README.md` ។ កូដគឺសាមញ្ញណាស់ អ្នកអាចមើលវាដោយខ្លួនឯងបាន។

Google API ត្រូវបានប្រើសម្រាប់ការបកប្រែដោយឥតគិតថ្លៃ។ ប្រសិនបើអ្នកមិនអាចចូលប្រើ Google បានទេ សូមកំណត់រចនាសម្ព័ន្ធ និងកំណត់ប្រូកស៊ី ដូចជា៖

```
export https_proxy=http://127.0.0.1:7890 http_proxy=http://127.0.0.1:7890 all_proxy=socks5://127.0.0.1:7890
```

ស្គ្រីបបកប្រែនឹងបង្កើតឃ្លាំងសម្ងាត់ដែលបានបកប្រែនៅក្នុងថត `.i18n` សូមពិនិត្យមើលវាជាមួយនឹង `git status` ហើយបញ្ចូលវាទៅក្នុងឃ្លាំងកូដ ដើម្បីជៀសវាងការបកប្រែម្តងហើយម្តងទៀត។

សូមដំណើរការ `bunx i18n` រាល់ពេលដែលអ្នកកែប្រែការបកប្រែដើម្បីធ្វើបច្ចុប្បន្នភាពឃ្លាំងសម្ងាត់។

ប្រសិនបើអត្ថបទដើម និងការបកប្រែត្រូវបានកែប្រែក្នុងពេលតែមួយ ឃ្លាំងសម្ងាត់នឹងមានការភ័ន្តច្រឡំ ដូច្នេះប្រសិនបើអ្នកចង់កែប្រែ អ្នកអាចកែប្រែបានតែមួយប៉ុណ្ណោះ ហើយបន្ទាប់មកដំណើរការ `bunx i18n` ដើម្បីធ្វើបច្ចុប្បន្នភាពឃ្លាំងសម្ងាត់។
