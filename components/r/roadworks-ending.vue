<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dou4ohbzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:roadworks-ending" /></template>
<style>
.dou4ohbzs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.25 15.5l3.5-13h2l3.5 13m-1.95 3H2.5v-3h10.8M6.5 7H11m-5.5 4H12m2.75 7l2 2L21 15.75");
}

</style>
