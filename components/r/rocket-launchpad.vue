<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ikuh3-btn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:rocket-launchpad" /></template>
<style>
.ikuh3-btn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 20.5h19M4 5h3.5v15.5H4Zm3.5 5h6m0 10.5V9c0-3 2.5-5.5 2.5-5.5S18.5 6 18.5 9v11.5m-5-5l-2 2.5v2.5m7-5l2 2.5v2.5");
}

</style>
