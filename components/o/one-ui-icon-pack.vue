<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dqhxnerpl"/><path class="pt09rtbrs"/><rect class="f_4t88xfh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:one-ui-icon-pack" /></template>
<style>
.dqhxnerpl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4M37.652 20v8");
}

.f_4t88xfh {
  width: 5.3px;
  height: 8px;
  x: 10.348px;
  y: 20px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.65px;
  ry: 2.65px;
}

.pt09rtbrs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.884 28v-3.3a2 2 0 0 0-2-2h0a2 2 0 0 0-2 2m0 3.3v-5.3M30.208 20v5.35a2.65 2.65 0 1 0 5.3 0V20m-7.701 6.99A2 2 0 0 1 26.069 28h0a2 2 0 0 1-2-2v-1.3a2 2 0 0 1 2-2h0a2 2 0 0 1 2 2v.65h-4");
}

</style>
