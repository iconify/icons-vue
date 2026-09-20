<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ydqthzbbt"/><path class="f2l5pabqq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:photoczip" /></template>
<style>
.f2l5pabqq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.5 33.007V14.993h5.897c3.334 0 6.037 2.709 6.037 6.05s-2.703 6.05-6.037 6.05H10.5M31.533 24H37.5l-5.967 9.007H37.5m-8.097-3.02v.036a2.983 2.983 0 1 1-5.967 0v-3.04a2.983 2.983 0 1 1 5.967 0v.038");
}

.ydqthzbbt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 42.5h-29c-2.2 0-4-1.8-4-4v-29c0-2.2 1.8-4 4-4h29c2.2 0 4 1.8 4 4v29c0 2.2-1.8 4-4 4");
}

</style>
