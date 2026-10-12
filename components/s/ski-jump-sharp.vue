<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vloa5obke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ski-jump-sharp" /></template>
<style>
.vloa5obke {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 21.25V2.75h3.75M10 21.25V2.75h3.75M16 4.5v16.75M20 4.5v16.75m-5.25-3.5h2.5m1.5 0h2.5");
}

</style>
