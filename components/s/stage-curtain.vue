<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nx07kybqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:stage-curtain" /></template>
<style>
.nx07kybqp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 3.5h19M4 3.5v17h3c.5-3.5 1.5-5 3-6C7 12 6 8 6.25 3.5M20 3.5v17h-3c-.5-3.5-1.5-5-3-6c3-2.5 4-6.5 3.75-11");
}

</style>
