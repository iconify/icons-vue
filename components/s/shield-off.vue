<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t8edvac_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:shield-off" /></template>
<style>
.t8edvac_w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.132 4.168L12 2.75l7.5 2.75v6c0 1.252-.22 2.405-.626 3.455m-3.425 4.391c-1.012.762-2.176 1.398-3.449 1.904c-4.4-1.75-7.5-5.05-7.5-9.75V8.432M3.5 3.5l17 17");
}

</style>
