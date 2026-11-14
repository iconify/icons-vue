<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n6_zn8r8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:optics" /></template>
<style>
.n6_zn8r8p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 3a14 14 0 0 1 0 18A14 14 0 0 1 9 3ZM2.5 8.5h3.75m-3.75 7h3.75m5.5-7l9.25 7m-9.25 0l9.25-7");
}

</style>
