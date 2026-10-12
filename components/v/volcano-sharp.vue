<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="c17usmf9j"/><path class="ehu3gubgw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:volcano-sharp" /></template>
<style>
.c17usmf9j {
  d: path("M9.25 9.25h5.5l6.1 10.4l1.306 1.733l-2.166-.133H4.01l-2.166.133L3.15 19.65Z");
}

.ehu3gubgw {
  d: path("M12 9.25v3.5L10 15m2-12.25v3.5m-4.25-2.5l1.5 2.5m7-2.5l-1.5 2.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
