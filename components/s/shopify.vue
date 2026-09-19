<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="aer8ac1re"/><path class="dvf-2pbor"/><path class="jnzglr9zs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:shopify" /></template>
<style>
.aer8ac1re {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.254 38.314L30.803 42.5l9.943-2.093l-4.31-28.696l-3.017-.086l-2.616-2.617l-20.409 6.28zM30.803 9.009V42.5");
}

.dvf-2pbor {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.063 31.18c.77 1.004 1.735 1.377 3.079 1.377h1.86a3.133 3.133 0 0 0 3.132-3.133v-.014a3.133 3.133 0 0 0-3.133-3.133h-2.05a3.136 3.136 0 0 1-3.137-3.136a3.143 3.143 0 0 1 3.143-3.143h1.85c1.343 0 2.308.373 3.078 1.376m-3.286-9.226c-.995-3.663 5.694-9.34 7.386-2.272");
}

.jnzglr9zs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.553 13.7c1.41-8.73 10.122-11.633 9.822-3.022");
}

</style>
