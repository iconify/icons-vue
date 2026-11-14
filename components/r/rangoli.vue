<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zdgu3ybil"/><path class="fzt5-fp_l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:rangoli" /></template>
<style>
.fzt5-fp_l {
  d: path("M16.75 12a1.75 1.75 0 0 1-1.5 3.25a1.75 1.75 0 0 1-3.25 1.5a1.75 1.75 0 0 1-3.25-1.5A1.75 1.75 0 0 1 7.25 12a1.75 1.75 0 0 1 1.5-3.25A1.75 1.75 0 0 1 12 7.25a1.75 1.75 0 0 1 3.25 1.5a1.75 1.75 0 0 1 1.5 3.25ZM12 12h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zdgu3ybil {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0Z");
}

</style>
