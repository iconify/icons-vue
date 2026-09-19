<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i3d3hvbvy"/><circle class="rct93mrgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:torchie" /></template>
<style>
.i3d3hvbvy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.54 11.28L24 5.5l4.44 5.78m0 25.44l-4.46 5.78l-4.44-5.78m22.44-12.71h-7.41m-21.14 0H6.02m10.5 7.47l-5.23 5.24m5.23-20.19l-5.24-5.24m20.18 5.24l5.24-5.24m-5.23 20.19l5.23 5.24");
}

.rct93mrgj {
  cx: 24px;
  cy: 24.01px;
  r: 7.37px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
