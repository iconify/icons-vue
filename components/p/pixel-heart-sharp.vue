<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="tvcvnp45p"/><path class="r8wocdcfy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pixel-heart-sharp" /></template>
<style>
.r8wocdcfy {
  d: path("M6.25 7.5h1.5V9h-1.5z");
}

.tvcvnp45p {
  d: path("M6.25 4.5h4.5V7h2.5V4.5h5V7h2.5v5h-2.5v2.5h-2.5V17h-2.5v2.5h-2.5V17h-2.5v-2.5h-2.5V12h-2.5V7h2.5V4.5z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
