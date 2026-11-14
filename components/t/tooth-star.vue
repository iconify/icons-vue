<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gsy4k0w8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tooth-star" /></template>
<style>
.gsy4k0w8g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16.749 9.806c.403-.946.751-1.987.751-3.306c0-2.25-.75-4-3-4c-1.75 0-2.75.75-4.5.75S7.25 2.5 5.5 2.5c-2.25 0-3 1.75-3 4c0 2.5 1.25 4 1.75 5.75L5 17c.25 1.5 2 1.5 2.5 0l1-3.25c.5-1.25 2.5-1.25 3 0l.065.212M17.75 14l1.029 2.084l2.3.334l-1.665 1.623l.393 2.291l-2.057-1.082l-2.057 1.082l.393-2.291l-1.665-1.623l2.3-.334Z");
}

</style>
