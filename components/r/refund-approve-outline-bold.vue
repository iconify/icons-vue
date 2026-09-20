<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="jd_dotbnq"/><path class="o7jy28bce"/><path class="cpsm-qevf"/><path class="myn7q3llc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:refund-approve-outline-bold" /></template>
<style>
.cpsm-qevf {
  d: path("M9 7.5 6.5 10 9 12.5");
}

.jd_dotbnq {
  d: path("M6 2h12a2 2 0 0 1 2 2v15l-2 -2 -2 2 -2 -2 -2 2 -2 -2 -2 2 -2 -2 -2 2V4a2 2 0 0 1 2 -2");
}

.myn7q3llc {
  d: path("m13 10.5 2 2 2.5 -2.5");
}

.o7jy28bce {
  d: path("M6.5 10H11");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
