Umineko Scripting
=================

Install PHP somewhere on your PATH. No extra modules are required, just the default configuration is fine.
cd to the project root.
mkdir out; php update-manager/update-manager.php dscript out/wh.txt . wh
Check out/wh.txt for anything suspicious. You probably won't find anything because the script is too complicated for human consumption.
php update-manager/update-manager.php script out/wh.txt "out/Witch-Hunt.file" 8
Copy the generated .file file to the Umineko Project directory and choose "Witch-Hunt" as your language in the game settings.

PHP 깔고 path 추가한다음

프로젝트에서
mkdir out; php update-manager/update-manager.php dscript out/en.txt . en

이렇게 쳐서 txt로 뽑아서 한번검사한다음 이상없으면

php update-manager/update-manager.php script out/en.txt "out/en.file" 8

하면 en.file 나옴

#### Credits
- Umineko Project
- Knox Translations
- SNS Team
- All third-party contributors and authors
