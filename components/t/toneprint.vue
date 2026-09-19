<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="joiomubtv"/><circle class="xsqzccc6b"/><path class="je3hzdbmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:toneprint" /></template>
<style>
.je3hzdbmn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 7.5v11.964m-8.99 18.374V10.171m17.984 27.658V10.18");
}

.joiomubtv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 2.5c11.867 0 21.5 9.633 21.5 21.5c0 11.877-9.633 21.5-21.5 21.5c-11.877 0-21.5-9.623-21.5-21.5C2.5 12.133 12.123 2.5 24 2.5");
}

.xsqzccc6b {
  cx: 24px;
  cy: 24px;
  r: 16.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
