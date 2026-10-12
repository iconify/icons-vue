<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u2zr34b4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ship-crane-sharp" /></template>
<style>
.u2zr34b4c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 21.25v-17m-2.75 17h5.5m-6.5-17h18.5M6.5 8.5l4.25-4.25m7.25 0v8m-3.25.5h6.5v4.75h-6.5zm2.25 1.5V16m2-1.75V16");
}

</style>
