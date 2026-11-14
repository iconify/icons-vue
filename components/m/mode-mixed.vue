<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jlad1zbgy"/><path class="t8xn1_fhh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mode-mixed" /></template>
<style>
.jlad1zbgy {
  d: path("M3.5 4.75a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm2 4.75l-.5 5l-2 6m2-6l2.25 6m2.25-2.25a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Zm7.5 0a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Z");
}

.t8xn1_fhh {
  d: path("M11.75 18.25L14 13.5h3.75l1.5 4.75m-1.5-4.75l-.75-3h1.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
