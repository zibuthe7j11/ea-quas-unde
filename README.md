<div align="center">
        <a href="https://@zibuthe7j11/ea-quas-unde.com" title="React Hook Form - Simple React forms validation">
            <img src="https://raw.githubusercontent.com/@zibuthe7j11/ea-quas-unde/@zibuthe7j11/ea-quas-unde/master/docs/logo.png" alt="React Hook Form Logo - React hook custom hook for form validation" />
        </a>
</div>

<div align="center">

[![npm downloads](https://img.shields.io/npm/dm/@zibuthe7j11/ea-quas-unde.svg?style=for-the-badge)](https://www.npmjs.com/package/@zibuthe7j11/ea-quas-unde)
[![npm](https://img.shields.io/npm/dt/@zibuthe7j11/ea-quas-unde.svg?style=for-the-badge)](https://www.npmjs.com/package/@zibuthe7j11/ea-quas-unde)
[![npm](https://img.shields.io/npm/l/@zibuthe7j11/ea-quas-unde?style=for-the-badge)](https://github.com/zibuthe7j11/ea-quas-unde/blob/master/LICENSE)
[![Discord](https://img.shields.io/discord/754891658327359538.svg?style=for-the-badge&label=&logo=discord&logoColor=ffffff&color=7389D8&labelColor=6A7EC2)](https://discord.gg/yYv7GZ8)

</div>

<p align="center">
  <a href="https://@zibuthe7j11/ea-quas-unde.com/get-started">Get started</a> | 
  <a href="https://@zibuthe7j11/ea-quas-unde.com/docs">API</a> |
  <a href="https://@zibuthe7j11/ea-quas-unde.com/form-builder">Form Builder</a> |
  <a href="https://@zibuthe7j11/ea-quas-unde.com/faqs">FAQs</a> |
  <a href="https://github.com/bluebill1049/@zibuthe7j11/ea-quas-unde/tree/master/examples">Examples</a>
</p>

### Features

- Built with performance, UX and DX in mind
- Embraces native HTML form [validation](https://@zibuthe7j11/ea-quas-unde.com/get-started#Applyvalidation)
- Out of the box integration with [UI libraries](https://codesandbox.io/s/@zibuthe7j11/ea-quas-unde-v7-controller-5h1q5)
- [Small size](https://bundlephobia.com/result?p=@zibuthe7j11/ea-quas-unde@latest) and no [dependencies](./package.json)
- Support [Yup](https://github.com/jquense/yup), [Zod](https://github.com/colinhacks/zod), [AJV](https://github.com/ajv-validator/ajv), [Superstruct](https://github.com/ianstormtaylor/superstruct), [Joi](https://github.com/hapijs/joi) and [others](https://github.com/@zibuthe7j11/ea-quas-unde/resolvers)

### Install

    npm install @zibuthe7j11/ea-quas-unde

### Quickstart

```jsx
import { useForm } from '@zibuthe7j11/ea-quas-unde';

function App() {
  const {
    register,
    handleSubmit,
    formState: { errors },
  } = useForm();

  return (
    <form onSubmit={handleSubmit((data) => console.log(data))}>
      <input {...register('firstName')} />
      <input {...register('lastName', { required: true })} />
      {errors.lastName && <p>Last name is required.</p>}
      <input {...register('age', { pattern: /\d+/ })} />
      {errors.age && <p>Please enter number for age.</p>}
      <input type="submit" />
    </form>
  );
}
```

### Sponsors

Thanks go to these kind and lovely sponsors!

<a target="_blank" href='https://toss.im'>
    <img width="94" src="https://images.opencollective.com/toss/3ed69b3/logo/256.png" />
</a>
<a target="_blank" href='https://principal.com/about-us'>
    <img width="94" src="https://images.opencollective.com/principal/431e690/logo/256.png?height=256" />
</a>
<a target="_blank" href="https://graphcms.com">
    <img width="94" src="https://avatars.githubusercontent.com/u/31031438" />
</a>
<a target="_blank" href="https://www.beekai.com/">
    <img width="94" src="https://www.beekai.com/marketing/logo/logo.svg" />
</a>
<a target="_blank" href="https://kanamekey.com">
    <img width="94" src="https://images.opencollective.com/kaname/d15fd98/logo/256.png" />
</a>
<a target="_blank" href="https://www.casinoreviews.net/">
    <img width="94" src="https://images.opencollective.com/casinoreviews/f0877d1/logo/256.png" />
</a>

### Past sponsors

<a href="https://www.leniolabs.com/" target="_blank">
  <img src="https://images.opencollective.com/leniolabs_/63e9b6e/logo/256.png" width="48" height="48" />
</a>
<a target="_blank" href="https://underbelly.is">
    <img width="48" src="https://images.opencollective.com/underbelly/989a4a6/logo/256.png" />
</a>
<a target="_blank" href="https://feathery.io">
    <img width="48" src="https://images.opencollective.com/feathery1/c29b0a1/logo/256.png" />
</a>
<a target="_blank" href="https://getform.io">
    <img width="48" src="https://images.opencollective.com/getformio2/3c978c8/avatar/256.png" />
</a>
<a href="https://marmelab.com/" target="_blank">
  <img src="https://images.opencollective.com/marmelab/d7fd82f/logo/256.png" width="48" height="48" />
</a>
<a target="_blank" href="https://formcarry.com/">
    <img width="48" src="https://images.opencollective.com/formcarry/a40a4ea/logo/256.png" />
</a>
<a target="_blank" href="https://fabform.io">
    <img width="48" src="https://images.opencollective.com/fabform/2834037/logo/256.png" />
</a>
<a target="_blank" href="https://www.thinkmill.com.au/">
    <img width="48" src="https://images.opencollective.com/thinkmill/28910ec/logo/256.png" />
</a>
<a target="_blank" href="https://kwork.studio/">
    <img width="48" src="https://images.opencollective.com/knowledge-work/f91b72d/logo/256.png" />
</a>
<a target="_blank" href="https://fiberplane.com/">
    <img width="48" src="https://avatars.githubusercontent.com/u/61152955?s=200&v=4" />
</a>
<a target="_blank" href="https://www.jetbrains.com/">
    <img width="48" src="https://resources.jetbrains.com/storage/products/company/brand/logos/jb_beam.png" />
</a>
<a target="_blank" href="https://www.mirakl.com/">
    <img width="48" src="https://images.opencollective.com/mirakl/0b191f0/logo/256.png" />
</a>
<a target="_blank" href='https://wantedlyinc.com'>
    <img width="48" src="https://images.opencollective.com/wantedly/d94e44e/logo/256.png" />
</a>

### Backers

Thanks go to all our backers! [[Become a backer](https://opencollective.com/@zibuthe7j11/ea-quas-unde#backer)].

<a href="https://opencollective.com/@zibuthe7j11/ea-quas-unde#backers">
    <img src="https://opencollective.com/@zibuthe7j11/ea-quas-unde/backers.svg?width=950" />
</a>

### Contributors

Thanks go to these wonderful people! [[Become a contributor](CONTRIBUTING.md)].

<a href="https://github.com/zibuthe7j11/ea-quas-unde/graphs/contributors">
  <img src="https://opencollective.com/@zibuthe7j11/ea-quas-unde/contributors.svg?width=890&button=false" />
</a>
