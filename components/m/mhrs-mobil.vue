<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nlupcrbir"/><path class="flk5kuaij"/><circle class="zq9mbzfig"/><path class="dyvr7000u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mhrs-mobil" /></template>
<style>
.dyvr7000u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.404 17.24H38.81m1.454 17.996a2.371 2.371 0 0 0-4.401-1.221a2.371 2.371 0 0 0-4.242 2.07c.784 2.255 4.242 4.73 4.242 4.73s3.458-2.475 4.242-4.73c.1-.264.159-.55.159-.849");
}

.flk5kuaij {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.827 20.291h6.324v6.324h-6.324zm9.626 0h6.324v6.324h-6.324zm-19.251 0h6.324v6.324h-6.324zm9.625 9.838h6.324v6.324h-6.324zm-9.625 0h6.324v6.324h-6.324zM13.432 6.5h2.402a1 1 0 0 1 1 1v5.043a1 1 0 0 1-1 1h-2.402a1 1 0 0 1-1-1V7.5a1 1 0 0 1 1-1m16.713 0h2.402a1 1 0 0 1 1 1v5.043a1 1 0 0 1-1 1h-2.402a1 1 0 0 1-1-1V7.5a1 1 0 0 1 1-1");
}

.nlupcrbir {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.964 40.837H9.176a2 2 0 0 1-2-2V11.211a2 2 0 0 1 2-2h2.955m5.288 0h11.64m4.542 0h3.201a2 2 0 0 1 2 2V29.83");
}

.zq9mbzfig {
  cx: 35.777px;
  cy: 36.452px;
  r: 7.048px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
