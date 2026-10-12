<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bic-ysbwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:traction-control-sharp" /></template>
<style>
.bic-ysbwc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 11.75V9.5l1.23-.22l.29-.06L6.5 9l.42-1.18l.66-1.89L8 4.75h8l.42 1.18l.66 1.89L17.5 9l1.23.22l.29.06l1.23.22V13H3.75zm3-2.75h10.5M8.5 15.25q-2.4 1.5 0 3c2.4 1.5 1.6 2 0 3m7-6q-2.4 1.5 0 3c2.4 1.5 1.6 2 0 3");
}

</style>
