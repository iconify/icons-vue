<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nwvk81bwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:trumpet-sharp" /></template>
<style>
.nwvk81bwb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m16.8 9.89l3.65-3.53l.8-.61v12.5l-.8-.61l-3.65-3.53l-.8-.61v-3zM2.75 12H16M2.75 10.5v3m3-1.5v5.5h7.5V12m-5.5 0V7.75M10.5 12V7.75M13.25 12V7.75M7 7.75h1.5m1.25 0h1.5m1.25 0H14");
}

</style>
