# BlackFlag Theme
- Todos os componentes começam com letra maiúscula
- As classes CSS dos componentes também são todos em letras maiúsculas.

"react": "^16.0.0",
"node-sass": "npm:sass"
 yarn add node-sass@npm:sass --save-dev

## Importando os componentes
No arquivo da sua página ReactJs
```js
import { Button, Field } from 'blackflag'
```
Usando um componente importado
```html
<Button href="#">Button</Button>
```
> Saída HTML
> ```html
> <a class="Button" href="#">Button</a>
> ```

## Importando o SASS
```js
import 'blackflag/scss'
```

## Lista de componentes

### Controls
- [Button](/src/controls/Button/README.md)  
- [Field](/src/controls/Field/README.md)

### Layout
- [Container](/src/layout/Container/README.md)  
- [Divider](/src/layout/Divider/README.md)  
- [Ellipsis](/src/layout/Ellipsis/README.md)  
- [Grid](/src/layout/Grid/README.md)  
- [Page](/src/layout/Page/README.md)  
- [Table](/src/layout/Table/README.md)  
- [Wrapper](/src/layout/Wrapper/README.md)  

### Media
- [Icon](/src/layout/Icon/README.md)
- [Image](/src/layout/Image/README.md)
- [Video](/src/layout/Video/README.md)

### Modules
- [Card](/src/layout/Card/README.md)
- [Modal](/src/layout/Modal/README.md)
- [Progress](/src/layout/Progress/README.md)
- [Spinner](/src/layout/Spinner/README.md)
- [Tabs](/src/layout/Tabs/README.md)
