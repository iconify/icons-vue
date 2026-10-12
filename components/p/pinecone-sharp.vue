<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="n9pwrjb3r"/><path class="jzcykhbjw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pinecone-sharp" /></template>
<style>
.jzcykhbjw {
  d: path("M8.75 8.25L12 10.5l3.25-2.25M8.5 13l3.5 2.5l3.5-2.5");
}

.n9pwrjb3r {
  d: path("M12 2.75c3.5 0 6.25 3.5 6.25 7.75c0 5.5-3 10.75-6.25 10.75S5.75 16 5.75 10.5c0-4.25 2.75-7.75 6.25-7.75Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
