<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bkep2if4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:rain-gauge-reading" /></template>
<style>
.bkep2if4s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 2.5h14l-2 3v14a2 2 0 0 1-2 2H9a2 2 0 0 1-2-2v-14ZM7 15h10M7 9h3.5M7 12h3.5");
}

</style>
