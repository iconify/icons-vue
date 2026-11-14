<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="olzbnx0_e"/><path class="gqrrg154p"/><path class="aujcgoije"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:octahedron" /></template>
<style>
.aujcgoije {
  d: path("m12 2.5l-1.5 11l1.5 8");
}

.gqrrg154p {
  d: path("m4 11l6.5 2.5L20 11");
}

.olzbnx0_e {
  d: path("m12 2.5l8 8.5l-8 10.5L4 11Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
