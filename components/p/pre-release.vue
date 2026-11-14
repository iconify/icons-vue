<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="f16lxt_oz"/><path class="h201gnb1o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pre-release" /></template>
<style>
.f16lxt_oz {
  d: path("M12.21 16.395L10 17.5l-7.5-3.75v-7.5L10 2.5l7.5 3.75v2.915");
}

.h201gnb1o {
  d: path("M2.5 6.25L10 10l7.5-3.75M10 10v7.5m5 4.5v-7.5a2.5 2.5 0 0 1 5 0a2.5 2.5 0 0 1-2.5 2.5a2.5 2.5 0 0 1 0 5c-1 0-1.75-.5-2.5-1.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
