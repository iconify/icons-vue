<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="itxcm0bbl"/><path class="v22ikkb0f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:site-plan-sharp" /></template>
<style>
.itxcm0bbl {
  d: path("M2.75 2.75h18.5v18.5H2.75z");
}

.v22ikkb0f {
  d: path("M7.75 6.5H14v4h-3v4H7v-8zm9.75 12V14m-1.25 1.25L17.5 14l1.25 1.25M2.75 18h11");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
