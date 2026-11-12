<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="nx9b_s0ui"/><path class="itvkagoch"/><path class="kpzw3mbym"/><path class="zj2p4py0y"/><path class="cwatz7g8l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:wi-fi-cross-linear" /></template>
<style>
.cwatz7g8l {
  d: path("M22 5.00002L19 8.00001M19 8.00001L16 11M19 8.00001L16 5M19 8.00001L21.9999 11");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.itvkagoch {
  d: path("M5.33301 12.295C7.42965 10.032 10.2681 9.05764 13.0035 9.37195");
}

.kpzw3mbym {
  d: path("M2 8.69694C5.01816 5.43925 9.06111 3.96185 13.0088 4.26472");
}

.nx9b_s0ui {
  d: path("M8.66699 15.8931C10.5079 13.9061 13.4927 13.9061 15.3337 15.8931");
}

.zj2p4py0y {
  stroke-linejoin: round;
  d: path("M12.0176 19.4644H12.0177");
}

</style>
