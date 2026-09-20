<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="v34_7jb3k"/><circle class="yj2oxvl4f"/><path class="srq5_h-9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pixel-experience" /></template>
<style>
.srq5_h-9e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 9.404V3.5m0 22.304v5.904m8.2-14.104h5.904m-22.304 0H9.896M15.8 29.078v12.47a2.952 2.952 0 0 1-5.904 0V17.605");
}

.v34_7jb3k {
  cx: 24px;
  cy: 17.604px;
  r: 14.104px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yj2oxvl4f {
  cx: 24px;
  cy: 17.604px;
  r: 8.2px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
