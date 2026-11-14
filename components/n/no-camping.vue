<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lm03r2map"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:no-camping" /></template>
<style>
.lm03r2map {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 19.5h13.1M4 19.5l4.217-7.38m2.878-5.036L12 5.5l3.461 6.056M7.5 19.5L10 14l2.5 5.5m-9-16l17 17");
}

</style>
