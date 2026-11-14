<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a01fxbbfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pencil-ruler" /></template>
<style>
.a01fxbbfm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 2.5h3A1.75 1.75 0 0 1 9.5 4.25v15.5a1.75 1.75 0 0 1-1.75 1.75h-3A1.75 1.75 0 0 1 3 19.75V4.25A1.75 1.75 0 0 1 4.75 2.5m10.75 0H18A1.5 1.5 0 0 1 19.5 4v11.146a1.5 1.5 0 0 1-.158.671l-1.25 2.5a1.5 1.5 0 0 1-2.684 0l-1.25-2.5a1.5 1.5 0 0 1-.158-.671V4a1.5 1.5 0 0 1 1.5-1.5M3 6h2.75M3 9.5h2M3 13h2.75M3 16.5h2M14 6h5.5M14 15.5h5.5");
}

</style>
