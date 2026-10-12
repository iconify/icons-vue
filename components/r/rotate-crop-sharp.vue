<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ycte86joj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:rotate-crop-sharp" /></template>
<style>
.ycte86joj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 2.75v13.5h14.5m-18.5-9.5h10.5v14.5M15 3.5a4.75 4.75 0 0 1 4.75 4.75m-1.5-1.5l1.5 1.5l1.5-1.5");
}

</style>
