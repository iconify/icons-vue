<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sln-7obqv"/><path class="qvbfq_bwu"/><path class="iq5-4acyl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tesla" /></template>
<style>
.iq5-4acyl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.586 9.541L24 13.431l4.414-3.89");
}

.qvbfq_bwu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.479 14.678A10.7 10.7 0 0 1 7.556 12.8c4.22-2.427 12.03-3.26 12.03-3.26L24 41.906l4.414-32.364s7.81.832 12.03 3.259a10.7 10.7 0 0 1-2.923 1.878");
}

.sln-7obqv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 10.28A50.8 50.8 0 0 1 24 6.095a50.8 50.8 0 0 1 19.5 4.185");
}

</style>
