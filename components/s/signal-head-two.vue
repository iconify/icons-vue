<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="brswkjbqa"/><path class="r_m_3abxv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:signal-head-two" /></template>
<style>
.brswkjbqa {
  d: path("M7.5 4.5h9v15h-9Z");
}

.r_m_3abxv {
  d: path("M10.5 8.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm0 6.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
