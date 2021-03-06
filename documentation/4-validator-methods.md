# 4. Validator methods

## 4.1 `getCounter` obtains the index of the object being validated

* `getCounter()`

## 4.2 `failFastRule` when enabled, if one validation group fails the others will not be validated.

* `failFastRule()`

## 4.3 `setPropertyOnContext` when a value instance is being validated it will be available in context with the declared property name

* `setPropertyOnContext(final String property)`

## 4.4 `getPropertyOnContext` when a value instance is available in context with the declared property name it can be retrieved anywhere in the validation tree.

* `getPropertyOnContext(final String property, final Class<P> clazz)`

## 4.5 `validate` instance

* `validate(final T instance)`

## 4.6 `validate` instance with transform results

* `validate(final T instance, final ValidationResultTransform<E> transform)`

## 4.7 `validate` collection

* `validate(final Collection<T> instances)`

## 4.8 `validate` collection with transform results

* `validate(final Collection<T> instances, final ValidationResultTransform<E> transform)`

## 4.9 `ruleFor` instance

* `ruleFor(final Function<T, P> function)`

## 4.10 `ruleFor` instance with field name

* `ruleFor(final String fieldName, final Function<T, P> function)`

## 4.11 `ruleForEach` collection

* `ruleForEach(final Function<T, Collection<P>> function)`

## 4.12 `ruleForEach` collection with field name

* `ruleForEach(final String fieldName, final Function<T, Collection<P>> function)`
