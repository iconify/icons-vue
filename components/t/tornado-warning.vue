<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="owhrnxb4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tornado-warning" /></template>
<style>
.owhrnxb4g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 10h11.5a2.75 2.75 0 0 0 0-5.5a5 5 0 0 0-8.5.25A2.75 2.75 0 0 0 6 10Zm.5 3H15m-6.5 3.5h5m-4 3.5h3m5.5-5.5V18m0 3h.01");
}

</style>
