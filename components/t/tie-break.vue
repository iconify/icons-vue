<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xi6lqwgsy"/><path class="poqrzecws"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tie-break" /></template>
<style>
.poqrzecws {
  d: path("M20.25 4.75a3.5 4.5 45 1 1-6.5 6.5a3.5 4.5 45 1 1 6.5-6.5Zm-6.5 6.5L5 20m-.5-9.5l5-5m5 0l5 5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xi6lqwgsy {
  d: path("M3.75 4.75a3.5 4.5-45 1 1 6.5 6.5a3.5 4.5-45 1 1-6.5-6.5Zm6.5 6.5L19 20");
}

</style>
