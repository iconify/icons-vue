<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bcpp8mbal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:smart-garden" /></template>
<style>
.bcpp8mbal {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.5 5.75l1.5-3h14l1.5 3Zm3 9.25h11L16 21H8Zm5.5 0V9.5m0 2.75q-5 0-5.5-3.75q3 .25 5.5 3.75m0 0q5 0 5.5-3.75q-3 .25-5.5 3.75");
}

</style>
