<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wyythyb1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:telescope-plus" /></template>
<style>
.wyythyb1o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.799 10.842L17.3 4.08l1.901 4.078L4.7 14.92ZM11 12l-4.5 9m4.5-9l1.237 5.564M18 15v6m-3-3h6");
}

</style>
