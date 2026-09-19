<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="x_ssngb7v"/><path class="lbi_dn5ty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:my-pixel" /></template>
<style>
.lbi_dn5ty {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.762 15.562a3.356 3.356 0 0 1 0-6.712h10.476a3.356 3.356 0 0 1 0 6.712z");
}

.x_ssngb7v {
  width: 22.96px;
  height: 39px;
  x: 12.52px;
  y: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

</style>
