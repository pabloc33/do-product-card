# DO-Product-Card

Este es un paquete de pruebas de despliegues en NPM

### Pablo Contino

## Ejemplo

```
import {ProductCard, ProductImage, ProductTitle, ProductButtons} from 'dp-product-card';
```

```
<ProductCard
key={product.id}
product={product}
initialValues={{
          count: 4,
          maxCount: 10,
        }} >
{({ reset, count, increseBy, maxCount, isMaxCountReached }) => (
<>
<ProductImage />
<ProductTitle />
<ProductButtons />
</>
)}
</ProductCard>
```
