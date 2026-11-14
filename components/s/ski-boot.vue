<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gkyt4lbti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ski-boot" /></template>
<style>
.gkyt4lbti {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 3h6l.75 6.5L19.5 13c1.1.75 1.5 1.75 1.5 3v3.5H3.5v-3l3-7Zm-4 13.5H21M8.25 7h5m-5.5 5.5H16");
}

</style>
