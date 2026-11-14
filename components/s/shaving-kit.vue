<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e_zkwj_sr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:shaving-kit" /></template>
<style>
.e_zkwj_sr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.889 5.093l6.01 6.011a1.75 1.75 0 0 1 0 2.474a1.75 1.75 0 0 1-2.474 0l-6.011-6.01a1.75 1.75 0 0 1 0-2.475a1.75 1.75 0 0 1 2.475 0m.53 5.48l-3.182 3.182m0 0za1.25 1.25 0 0 1 0 1.768l-4.242 4.243a1.25 1.25 0 0 1-1.768 0a1.25 1.25 0 0 1 0-1.768l4.243-4.243a1.25 1.25 0 0 1 1.767 0");
}

</style>
