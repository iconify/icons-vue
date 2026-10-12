<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ckg4kobif"/><path class="wnvabvbzg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sector-sharp" /></template>
<style>
.ckg4kobif {
  d: path("M11.28 19.48L3.54 8.42L2.82 7.4l1.06-.69a16 16 0 0 1 16.24 0l1.06.69l-.72 1.02l-7.74 11.06L12 20.5z");
}

.wnvabvbzg {
  d: path("M9.13 16.4a5 5 0 0 1 5.74 0");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
