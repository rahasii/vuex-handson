<template lang="html">
  <div class="sample">
    <h1>{{ title }}</h1>
    Hello, I'm {{ name }}
    <div class="slot">
      <slot/>
    </div>
  </div>
</template>


<script>
export default {
  props: {
    title: {
      type: String,
      default: 'Defalut Title'
    }
  },
  data() {
    return {
      name: 'rahasii'
    }
  }
}
</script>
