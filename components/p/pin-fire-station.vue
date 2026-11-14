<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="trhk7dd7a"/><path class="xdy2x0bok"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pin-fire-station" /></template>
<style>
.trhk7dd7a {
  d: path("M12.472 21H2.5V9.5l9.5-6l8.002 5.054m.591.373l.907.573v1.328");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xdy2x0bok {
  d: path("M5 13h6v8H5Zm13 8.5c-2.25 0-3.5-1.75-3.5-3.5s1.25-2.5 2-3.5c.25 1.25 1 1.75 1.5 1.75c0-1.5.75-2.5 1.5-3.25c1 2 2 3.25 2 5s-1.25 3.5-3.5 3.5Z");
}

</style>
