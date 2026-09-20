<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="fsuht_b8c"/><path class="jxonqxbcf"/><path class="gbjtkzb6z"/><path class="oze4upblc"/><path class="acyg6nb1v"/><path class="idhymedkk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:viewpoint-duotone-bold" /></template>
<style>
.acyg6nb1v {
  d: path("M10 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.fsuht_b8c {
  fill: currentColor;
  d: path("M10 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.gbjtkzb6z {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m2 20 6 -6 3 3 5 -5 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.idhymedkk {
  d: path("m2 20 6 -6 3 3 5 -5 5 5");
}

.jxonqxbcf {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6.36 5.95a6 6 0 0 1 11.28 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.oze4upblc {
  d: path("M6.36 5.95a6 6 0 0 1 11.28 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
