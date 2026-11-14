<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="av8i1cgfc"/><path class="l2ceo8b6x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:obsidian" /></template>
<style>
.av8i1cgfc {
  d: path("M3.5 17L7 6l6-3.5l7.5 6L17 21Z");
}

.l2ceo8b6x {
  d: path("M13 2.5L11.5 12l5.5 9");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
