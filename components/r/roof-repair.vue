<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jbyjcq8qm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:roof-repair" /></template>
<style>
.jbyjcq8qm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.544 20.5H3.5v-10L12 3.25l8.5 7.25v1.056m-1 2.944l-1.25 1.25a1.5 1.5 0 0 0 2 2l1.25-1.25m-3.25 1.25L15 21");
}

</style>
