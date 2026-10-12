<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sq3-hpaxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:prism-sharp" /></template>
<style>
.sq3-hpaxm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.54 5.13l5.92 12.24l.54 1.13H5l.54-1.13l5.92-12.24L12 4zM2.75 14l5-1.5M17 10.75l4.25-1.25m-3.75 4l3.75 1m-4 1.75l3.5 2.25");
}

</style>
