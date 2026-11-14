<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="g6ulkabjn"/><path class="s57x0eefx"/><path class="kx2yu6e8z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:podcast-cover" /></template>
<style>
.g6ulkabjn {
  d: path("M2.5 2.5h19v19h-19Z");
}

.kx2yu6e8z {
  d: path("M8.818 14.682a4.5 4.5 0 1 1 6.364 0M12 13.25v5.5");
}

.s57x0eefx {
  d: path("M10.25 11.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
