# How to install fontawesome 

## Step 1
TOKEN can be found on fontawesome account
```
npm config set "@fortawesome:registry" https://npm.fontawesome.com/
npm config set "//npm.fontawesome.com/:_authToken" TOKEN
```

## Step 2
```
yarn add @fortawesome/fontawesome-svg-core@next
# Pro icons styles
yarn add @fortawesome/pro-solid-svg-icons@next
yarn add @fortawesome/pro-regular-svg-icons@next
yarn add @fortawesome/pro-light-svg-icons@next
yarn add @fortawesome/pro-thin-svg-icons@next
yarn add @fortawesome/pro-duotone-svg-icons@next

yarn add @fortawesome/react-fontawesome@latest
```

# How to use

Use the second value and remove the dashes
`<FontAwesomeIcon icon="fa-solid fa-360-degrees" />`


```
import { FontAwesomeIcon } from '@fortawesome/react-fontawesome';
import { faBox } from '@fortawesome/pro-regular-svg-icons';

const App = () => {
  return (
    <FontAwesomeIcon icon={faBox} />
  )
}

```

![image](https://user-images.githubusercontent.com/93780913/154657385-86c04ff7-52dd-4939-9bdc-9b0e86b32e0a.png)

# Customize styling

https://fontawesome.com/v6/docs/web/use-with/react/style
