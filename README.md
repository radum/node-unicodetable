# unicode lookup table

loads http://unicode.org/Public/UNIDATA/UnicodeData.txt into [nodejs](http://nodejs.org).

## install

    npm install unicode


## example

    master//node-unicodetable » node
    > require('unicode/category/So')["♥".charCodeAt(0)]
    { value: '2665',
      name: 'BLACK HEART SUIT',
      category: 'So',
      class: '0',
      bidirectional_category: 'ON',
      mapping: '',
      decimal_digit_value: '',
      digit_value: '',
      numeric_value: '',
      mirrored: 'N',
      unicode_name: '',
      comment: '',
      uppercase_mapping: '',
      lowercase_mapping: '',
      titlecase_mapping: '' }
