<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iu6vc453z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ski-start-gate" /></template>
<style>
.iu6vc453z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 2.5v19m12-19v19M4.75 6.5h14.5A1.75 1.75 0 0 1 21 8.25A1.75 1.75 0 0 1 19.25 10H4.75A1.75 1.75 0 0 1 3 8.25A1.75 1.75 0 0 1 4.75 6.5");
}

</style>
