<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="acyqt5bdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:turbine-maintenance" /></template>
<style>
.acyqt5bdc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 8.5v-6m0 6l-5.25 3m5.25-3l5.25 3m-5.25-3v13m-3 0h5.6m8.4-7.5a2.5 2.5 0 1 0 2 2m-7 5l2.75-2.75");
}

</style>
