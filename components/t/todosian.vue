<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ox8athu-y"/><path class="tejyjcbdt"/><path class="zqt69gbvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:todosian" /></template>
<style>
.ox8athu-y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36 10.1H12l-6.5 8.6L24 37.9l18.5-19.2zM5.5 18.7h29.3");
}

.tejyjcbdt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 37.9l-8.9-19.2l5.6-8.6m6.4 0l5.2 8.6");
}

.zqt69gbvt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39 14L25.7 29.1l-2.9-3.8l-3.4 2.6");
}

</style>
