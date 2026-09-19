<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="u6g5scyve"/><path class="av2iqpb9w"/><circle class="wkxw5hbfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:xrecorder" /></template>
<style>
.av2iqpb9w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m44 15.589l-7.678 4.432V16.65a2 2 0 0 0-2-2H13.678a2 2 0 0 0-2 2v14.7a2 2 0 0 0 2 2h20.644a2 2 0 0 0 2-2v-3.37L44 32.412a1 1 0 0 0 1.5-.867v-15.09a1 1 0 0 0-1.5-.866");
}

.u6g5scyve {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.203 39.203A21.43 21.43 0 0 1 24 45.5C12.126 45.5 2.5 35.874 2.5 24S12.126 2.5 24 2.5a21.43 21.43 0 0 1 15.203 6.297");
}

.wkxw5hbfm {
  cx: 24px;
  cy: 24px;
  r: 3px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
