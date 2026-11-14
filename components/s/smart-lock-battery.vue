<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d17f_sbrc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:smart-lock-battery" /></template>
<style>
.d17f_sbrc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 21H2.5V10h10v4.1M4.75 10V6.75a2.75 2.75 0 0 1 5.5 0V10M7.5 13.5v4m8-1.75h4.25a1 1 0 0 1 1 1v.5h1v1.5h-1v.5a1 1 0 0 1-1 1H15.5a1 1 0 0 1-1-1v-2.5a1 1 0 0 1 1-1Z");
}

</style>
