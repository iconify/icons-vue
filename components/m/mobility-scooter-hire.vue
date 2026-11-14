<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="sk-wfsb1e"/><path class="fasrnrb4z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mobility-scooter-hire" /></template>
<style>
.fasrnrb4z {
  d: path("M4.5 4v7.5H11m-2.5 0V16m-5.25 2.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm11.75 0a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Z");
}

.sk-wfsb1e {
  d: path("M3 16h11.5c1 0 1.5-.5 2-1.5L18.75 6M16 5.5h5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
