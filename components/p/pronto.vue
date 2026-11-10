<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="j4d9bob7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pronto" /></template>
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

.j4d9bob7s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.76 24.448a2 2 0 0 1 2-2m-2.001 0v5.3m3.811-3.3a2 2 0 1 1 4 0v1.3a2 2 0 1 1-4 0zm15.781 0a2 2 0 1 1 4 0v1.3a2 2 0 1 1-4 0zm-5.971 3.3v-3.3a2 2 0 1 0-4 0m0 3.3v-5.3m6.86-1.65v5.95a1 1 0 0 0 1 1h.3m-2.349-5.3h2.1M8.649 28v-8h2.619c1.48 0 2.68 1.203 2.68 2.687s-1.2 2.686-2.68 2.686h-2.62");
}

</style>
