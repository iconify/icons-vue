<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z9wv9yeob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:view-front" /></template>
<style>
.z9wv9yeob {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 9h9v9h-9Zm0 0l3-3h9v9l-3 3m0-9l3-3m-19 7.5h4.25M4.25 11l2.5 2.5l-2.5 2.5");
}

</style>
