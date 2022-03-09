# config

常用配置

## 规范

- 提交规范
  
  - [GitHub - streamich/git-cz: Semantic Git commits](https://github.com/streamich/git-cz#install-globally-standalone)

## vscode插件

- 编写shell
  
  - shellcheck  
    检查语法，提示错误信息
  
  - shell-format  
    shell格式化
  
  - shellman  
    shell自动补全命令
    
    参考文章：https://zhuanlan.zhihu.com/p/199187317

## vim插件

- Plug 'dense-analysis/ale'
  - https://github.com/dense-analysis/ale#installation-with-vim-plug
  - 检查shell的语法，提示语法错误信息
- Plug 'scrooloose/nerdtree'
  - https://github.com/preservim/nerdtree
  - 文件目录树

## postman

- 将swagger或者redoc生成的json文件导入到postman进行调试
  
  - https://learning.postman.com/docs/integrations/available-integrations/working-with-openAPI/

## mac

- sed
  
  - mac上的sed和linux上不同，使用gsed与linux对齐  
    
    ```bash
    brew install gnu-sed
    # gsed命令代替mac的sed
    ```
