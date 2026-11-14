<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hxugbob5c"/><path class="fiuluzb6o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:map-boss-marker" /></template>
<style>
.fiuluzb6o {
  d: path("M8 10a4 4 0 0 1 8 0v2.75h-1.75V15h-4.5v-2.25H8Zm2.5.25h.01m2.99 0h.01");
}

.hxugbob5c {
  d: path("M12 21.5C7 16.5 4.5 13 4.5 10a7.5 7.5 0 0 1 15 0c0 3-2.5 6.5-7.5 11.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
