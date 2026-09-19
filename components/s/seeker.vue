<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="w621d6uos"/><path class="sbzj6k87x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:seeker" /></template>
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

.sbzj6k87x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.637 32.246a57 57 0 0 1 .015-8.475m11.418-4.729a2.754 2.754 0 1 1 5.396-1.102");
}

.w621d6uos {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M3.336 28.58s4.168 3.371 5.3 3.666m.01-8.302a13.516 13.516 0 0 1 24.267-7.821l6.565.353c1.068.057 1.694.85 1.09 1.67c-.329.328-4.911 5.498-4.911 5.498c-.916 1.142-6.094 6.174 4.225 14.847");
}

</style>
