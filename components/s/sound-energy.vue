<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uqqdjqbib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sound-energy" /></template>
<style>
.uqqdjqbib {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.714 8.17a5 5 0 0 1 0 7.66M6.606 4.723a9.5 9.5 0 0 1 0 14.554M14.5 19v-5m3.5 5v-9m3.5 9V5");
}

</style>
