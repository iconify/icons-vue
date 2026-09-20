<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ri2m-q_tv"/><path class="xrw775b-m"/><path class="aobk5acyk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:manual-approval-outline-bold" /></template>
<style>
.aobk5acyk {
  d: path("M8 16.5a4 4 0 0 1 8 0");
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
