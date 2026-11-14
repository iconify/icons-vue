<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ziwkelb-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:social-distancing" /></template>
<style>
.ziwkelb-j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 20.5c0-3.5 1.25-5.75 3.25-5.75S9 17 9 20.5Zm12.5 0c0-3.5 1.25-5.75 3.25-5.75S21.5 17 21.5 20.5ZM3.25 9.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm12.5 0a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm-6.5 0h5.5m-4-1.5l-1.5 1.5l1.5 1.5m2.5-3l1.5 1.5l-1.5 1.5");
}

</style>
