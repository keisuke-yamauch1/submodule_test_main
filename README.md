# submodule_test_main

submodule更新

- cd submodule_test_sub
- git submodule update --remote
- git pull

ローカルでの開発

- サブモジュール側でブランチ作成&プッシュ
- こちらでcd submodule_test_sub
- git checkout {作成したブランチ}
- そのまま、サブモジュールディレクトリで作業
- コミット、プッシュするとサブモジュール側にコミットされる