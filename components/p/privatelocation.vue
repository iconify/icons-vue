<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="y-qoxogsy"/><path class="vb_uuxzdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:privatelocation" /></template>
<style>
.vb_uuxzdb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.2 4.86L6.69 11.25V27C6.69 35.44 24 43.5 24 43.5S41.31 35.44 41.31 27V11.25L25.8 4.86a4.68 4.68 0 0 0-3.6 0");
}

.y-qoxogsy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 12.41a7.26 7.26 0 0 0-7.26 7.26h0c0 5.68 5.56 12.53 7 14.21a.43.43 0 0 0 .62 0h.05c1.41-1.68 6.85-8.52 6.85-14.2A7.26 7.26 0 0 0 24 12.41m0 10a2.72 2.72 0 1 1 2.71-2.73v0a2.71 2.71 0 0 1-2.71 2.7Z");
}

</style>
