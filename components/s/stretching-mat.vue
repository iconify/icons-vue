<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="f1a5tcbce"/><path class="la_xb4efh"/><path class="f6-gvibuw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:stretching-mat" /></template>
<style>
.f1a5tcbce {
  d: path("M4.25 10.5L15.75 5a4 4 0 0 1 3.5 7l-11.5 5.5");
}

.f6-gvibuw {
  d: path("M6 12.75A1.25 1.25 0 1 1 4.75 14m6-6.5l3.5 7m-1-8.25l3.5 7");
}

.la_xb4efh {
  d: path("M2 14a4 4 0 1 0 8 0a4 4 0 1 0-8 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
