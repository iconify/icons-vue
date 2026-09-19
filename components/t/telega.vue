<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lh73gmbmn"/><path class="l-oq_w7iq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:telega" /></template>
<style>
.l-oq_w7iq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m18.624 23.315l8.721-5.488l12.489 12.157m-3.842-16.922l5.879 5.325");
}

.lh73gmbmn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.694 23.542L41.16 7.452c1.218-.537 2.543.5 2.313 1.812L38.238 39.07c-.276 1.576-2.222 2.174-3.336 1.026L18.624 23.315l-13.78.846c-.36.022-.48-.473-.15-.62Z");
}

</style>
