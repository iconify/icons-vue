<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="aj5p9tbck"/><circle class="kf6-t6vzx"/><path class="w5c1w6fzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:nyon-material-you-icons" /></template>
<style>
.aj5p9tbck {
  cx: 34.5px;
  cy: 13.5px;
  r: 8px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.kf6-t6vzx {
  cx: 13.5px;
  cy: 34.5px;
  r: 8px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.w5c1w6fzn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.5 21.5h-16v-16c8.837 0 16 7.163 16 16c0 1.38 1.12 2.5 2.5 2.5s2.5 1.12 2.5 2.5c0 8.837 7.163 16 16 16v-16h-16");
}

</style>
