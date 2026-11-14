<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="n0bp65b1i"/><path class="jsuac-tha"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tablet-charging" /></template>
<style>
.jsuac-tha {
  d: path("m12.75 7.25l-2 3.75h2.5l-2 3.75");
}

.n0bp65b1i {
  d: path("M4 2.5h16v19H4Zm6.5 16h3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
