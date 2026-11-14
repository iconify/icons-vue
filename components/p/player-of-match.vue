<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tktcy7bdi"/><path class="rdpkg2bds"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:player-of-match" /></template>
<style>
.rdpkg2bds {
  d: path("M5 5.5H2.5V7a3 3 0 0 0 2.75 3M15 5.5h2.5V7a3 3 0 0 1-2.75 3M10 13.5v.7m0 1.8v2m-2.5 0h4.6m5.65-4l1.029 2.084l2.3.334l-1.665 1.623l.393 2.291l-2.057-1.082l-2.057 1.082l.393-2.291l-1.665-1.623l2.3-.334Z");
}

.tktcy7bdi {
  d: path("M5 3.5h10v5a5 5 0 0 1-10 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
