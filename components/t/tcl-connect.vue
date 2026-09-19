<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><circle class="l6cd208_p"/><path class="r62d9zsrx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tcl-connect" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.l6cd208_p {
  cx: 24px;
  cy: 24px;
  r: 18.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.r62d9zsrx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.492 19.209v9.584h4.738m-24.46-9.584h6.278m-3.139 9.584v-9.584m13 6.369v.04c0 1.753-1.405 3.174-3.139 3.174s-3.139-1.421-3.139-3.175v-3.234c0-1.754 1.405-3.175 3.139-3.175s3.139 1.421 3.139 3.175v.039M9.015 39.421a1.5 1.5 0 1 1 2.122-2.121M24 5.5a1.5 1.5 0 0 1 0-3");
}

</style>
