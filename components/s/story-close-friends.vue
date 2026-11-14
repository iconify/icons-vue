<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w2wd1sb5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:story-close-friends" /></template>
<style>
.w2wd1sb5q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.65 2.644a9.5 9.5 0 0 1 7.706 7.706m0 3.3a9.5 9.5 0 0 1-7.706 7.706m-3.3 0a9.5 9.5 0 0 1-7.706-7.706m0-3.3a9.5 9.5 0 0 1 7.706-7.706M12 6l1.5 4.25l4.75.25l-3.75 2.75l1.25 4.5l-3.75-2.5l-3.75 2.5l1.25-4.5l-3.75-2.75l4.75-.25Z");
}

</style>
