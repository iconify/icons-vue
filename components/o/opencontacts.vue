<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fhw3vczax"/><path class="vb_uuxzdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:opencontacts" /></template>
<style>
.fhw3vczax {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 12.72a4.5 4.5 0 1 1-4.5 4.5a4.5 4.5 0 0 1 4.5-4.5m0 11.19c5 0 9 1.4 9 3.07v4.3H15V27c0-1.69 4-3.09 9-3.09");
}

.vb_uuxzdb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.2 4.86L6.69 11.25V27C6.69 35.44 24 43.5 24 43.5S41.31 35.44 41.31 27V11.25L25.8 4.86a4.68 4.68 0 0 0-3.6 0");
}

</style>
