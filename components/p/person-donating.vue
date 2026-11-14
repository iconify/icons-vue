<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gogk1ybfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:person-donating" /></template>
<style>
.gogk1ybfi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 13.5H6c1 0 1.75.5 2.5 1.25l1.5 1.5h4.5l4.25-3.5a1.75 1.75 0 0 1 2 2.25L16 20.25c-.5.5-1 .75-1.75.75H2.5M9 7.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0Zm4-1.25v2.5");
}

</style>
