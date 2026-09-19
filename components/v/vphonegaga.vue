<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="dcasrybal"/><path class="be2pmv3la"/><path class="toc_fcc9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:vphonegaga" /></template>
<style>
.be2pmv3la {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.998 9a1.5 1.5 0 0 0-1.3 2.25l15.589 27a1.5 1.5 0 0 0 2.597 0l6.026-10.434a1.5 1.5 0 0 0 0-1.5L19.345 9.75a1.5 1.5 0 0 0-1.3-.75z");
}

.dcasrybal {
  cx: 23.997px;
  cy: 30px;
  r: 1px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.toc_fcc9h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.003 9a1.5 1.5 0 0 1 1.298 2.25l-15.588 27a1.5 1.5 0 0 1-2.597 0L19.09 27.816a1.5 1.5 0 0 1 0-1.5L28.655 9.75a1.5 1.5 0 0 1 1.3-.75z");
}

</style>
