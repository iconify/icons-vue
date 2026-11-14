<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ersy5zbyg"/><path class="j8ni8ik0d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:valve-chamber" /></template>
<style>
.ersy5zbyg {
  d: path("M2.5 2.5h19v19h-19Zm0 12.5h7m5 0h7");
}

.j8ni8ik0d {
  d: path("M9.5 15a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm2.5-2.5V8M9 8h6");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
