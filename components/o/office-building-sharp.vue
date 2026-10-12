<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="t632olb1f"/><path class="la4yn1b5e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:office-building-sharp" /></template>
<style>
.la4yn1b5e {
  d: path("M10 21.25v-3h4v3");
}

.t632olb1f {
  d: path("M6.75 21.25h-2V7.75h3.5v-4h7.5v4h3.5v13.5h-2Zm1.5-10v3.5m3.75-3.5v3.5m3.75-3.5v3.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
