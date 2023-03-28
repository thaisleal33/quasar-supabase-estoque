# Quasar + Supabase estoque app (quasar-estoque-supabase)

## Init Config

Necessário configurar no arquivo ***quasar.conf.js*** suas credenciais do supabase

```js
build: {
  env: {
    SUPABASE_URL: 'XXXX',
    SUPABASE_KEY: 'YYYY'
  }
}
```

## Instalando as dependências
```bash
npm i
```

### Development mode (hot-code reloading, error reporting, etc.)
```bash
quasar dev
```

### Build p/ produção
```bash
quasar build
```

### Customize a configuração do seu jeito
[Configurando quasar.conf.js](https://quasar.dev/quasar-cli/quasar-conf-js).
