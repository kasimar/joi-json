# Type: `uuid`

The `uuid` type is short cut type that automatically configures the `string` type to accept uuid values. This type can be used to parse both UUIDs and GUIDS. Joi-JSON
will map this type to the `Joi.string().guid()` schema.

# String notation

```js
{
    id: 'uuid,required'
}
```

# Object notation

```js
{
    id: {

        '@type': 'uuid',
        required: true
    }
}
```

For more information on this type, see the [Joi documentation](https://github.com/hapijs/joi/blob/v8/API.md).
