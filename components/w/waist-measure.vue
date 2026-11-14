<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cz14brb_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:waist-measure" /></template>
<style>
.cz14brb_e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.116 9h9.768a1.75 1.75 0 0 1 1.745 1.61l.72 9a1.75 1.75 0 0 1-1.745 1.89h-2.218a1.75 1.75 0 0 1-1.703-1.349L13 17.25a1.027 1.027 0 0 0-2 0l-.683 2.901A1.75 1.75 0 0 1 8.614 21.5H6.396a1.75 1.75 0 0 1-1.745-1.89l.72-9A1.75 1.75 0 0 1 7.116 9M4.25 4.5h15.5a1.75 1.75 0 0 1 1.75 1.75A1.75 1.75 0 0 1 19.75 8H4.25A1.75 1.75 0 0 1 2.5 6.25A1.75 1.75 0 0 1 4.25 4.5M6 4.5V6m3.5-1.5V6M13 4.5V6m3.5-1.5V6");
}

</style>
