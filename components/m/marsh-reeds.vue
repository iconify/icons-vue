<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="n3mw8bbsp"/><path class="curbr4b5o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:marsh-reeds" /></template>
<style>
.curbr4b5o {
  d: path("M2.5 19.5q2.375-1.25 4.75 0t4.75 0t4.75 0t4.75 0");
}

.n3mw8bbsp {
  d: path("M12 19.5V11m0-6.5v-2m-1.5 2h3V11h-3Zm-1.25 15C9 14 7 9.5 3.5 7m11.25 12.5C15 14 17 9.5 20.5 7");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
