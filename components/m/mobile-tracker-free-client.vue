<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ruocc3coy"/><circle class="l6cd208_p"/><path class="zut_6o5gt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mobile-tracker-free-client" /></template>
<style>
.l6cd208_p {
  cx: 24px;
  cy: 24px;
  r: 18.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ruocc3coy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 24v14.5c0 2.216-1.784 4-4 4H24M5.5 24V9.5c0-2.216 1.784-4 4-4H24");
}

.zut_6o5gt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.004 31.978V16.004L24 31.996l7.996-15.968v15.968");
}

</style>
