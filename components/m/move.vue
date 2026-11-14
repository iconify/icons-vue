<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sru_dhb3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:move" /></template>
<style>
.sru_dhb3b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.5v19M2.5 12h19M9.25 5.25L12 2.5l2.75 2.75m-5.5 13.5L12 21.5l2.75-2.75m-9.5-9.5L2.5 12l2.75 2.75m13.5-5.5L21.5 12l-2.75 2.75");
}

</style>
