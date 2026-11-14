<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="l9spfr4_e"/><path class="y9e8twb_p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:power-cord" /></template>
<style>
.l9spfr4_e {
  d: path("M13 7h8v3a3 3 0 0 1-3 3h-2a3 3 0 0 1-3-3Zm2.5-4v4m3-4v4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y9e8twb_p {
  d: path("M17 13v3a4.5 4.5 0 0 1-4.5 4.5H8A3.5 3.5 0 0 1 4.5 17V4");
}

</style>
