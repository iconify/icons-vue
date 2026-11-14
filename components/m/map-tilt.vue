<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="si_iu_u-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:map-tilt" /></template>
<style>
.si_iu_u-q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6.5 6l3.75-1.5l3.5 1.5l3.75-1.5l4 13.5l-6.5 2l-6-2l-6.5 2Zm3.75-1.5L9 18m4.75-12L15 20");
}

</style>
