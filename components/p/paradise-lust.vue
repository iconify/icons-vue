<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="l6px8ybyh"/><circle class="dqy_2gbug"/><path class="pt44n8bwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:paradise-lust" /></template>
<style>
.dqy_2gbug {
  cx: 24px;
  cy: 23.966px;
  r: 11.199px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.l6px8ybyh {
  cx: 24px;
  cy: 24px;
  r: 21.38px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.pt44n8bwu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m10.287 7.597l7.113 7.322m-9.976-4.424l7.32 7.166M37.535 7.449l-7.248 7.25m10.46-3.99l-7.489 6.956M30.35 33.19l7.26 7.298m-4.281-10.326l7.362 7.198m-25.856-6.957L7.357 37.42m10.473-4.107l-7.318 7.276");
}

</style>
