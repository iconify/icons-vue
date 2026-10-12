<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="oh5eun6ew"/><path class="dx6g-kbij"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:shoe-cabinet-sharp" /></template>
<style>
.dx6g-kbij {
  d: path("M6.75 11.25v-3.5h2l.4 1.551l1.6-.051h3.5l2.084-.042l.416 2.042Zm.75 8v-3.5h2l.4 1.551l1.6-.051H15l2.084-.042l.416 2.042Z");
}

.oh5eun6ew {
  d: path("M3.75 21.25V4.75h16.5v16.5m-16.5-10h16.5m-16.5 8h16.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
