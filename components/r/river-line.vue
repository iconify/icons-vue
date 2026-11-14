<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="nr05u96_r"/><path class="z9fvtcc0q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:river-line" /></template>
<style>
.nr05u96_r {
  d: path("M4.5 21.5c0-6 9-6.5 9-12c0-3.5-3-5-3-7");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z9fvtcc0q {
  d: path("M10.5 21.5c0-4 9-4.5 9-12c0-4.5-3-5-3-7");
}

</style>
