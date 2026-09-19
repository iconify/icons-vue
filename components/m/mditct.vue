<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="lr0u3u13p"/><path class="iz9rpjlkp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mditct" /></template>
<style>
.iz9rpjlkp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.04 31.96L5.5 42.5M22 28.455L27.106 13.5M32 28.5l-4.894-15m3.257 9.982h-6.665");
}

.lr0u3u13p {
  cx: 27px;
  cy: 21px;
  r: 15.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
