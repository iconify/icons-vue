<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="kr71oacge"/><path class="ikcxdfx3c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sequence-resume" /></template>
<style>
.ikcxdfx3c {
  d: path("m10 2.5l2 2l-2 2M10 9l5.5 3.5L10 16Z");
}

.kr71oacge {
  d: path("M20 12.5a8 8 0 1 1-8-8");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
