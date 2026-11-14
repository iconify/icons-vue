<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xqi8tub1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ski-pole" /></template>
<style>
.xqi8tub1z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 7.5v14m0-19zA1.5 1.5 0 0 1 13.5 4v2A1.5 1.5 0 0 1 12 7.5A1.5 1.5 0 0 1 10.5 6V4A1.5 1.5 0 0 1 12 2.5M9.5 18h5m-4-13C8 6 7.5 9 9 10.5");
}

</style>
