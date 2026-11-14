<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t6zpl0boy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ruler-vertical" /></template>
<style>
.t6zpl0boy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.625 2.5h4.75A2.625 2.625 0 0 1 17 5.125v13.75a2.625 2.625 0 0 1-2.625 2.625h-4.75A2.625 2.625 0 0 1 7 18.875V5.125A2.625 2.625 0 0 1 9.625 2.5M7 6.5h3.5M7 10h5.5M7 13.5h3.5M7 17h5.5");
}

</style>
