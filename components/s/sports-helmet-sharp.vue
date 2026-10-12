<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="d3_zm4bxz"/><path class="c-4xeztvv"/><path class="jve_nxd9n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sports-helmet-sharp" /></template>
<style>
.c-4xeztvv {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.75 12.5h.01");
}

.d3_zm4bxz {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3.25A8.75 8.75 0 0 1 20.25 9H12.5v6.25H16v5H8.5A5.25 5.25 0 0 1 3.25 15v-3A8.75 8.75 0 0 1 12 3.25Z");
}

.jve_nxd9n {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16.5 11.75h4.75v6H18");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
