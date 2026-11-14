<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pqbqubb7o"/><path class="eu2-dbvoj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:skip-truck" /></template>
<style>
.eu2-dbvoj {
  d: path("M16 18.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM2.5 6.5h10l-1.5 10H4Z");
}

.pqbqubb7o {
  d: path("M15 16.5V9h3.5l3 3.5v4m-19 0h19M5 18.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
