<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pyb1-gt5y"/><path class="anvw7138m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:office-signage" /></template>
<style>
.anvw7138m {
  d: path("m8 12.5l-2 2l2 2m-2-2h4.5m5.5-2l2 2l-2 2m2-2h-4.5");
}

.pyb1-gt5y {
  d: path("M2.5 9.75h19v9.5h-19Zm4.5 0l5-5.25l5 5.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
