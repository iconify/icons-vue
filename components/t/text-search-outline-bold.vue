<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="xgrfb-bqu"/><path class="t407ddc6o"/><path class="edsmp8bai"/><path class="e2rc7m64w"/><path class="wus2r4r7n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:text-search-outline-bold" /></template>
<style>
.e2rc7m64w {
  d: path("M13.5 15a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.edsmp8bai {
  d: path("M3 18h8");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.t407ddc6o {
  d: path("M3 12h8");
}

.wus2r4r7n {
  d: path("m18.5 17 2.5 2.5");
}

.xgrfb-bqu {
  d: path("M3 6h18");
}

</style>
