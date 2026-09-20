<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="a4ntl3b-i"/><path class="km9uii_ku"/><path class="fa3u5bc0h"/><path class="ri2m-q_tv"/><path class="xrw775b-m"/><path class="aobk5acyk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:manual-approval-duotone-bold" /></template>
<style>
.a4ntl3b-i {
  fill: currentColor;
  d: path("M10 9.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.aobk5acyk {
  d: path("M8 16.5a4 4 0 0 1 8 0");
}

.fa3u5bc0h {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 16.5a4 4 0 0 1 8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.km9uii_ku {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 3v18M4 6h16M4 18h16m0 -15v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ri2m-q_tv {
  d: path("M4 3v18M4 6h16M4 18h16m0 -15v18");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.xrw775b-m {
  d: path("M10 9.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
