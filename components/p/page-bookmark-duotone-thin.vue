<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bfxqopr2s"/><path class="kfp8u8bco"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:page-bookmark-duotone-thin" /></template>
<style>
.bfxqopr2s {
  fill: currentColor;
  d: path("M7 3h10v18l-5 -5 -5 5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kfp8u8bco {
  d: path("M7 3h10v18l-5 -5 -5 5Z");
}

</style>
