<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="e4mqvczqi"/><path class="rc9v4_v0w"/><path class="fml2qzxuh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sort-linear" /></template>
<style>
.e4mqvczqi {
  d: path("M22 7L2 7");
}

.fml2qzxuh {
  d: path("M16 17H8");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rc9v4_v0w {
  d: path("M19 12L5 12");
}

</style>
