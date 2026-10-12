<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wl67qxbmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:patch-cable-sharp" /></template>
<style>
.wl67qxbmd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 5.25h3.5v6h-3.5zm12 0h3.5v6h-3.5zM6 11.25v3.5c0 3.6 2.7 6.5 6 6.5s6-2.9 6-6.5v-3.5m-12-6v-2.5m12 2.5v-2.5");
}

</style>
