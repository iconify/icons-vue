<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zkj8t6b_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:power-sleep" /></template>
<style>
.zkj8t6b_q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16.25 4.639A8.5 8.5 0 0 1 20.5 12M12 20.5A8.5 8.5 0 0 1 7.75 4.639M12 2.5V10m5.75 5A3 3 0 1 0 21 18.25A2.5 2.5 0 0 1 17.75 15Z");
}

</style>
