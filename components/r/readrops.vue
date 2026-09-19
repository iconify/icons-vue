<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="f7wqasbkf"/><circle class="lhnf4c04v"/><path class="h7aputa4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:readrops" /></template>
<style>
.f7wqasbkf {
  cx: 24px;
  cy: 24px;
  r: 9px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.h7aputa4x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.06 20H43.5m-39 0h11.44M30.7 30h12.8m-39 0h12.79M4.5 39.6H24m9 0h10.5m0-31.2H24m-9 0H4.5");
}

.lhnf4c04v {
  cx: 20.45px;
  cy: 27.55px;
  r: 2px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
