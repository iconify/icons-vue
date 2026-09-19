<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="bem_qszsv"/><rect transform="matrix(-1 0 0 -1 43.657 46.925)" class="ymf0_abyc"/><path class="jxm_bhsnh"/><rect transform="matrix(-1 0 0 -1 57.05 46.925)" class="mshu_nb6j"/><path class="yexxh6sjk"/><path class="netpdysae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:piggy" /></template>
<style>
.bem_qszsv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.106 20.445v6.833a2.28 2.28 0 0 1-2.278 2.277h0a2.27 2.27 0 0 1-1.61-.667");
}

.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.jxm_bhsnh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.803 20.445v6.833a2.28 2.28 0 0 1-2.278 2.277h0a2.27 2.27 0 0 1-1.61-.667");
}

.mshu_nb6j {
  width: 4.555px;
  height: 6.036px;
  x: 26.248px;
  y: 20.445px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.278px;
  ry: 2.278px;
}

.netpdysae {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.5 20.445v3.758a2.28 2.28 0 0 1-2.278 2.278h0a2.28 2.28 0 0 1-2.277-2.278v-3.758m-15.692 0v6.035M10.5 24.203a2.28 2.28 0 0 0 2.278 2.277h0a2.28 2.28 0 0 0 2.277-2.277v-1.48a2.28 2.28 0 0 0-2.277-2.278h0a2.28 2.28 0 0 0-2.278 2.277m0-2.277v9.11");
}

.yexxh6sjk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.5 24.203v3.075a2.28 2.28 0 0 1-2.278 2.277h0a2.27 2.27 0 0 1-1.61-.667");
}

.ymf0_abyc {
  width: 4.555px;
  height: 6.036px;
  x: 19.551px;
  y: 20.445px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.278px;
  ry: 2.278px;
}

</style>
