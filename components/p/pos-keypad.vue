<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="g6ulkabjn"/><path class="fdtws-btj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pos-keypad" /></template>
<style>
.fdtws-btj {
  d: path("M15.75 5.5h2.75v13h-2.75Zm-9.5 1.25h.01m3.24 0h.01m3.24 0h.01M6.25 12h.01m3.24 0h.01m3.24 0h.01m-6.51 5.25h.01m3.24 0h.01m3.24 0h.01");
}

.g6ulkabjn {
  d: path("M2.5 2.5h19v19h-19Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
