<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fp9a08bgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:opening-weekend" /></template>
<style>
.fp9a08bgs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 3.5h19M3 3.5h7.5Q6 9 6 12t1.5 5.5H3Zm18 0h-7.5Q18 9 18 12t-1.5 5.5H21Zm-18.5 17h19");
}

</style>
