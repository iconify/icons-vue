<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="br8a3ccjk"/><path class="pcoq0kllo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:package-json" /></template>
<style>
.br8a3ccjk {
  d: path("M9.526 17.263L2.5 13.75v-7.5L10 2.5l7.5 3.75v4.215");
}

.pcoq0kllo {
  d: path("M2.5 6.25L10 10l7.5-3.75M10 10v6.8m5.5-3.55h-.25q-1 0-1 1v2.25l-1 1l1 1v2.25q0 1 1 1h.25m4-8.5h.25q1 0 1 1v2.25l1 1l-1 1v2.25q0 1-1 1h-.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
