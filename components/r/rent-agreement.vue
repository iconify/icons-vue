<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="lz2v-bc6z"/><path class="u3w__cbuk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:rent-agreement" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lz2v-bc6z {
  width: 15.5px;
  height: 18.5px;
  x: 4.25px;
  y: 2.75px;
  rx: 1.5px;
}

.u3w__cbuk {
  d: path("M9 10.25v-3L12 5l3 2.25v3Zm-1 3.5h8m-8 4c.75-1.25 1.5-1.25 1.75 0s1 .75 1.75-.5s1.25-.5 1.5.25h3");
}

</style>
