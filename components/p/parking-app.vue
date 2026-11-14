<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="f8dhrmbma"/><path class="e3od_zb8f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:parking-app" /></template>
<style>
.e3od_zb8f {
  d: path("M10 7h2.5a2.75 2.75 0 0 1 0 5.5H10");
}

.f8dhrmbma {
  d: path("M6 2.5h12v19H6ZM10 17V7");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
