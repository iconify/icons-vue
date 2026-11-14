<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="shtnemkps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:night-skiing" /></template>
<style>
.shtnemkps {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 3a5.5 5.5 0 1 0 4 8a4.5 4.5 0 0 1-4-8ZM2.5 20.5l19-6.5M18 12.5v-7M16 3h5v2.5h-5Z");
}

</style>
