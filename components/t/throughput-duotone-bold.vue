<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ei8gh2b1p"/><path class="yjhy2wbtm"/><path class="t1fwo7qnk"/><path class="it8u_fbzt"/><path class="zuuudpbwi"/><path class="dzvfone4k"/><path class="k134iabcj"/><path class="cks97xg-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:throughput-duotone-bold" /></template>
<style>
.cks97xg-s {
  d: path("m14 13 3 3 -3 3");
}

.dzvfone4k {
  d: path("m14 5 3 3 -3 3");
}

.ei8gh2b1p {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 8h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.it8u_fbzt {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m14 13 3 3 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.k134iabcj {
  d: path("M3 16h14");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.t1fwo7qnk {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 16h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.yjhy2wbtm {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m14 5 3 3 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zuuudpbwi {
  d: path("M3 8h14");
}

</style>
