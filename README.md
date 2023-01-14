Este es un paquete de pruebas de despliegue en npm

### Francisco Limaico

### Ejemplo

```
<ProductCard
        product={product}
        initialValues={{
          count: 4,
          maxCount: 10,
        }}
      >
        {({ reset, increaseBy, count, isMaxCountReached }) => (
          <>
            <ProductImage />
            <ProductTitle />
            <ProductButtons />
          </>
        )}
</ProductCard>
```