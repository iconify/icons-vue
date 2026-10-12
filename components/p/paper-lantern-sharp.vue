<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="x6laivbdq"/><path class="wsyir7piu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:paper-lantern-sharp" /></template>
<style>
.wsyir7piu {
  d: path("M12 6.75v11.5M9 7c-1.75 3.25-1.75 7.75 0 11m6-11c1.75 3.25 1.75 7.75 0 11");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x6laivbdq {
  d: path("M12 2.75V6m0 13v2.25M4.5 12.5C4.5 8.9 7.85 6 12 6s7.5 2.9 7.5 6.5S16.15 19 12 19s-7.5-2.9-7.5-6.5Z");
}

</style>
