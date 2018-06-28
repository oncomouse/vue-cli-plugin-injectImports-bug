# vue-cli-plugin-injectImports-bug

This plugin shows that GeneratorAPI.injectImports doesn't work on .vue files. 

## Steps to Reproduce

1. `git clone https://github.com/oncomouse/vue-cli-plugin-injectImports-bug`
2. `vue create -d vue-project`
3. `cd vue-project`
4. `npm i ../vue-cli-plugin-injectImports-bug`
5. `vue invoke @oncomouse/vue-cli-plugin-injectImports-bug`
