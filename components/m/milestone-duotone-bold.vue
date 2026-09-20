<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="d5b4fcc2f"/><path class="e_jc_gvct"/><path class="p5t8n6pcv"/><path class="z9ittvbis"/><path class="vavi9cbgb"/><path class="k5g5kukae"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:milestone-duotone-bold" /></template>
<style>
.d5b4fcc2f {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 19h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.e_jc_gvct {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 7v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.k5g5kukae {
  d: path("M8 7h10l-4 4 4 4H8");
}

.p5t8n6pcv {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 7h10l-4 4 4 4H8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.vavi9cbgb {
  d: path("M8 7v12");
}

.z9ittvbis {
  d: path("M2 19h20");
}

</style>
