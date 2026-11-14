<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k06l94b4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:robot-charging" /></template>
<style>
.k06l94b4d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.7 18.5H2.5v-12h16v6.8m-8-9.8v3m-3 5.5h.01m5.99 0h.01M19 14.5l-4.25 4H18l-1 3.25l4.25-4.25H18Z");
}

</style>
