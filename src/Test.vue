<template>
  <div>
    {{ foo }}
  </div>
</template>

<script>
export default {
  props: {
    foo: String,
    bar: {type: String, required: false},
    camelCaseBar: {type: String, required: false},
  }
}
</script>
