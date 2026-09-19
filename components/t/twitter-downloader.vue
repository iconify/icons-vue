<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="a00kobcff"/><circle class="iv34yub_k"/><path class="yazjg8bzf"/><path class="farvr_bbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:twitter-downloader" /></template>
<style>
.a00kobcff {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.358 18.77v.703c0 7.076-5.369 15.185-15.193 15.185c-2.9.007-5.738-.836-8.165-2.424q.633.086 1.272.077c2.404.007 4.74-.795 6.633-2.277a5.31 5.31 0 0 1-4.989-3.717q.5.105 1.012.106c.475 0 .948-.064 1.405-.19a5.32 5.32 0 0 1-4.279-5.235v-.07c.74.413 1.57.64 2.417.66a5.3 5.3 0 0 1-1.68-7.07a15.16 15.16 0 0 0 11.02 5.58a4.5 4.5 0 0 1-.148-1.222a5.305 5.305 0 0 1 9.254-3.732a11 11 0 0 0 3.394-1.3a5.38 5.38 0 0 1-2.382 3A11.2 11.2 0 0 0 37 15.96a10.9 10.9 0 0 1-2.641 2.811Z");
}

.farvr_bbk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m35.203 39.203l3.297 3.296l3.297-3.296");
}

.iv34yub_k {
  cx: 38.5px;
  cy: 38.499px;
  r: 7px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yazjg8bzf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.432 43.326A21.4 21.4 0 0 1 24 45.5C12.126 45.5 2.5 35.874 2.5 24S12.126 2.5 24 2.5S45.5 12.126 45.5 24c0 3.383-.781 6.583-2.173 9.43M38.5 42.499v-8");
}

</style>
