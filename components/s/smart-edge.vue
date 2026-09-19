<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="wkxw5hbfm"/><path class="y5viebclj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:smart-edge" /></template>
<style>
.wkxw5hbfm {
  cx: 24px;
  cy: 24px;
  r: 3px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.y5viebclj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M44.5 24a7.12 7.12 0 0 1-2.306 5.264H5.806C4.384 27.958 3.5 26.084 3.5 24s.884-3.958 2.306-5.264h36.388A7.12 7.12 0 0 1 44.5 24");
}

</style>
