<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="knir0lbiw"/><path class="uxon5q_0n"/><circle class="zqvvr-bpz"/><path class="gvaizkb6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:wot-compendium-unofficial" /></template>
<style>
.gvaizkb6b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.391 33.752a3.582 3.582 0 0 0 0-7.164m0-7.163a3.582 3.582 0 1 0 0 7.163");
}

.knir0lbiw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.904 10.115L5.82 41.256a37.6 37.6 0 0 1 11.237-2.006Z");
}

.uxon5q_0n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.392 18.182c1.675-2.77 7.454-9.03 15.44-12.682c-2.006 7.504 3.692 24.279 8.347 31.623c-14.567.441-31.743 5.377-31.743 5.377a4.65 4.65 0 0 1 0-2.504");
}

.zqvvr-bpz {
  cx: 27.391px;
  cy: 26.588px;
  r: 7.163px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
