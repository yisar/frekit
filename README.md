# frekit
Streaming rendering for fre SSR

```js
<Suspense fallback={<div>Loading...</div>}>
  <div>Actual Content</div>
</Suspense>
```

```html
<template name="$1">
  <!--$?-->
    <div>Loading...</div>
  <!--/$-->
</template>

<template name="$2">
  <div>Actual Content</div>
<template>
  
<script>
  replace($1, $2);
</script>
```
