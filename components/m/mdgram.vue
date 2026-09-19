<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="jzyi1bwgh"/><path class="vpm69ouys"/><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mdgram" /></template>
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

.jzyi1bwgh {
  cx: 18.813px;
  cy: 18.814px;
  r: 4.278px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.vpm69ouys {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m21.318 15.35l.486-.486c2.34-2.35 6.319-1.549 7.57 1.52l4.77 11.72c1.55 3.8-2.24 7.589-6.04 6.04l-11.719-4.77c-3.07-1.251-3.87-5.23-1.521-7.57l.486-.486");
}

</style>
