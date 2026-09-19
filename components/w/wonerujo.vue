<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qo-8tebjf"/><circle class="unndf0b4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:wonerujo" /></template>
<style>
.qo-8tebjf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m23.69 28.847l.02-15.472m15.6 16.116c.081-5.299-.005-10.817-.005-16.116c-.209-3.57-.695-7.039-7.349-8.766M8.233 13.375v15.471c0 8.11 15.342 8.213 15.471 0c-.01 8.29 15.471 7.98 15.6.645m-31.086-.644v6.961");
}

.unndf0b4b {
  cx: 39.032px;
  cy: 42.642px;
  r: 0.75px;
  fill: currentColor;
}

</style>
