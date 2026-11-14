<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r__i8qbeg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tulip-field" /></template>
<style>
.r__i8qbeg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m2.5 6l1.75 2L6 5l1.75 3L9.5 6v4a3.5 3.5 0 0 1-7 0ZM6 13.5v8M13 9l1.25 1.5l1.25-2l1.25 2L18 9v3a2.5 2.5 0 0 1-5 0Zm2.5 5.5V18m-4 0h10m-19 3.5h19");
}

</style>
