<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ur2r28hkd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:resizer" /></template>
<style>
.ur2r28hkd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3.5v17M2.5 12h6M4.75 9.75L2.5 12l2.25 2.25M15.5 12h6m-2.25-2.25L21.5 12l-2.25 2.25");
}

</style>
