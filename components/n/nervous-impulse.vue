<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u6pewoubx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:nervous-impulse" /></template>
<style>
.u6pewoubx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 13.75a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m5 0h3l2-6.5l2 6.5h7m0-2.75v5.5");
}

</style>
