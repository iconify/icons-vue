<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="u13u3ccnj"/><path class="ths3rcbby"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mood-sensitive" /></template>
<style>
.ths3rcbby {
  d: path("M8.75 17.25q2.25 2 4.5 0M16.5 7.5l-2.75-2.75C12.75 3.75 13.5 2 15 2c.75 0 1.25.5 1.5 1c.25-.5.75-1 1.5-1c1.5 0 2.25 1.75 1.25 2.75Z");
}

.u13u3ccnj {
  d: path("M4.5 15a6.5 6.5 0 1 0 13 0a6.5 6.5 0 1 0-13 0Zm4.25-1.25h.01m4.49 0h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
