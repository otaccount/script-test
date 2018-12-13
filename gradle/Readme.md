|1|2|
|-|-|
|tasks.[task名].execute()|別のtaskを呼び出し|
|dependsOn [task名],[task名]|別のtaskを先に実行|

apply plugin: 'application'
mainClassName = '[mainクラス]'
gradle run で実行

