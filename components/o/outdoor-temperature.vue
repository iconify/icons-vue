<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="y723hkbir"/><path class="qd996pboi"/><path class="fufqkqfij"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:outdoor-temperature" /></template>
<style>
.fufqkqfij {
  d: path("M14.25 8.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Zm2.25-4.25V3m0 9.75V14m4.25-5.5H22m-9.75 0H11m8.5-3l1-1m-7 1l-1-1m7 7l1 1m-7-1l-1 1");
}

.qd996pboi {
  fill: currentColor;
  d: path("M5 16.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y723hkbir {
  d: path("M4.5 13.5V5a2 2 0 0 1 4 0v8.5a3.75 3.75 0 1 1-4 0Zm2-5.5v7");
}

</style>
