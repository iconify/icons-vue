<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="o354ch2ep"/><path class="c_2zh39bb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pin-wildfire" /></template>
<style>
.c_2zh39bb {
  d: path("M12 18.5c-1.5 0-2.5-1-2.5-2.5s1.5-2.5 2.5-4c1 1.5 2.5 2.5 2.5 4s-1 2.5-2.5 2.5Z");
}

.o354ch2ep {
  d: path("M12 21.5c-4.5 0-7-3-7-6.5c0-4.5 4-6.5 5-12c3.5 2 4.5 5 4.5 7.5c1-1 1.5-2 1.75-3C18 9.5 19 12 19 15c0 3.5-2.5 6.5-7 6.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
