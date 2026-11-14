<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="orya24biw"/><path class="ssry9ybuz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:select-invert" /></template>
<style>
.orya24biw {
  d: path("M3.5 7V5.5a2 2 0 0 1 2-2H7m10 0h1.5a2 2 0 0 1 2 2V7m0 10v1.5a2 2 0 0 1-2 2H17m-10 0H5.5a2 2 0 0 1-2-2V17m7-13.5h3m-3 17h3m-10-10v3m17-3v3m-13-6h9v9h-9Z");
}

.ssry9ybuz {
  d: path("M16.5 7.5V15a1.5 1.5 0 0 1-1.5 1.5H7.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
