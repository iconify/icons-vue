<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kfdb2bc9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:refresh-dashed-sharp" /></template>
<style>
.kfdb2bc9o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M19.48 8.51A8.25 8.25 0 0 0 3.75 12m16.5-7.5v4.25H16M4.52 15.49A8.25 8.25 0 0 0 20.25 12m-16.5 7.5v-4.25H8");
}

</style>
