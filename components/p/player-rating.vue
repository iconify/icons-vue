<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mw1yq9bhl"/><path class="bq_d3gb-w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:player-rating" /></template>
<style>
.bq_d3gb-w {
  d: path("M5.5 8.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0ZM13 7h3.5M13 10.5h2.5m2.25 3.5l1.029 2.084l2.3.334l-1.665 1.623l.393 2.291l-2.057-1.082l-2.057 1.082l.393-2.291l-1.665-1.623l2.3-.334Z");
}

.mw1yq9bhl {
  d: path("M11 17H2.5V3h17v8.3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
