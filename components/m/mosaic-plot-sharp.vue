<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="j8mho8b-u"/><path class="sw6h5bcuw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mosaic-plot-sharp" /></template>
<style>
.j8mho8b-u {
  d: path("M2.75 2.75h18.5v18.5H2.75zm7 0v18.5m-7-7h7m0-6.25h11.5");
}

.sw6h5bcuw {
  d: path("M12.25 10.5h6.5v8.25h-6.5z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
