<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="nq5dvkfgq"/><path class="r02d1nb9l"/><path class="ricsl-blc"/><path class="uy3jp_bjh"/><path class="i30itkxpw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:sprout-duotone-bold" /></template>
<style>
.i30itkxpw {
  d: path("M12.5 13c0 -4.8 3.2 -8 8 -8 0 4.8 -3.2 8 -8 8");
}

.nq5dvkfgq {
  fill: currentColor;
  d: path("M3.5 13c0 -4.8 3.2 -8 8 -8 0 4.8 -3.2 8 -8 8");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.r02d1nb9l {
  fill: currentColor;
  d: path("M12.5 13c0 -4.8 3.2 -8 8 -8 0 4.8 -3.2 8 -8 8");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ricsl-blc {
  d: path("M12 12v9");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.uy3jp_bjh {
  d: path("M3.5 13c0 -4.8 3.2 -8 8 -8 0 4.8 -3.2 8 -8 8");
}

</style>
