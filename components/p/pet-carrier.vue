<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hpstaobxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pet-carrier" /></template>
<style>
.hpstaobxp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 7h19v14h-19Zm4 0V5.5A2.5 2.5 0 0 1 9 3h6a2.5 2.5 0 0 1 2.5 2.5V7m-8 4v6m5-6v6");
}

</style>
