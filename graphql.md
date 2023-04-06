### Type Systems

### 1. Object data type, properties modifier

```ts
  type Character {
    name: String!
    age: String // -> can null
  }
```

### 2. Type Operations

```ts
  type Query {
    hero(episode: ...): Character // -> arg can null
    droid(id: ID!): Droid // -> id must be passed
  }
```

### 3. Scalars type

- The type leave from the object type
