<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kjhf5jbcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:population-density" /></template>
<style>
.kjhf5jbcr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m2.5 4.5l6-2l7 2l6-2v17l-6 2l-7-2l-6 2Zm3.5 3h.01M9 7.5h.01M6 10.5h.01m2.99 0h.01m-1.51 3h.01M14.5 12h.01m3.24 4.75h.01");
}

</style>
