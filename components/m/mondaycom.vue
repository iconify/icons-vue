<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="jicwfjsyr"/><path class="bwo_1dbaq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mondaycom" /></template>
<style>
.bwo_1dbaq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.75 12.763a4.5 4.5 0 0 0-2.827 1.97L5.171 28.415a4.5 4.5 0 0 0 7.582 4.851v-.001l8.752-13.682a4.5 4.5 0 0 0-1.364-6.216l-.001-.001a4.5 4.5 0 0 0-3.39-.603m15.036 0a4.5 4.5 0 0 0-2.824 1.97L20.21 28.415a4.5 4.5 0 0 0 7.58 4.85l8.754-13.682a4.5 4.5 0 0 0-1.365-6.216l-.002-.001a4.5 4.5 0 0 0-3.39-.604");
}

.jicwfjsyr {
  cx: 39.038px;
  cy: 30.84px;
  r: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
