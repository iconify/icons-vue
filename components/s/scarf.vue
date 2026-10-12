<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vq0g1_bdd"/><path class="gr4zibb6d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:scarf" /></template>
<style>
.gr4zibb6d {
  d: path("M13.5 8.25h2.25q.75 0 .42.67l-4.09 8.41Q11.75 18 11 18H6q-.75 0-.29-.59l6.58-8.57q.46-.59 1.21-.59M6 18v3.25M8.5 18v3.25M11 18v3.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vq0g1_bdd {
  d: path("M9.25 9.75c-2.75-2.75-1.5-7 2.75-7s4.75 3.25 3.5 5.5");
}

</style>
