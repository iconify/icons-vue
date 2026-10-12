<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ejn2y0b4i"/><path class="en6spubez"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:policy" /></template>
<style>
.ejn2y0b4i {
  d: path("M10.5 21.25H7.25a2.5 2.5 0 0 1-2.5-2.5V5.25a2.5 2.5 0 0 1 2.5-2.5h6.5l5.5 5.5v2");
}

.en6spubez {
  d: path("M13.75 2.75v3.5a2 2 0 0 0 2 2h3.5m-11 3.5h3.5M8.25 15h2M17 13.25l3.5 1.25V17c0 2.25-1.5 3.5-3.5 4.25c-2-.75-3.5-2-3.5-4.25v-2.5Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
