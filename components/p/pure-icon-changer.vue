<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="qqwfmrkwm"/><path class="pmg9edprm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pure-icon-changer" /></template>
<style>
.pmg9edprm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 24v19.5M19.692 24A4.308 4.308 0 1 1 24 19.692V24zM24 19.692A4.308 4.308 0 1 1 28.308 24H24zM28.308 24A4.308 4.308 0 1 1 24 28.308V24zM24 28.308A4.308 4.308 0 1 1 19.692 24H24z");
}

.qqwfmrkwm {
  cx: 24px;
  cy: 24px;
  r: 19.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
