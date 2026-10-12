<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="x8ksupb-t"/><path class="hjqo8pkao"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mosque-dome-sharp" /></template>
<style>
.hjqo8pkao {
  d: path("M10.25 21.25V17h3.5v4.25m-7-4.25v1.5m10.5-1.5v1.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x8ksupb-t {
  d: path("M4.75 14.25c0-4 3.5-6.5 7.25-8c3.75 1.5 7.25 4 7.25 8Zm-1 0h16.5v7H3.75zM12 2.75v3.5");
}

</style>
