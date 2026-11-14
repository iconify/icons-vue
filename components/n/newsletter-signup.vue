<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zgqzskgiz"/><path class="xye4ag6lj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:newsletter-signup" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xye4ag6lj {
  d: path("M8.5 5.5L12 8l3.5-2.5M6 17.5h8");
}

.zgqzskgiz {
  d: path("M6 2.5h12V11H6ZM2.5 14h19v7h-19Z");
}

</style>
