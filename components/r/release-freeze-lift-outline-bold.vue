<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ri2m-q_tv"/><path class="kcomyoe5y"/><path class="gn1ganbdv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:release-freeze-lift-outline-bold" /></template>
<style>
.gn1ganbdv {
  d: path("M10.5 10a1.5 1.5 0 0 1 3 0");
}

.kcomyoe5y {
  d: path("M9 12h6v3H9Z");
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

</style>
