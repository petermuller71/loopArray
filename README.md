[![Build Status](https://travis-ci.org/{ORG-or-USERNAME}/{REPO-NAME}.png?branch=master)](https://travis-ci.org/{ORG-or-USERNAME}/{REPO-NAME})

PHP Loop through (infinite) multidemensional array or json
Instruction:
$result = loopArray::forEach($php_multi_array);
$print $result;

if data is json format, first do:
$php_multi_array = json_decode($data, true);
