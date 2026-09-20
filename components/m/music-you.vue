<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="qb81tbb2n"/><path class="o-yracb0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:music-you" /></template>
<style>
.o-yracb0d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.66 35.378V12.834M28.69 4.5h6.864a2.03 2.03 0 0 1 2.03 2.03v4.273a2.03 2.03 0 0 1-2.03 2.03H26.66V6.53a2.03 2.03 0 0 1 2.03-2.03");
}

.qb81tbb2n {
  cx: 18.538px;
  cy: 35.378px;
  r: 8.122px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
