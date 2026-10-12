<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="j10p-abjp"/><path class="sjzllzb4j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:toner-bottle-sharp" /></template>
<style>
.j10p-abjp {
  d: path("M7.75 3h4.5v3h-4.5zm4.5 1h1.5m-7.5 5h7.5v12.25h-7.5z");
}

.sjzllzb4j {
  d: path("m6.25 13.5l1.875-1.125L10 13.5l1.875 1.125L13.75 13.5m4.75-3.75c1.5 2 2.5 3.25 2.5 4.5a2.5 2.5 0 0 1-5 0c0-1.25 1-2.5 2.5-4.5Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
