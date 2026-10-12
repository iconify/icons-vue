<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="tl81b-b1l"/><path class="c0kteelpl"/><path class="pjgexrs9j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:squirrel-sharp" /></template>
<style>
.c0kteelpl {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.25 21.25H9.917l.733-2.2l1.6-4.8l.715-2.144l-.815-1.956l-.667-1.668L13 7.5l1.5-.95l.5-2.3l1.6 1.55h.9A3.5 3.5 0 0 1 21 9.3v1.75h-3.25l1.25 2.5v2.5c0 2.75-1.75 5.2-5.25 5.2Z");
}

.pjgexrs9j {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17.5 8.5h.01");
}

.tl81b-b1l {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 21.25c-2.75 0-5.25-3.25-5.25-7.75C2.75 7.5 5.5 3 9 3c2 0 3.25 1.25 3.25 3v2.5h-2.5c-1.75 0-2.5 1.5-2.5 4c0 3 .25 6 .75 8.75Z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
