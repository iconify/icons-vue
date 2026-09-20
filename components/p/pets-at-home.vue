<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="w4jwhdbpe"/><path class="yoqpibcbq"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pets-at-home" /></template>
<style>
.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.w4jwhdbpe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.35 29.796V16.204h4.45c2.516 0 4.555 2.044 4.555 4.565s-2.04 4.565-4.555 4.565h-4.45c-2.209 0-2.85-.867-2.85-.867m25.197 4.001c.518.855 1.29 1.328 2.794 1.328h.763a2.25 2.25 0 0 0 2.246-2.251a2.25 2.25 0 0 0-2.246-2.251h-1.525a2.25 2.25 0 0 1-2.246-2.252a2.25 2.25 0 0 1 2.246-2.25h.762c1.505 0 2.175.238 2.795.759m-9.546-3.563v10.11c0 .937.76 1.698 1.698 1.698h.51c1.385 0 1.749-1.328 1.749-1.328m-5.62-7.677h3.446");
}

.yoqpibcbq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.214 28.081a3.398 3.398 0 0 1-6.35-1.683v-2.209a3.398 3.398 0 0 1 6.796 0v1.105h-6.797");
}

</style>
