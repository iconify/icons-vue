<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ov2ka0vck"/><path class="ehcngrjeu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:roof-felt" /></template>
<style>
.ehcngrjeu {
  d: path("M4 5v14a5 2.5 0 0 0 10 0V5m0 1.5c4.5 0 6.5 2.5 6.5 6.5v8.5");
}

.ov2ka0vck {
  d: path("M4 5a5 2.5 0 1 0 10 0A5 2.5 0 1 0 4 5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
