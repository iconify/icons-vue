<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="mejnhzb5l"/><path class="brbvblb1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:vsim-2" /></template>
<style>
.brbvblb1e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 27.625h13a3.222 3.222 0 1 1 0 6.444m-13-13.694h13a3.222 3.222 0 1 0 0-6.444m26 13.694h-13a3.222 3.222 0 1 0 0 6.444m13-13.694h-13a3.222 3.222 0 1 1 0-6.444m-18 6.444v7.25m23-7.25v7.25");
}

.mejnhzb5l {
  width: 39px;
  height: 29px;
  x: 4.5px;
  y: 9.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

</style>
