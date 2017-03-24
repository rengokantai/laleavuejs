# laleavuejs
## 2. Features
### Using lifecycle hooks
beforeCreate 
- Before instance initialization  
Created
- reactive properties configured, instance not yet mounted
beforeMount
- Template compiled; ready to be inserted in DOM
Mounted
- Template inserted in DOM, replacing "el" element
beforeUpdate
- Data changed; update pending
Updated
- Re-rendered to reflect changes
beforeDestroy
- vm.$destroy() called

## 4. Advanced Vue Aplications
### Installing vue-cli and webpack
```
npm install -g vue-cli
```
```
vue init webpack-simple appname
```
