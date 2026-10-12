<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="g-48vhpdu"/><path class="ah8jctbmd"/><circle class="k6r3zgz2g"/><circle class="sotefpb_j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:toy-train-sharp" /></template>
<style>
.ah8jctbmd {
  d: path("M15 7.5h3.25v3.75H15Z");
}

.g-48vhpdu {
  d: path("M2.75 13.25V9h2V4.5h3.5V9H12V4.5h9.25v9.75H2.75z");
}

.k6r3zgz2g {
  cx: 6.75px;
  cy: 19.25px;
  r: 2px;
}

.sotefpb_j {
  cx: 17px;
  cy: 19.25px;
  r: 2px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
