<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tx6hqy6xp"/><path class="fxy_2tw9h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:podcast-studio" /></template>
<style>
.fxy_2tw9h {
  d: path("M6.25 9.5a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0Zm-1.5 12c0-3.75 1.75-6 4.25-6s4.25 2.25 4.25 6M15.5 7H19v6h-3.5Zm1.75 6v8.5");
}

.tx6hqy6xp {
  d: path("M2.5 21.5V5A2.5 2.5 0 0 1 5 2.5h14A2.5 2.5 0 0 1 21.5 5v16.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
