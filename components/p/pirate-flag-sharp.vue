<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="e1jgy-aym"/><path class="lpbfd9beg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pirate-flag-sharp" /></template>
<style>
.e1jgy-aym {
  d: path("M6.75 2.75h14.5v13H6.75z");
}

.lpbfd9beg {
  d: path("M13.75 5.25h-2.1v3.155l1 .545v.8h2.2v-.8l1-.545V5.25zm-3 6l6 2m0-2l-6 2m-6.5-10.5v18.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
