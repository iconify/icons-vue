<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="crf0mcbbl"/><path class="f9i8pu8tc"/><circle class="vg44ju7oj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:yi-home" /></template>
<style>
.crf0mcbbl {
  width: 22.115px;
  height: 32.823px;
  x: 12.988px;
  y: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 11.057px;
}

.f9i8pu8tc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.898 43.5h22.204");
}

.vg44ju7oj {
  cx: 24px;
  cy: 16.214px;
  r: 5.611px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
