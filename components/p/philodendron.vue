<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lt2y-uwtp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:philodendron" /></template>
<style>
.lt2y-uwtp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 8c-1.5-3.5-7.5-3.5-7.5 2c0 4.5 4 8 7.5 11.5c3.5-3.5 7.5-7 7.5-11.5c0-5.5-6-5.5-7.5-2m0 0V2.5M12 8v10.5m0-5.5l-4-3m4 3l4-3");
}

</style>
