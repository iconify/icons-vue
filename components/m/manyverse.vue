<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ll0g54h-q"/><circle class="lr2ac3wch"/><g class="y9tr6bcfx"><path class="gmk9iopod"/><circle class="i6p9wibdr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:manyverse" /></template>
<style>
.gmk9iopod {
  d: path("m12.708 31.88l.02-19.105c.232-1.246 2.068-1.51 2.623-.222L22.7 33.796a1.4 1.4 0 0 0 1.301 1.018a1.4 1.4 0 0 0 1.3-1.018l7.349-21.243c.555-1.289 2.391-1.024 2.623.222l.02 19.105");
}

.i6p9wibdr {
  cx: 35.292px;
  cy: 34.087px;
  r: 2.208px;
}

.ll0g54h-q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29c-2.2 0-4 1.8-4 4v29c0 2.2 1.8 4 4 4h29c2.2 0 4-1.8 4-4v-29c0-2.2-1.8-4-4-4");
}

.lr2ac3wch {
  cx: 12.708px;
  cy: 34.087px;
  r: 2.208px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
