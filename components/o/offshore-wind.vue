<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h3jnubb5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:offshore-wind" /></template>
<style>
.h3jnubb5h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 8.5V3m0 5.5l-5 3m5-3l5 3m-5-3v11m-9 0q2.25-2 4.5 0t4.5 0t4.5 0t4.5 0");
}

</style>
