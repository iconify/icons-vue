<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zvv1yzb7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sunrise" /></template>
<style>
.zvv1yzb7x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 19.5a5 5 0 0 1 10 0m-14.5 0h19M12 4v7.5m-2.5-5L12 4l2.5 2.5m-8 7.5L5 12.5M17.5 14l1.5-1.5");
}

</style>
