<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="o8dd-fbld"/><circle class="c_lx_rsko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:publix" /></template>
<style>
.c_lx_rsko {
  cx: 24.914px;
  cy: 22.824px;
  r: 4.784px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.o8dd-fbld {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.914 12.941c-5.458 0-9.889 4.425-9.881 9.883c.006 4.779 0 9.559 0 14.338c0 .819.463 1.477 1.04 1.477h2.786c.576 0 1.04-.658 1.04-1.477V31.34a9.9 9.9 0 0 0 5.015 1.367c5.459 0 9.884-4.425 9.883-9.883c0-5.459-4.424-9.884-9.883-9.883");
}

</style>
