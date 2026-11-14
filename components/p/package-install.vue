<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="sx0s2jckd"/><path class="i-lu2wu6h"/><path class="p1c1_lbge"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:package-install" /></template>
<style>
.i-lu2wu6h {
  d: path("m2.5 6.5l8 4l8-4m-8 4V19m-4-14.5l8 4M14 18a4 4 0 1 0 8 0a4 4 0 1 0-8 0Zm4-2v4");
}

.p1c1_lbge {
  d: path("M16.5 18.5L18 20l1.5-1.5");
}

.sx0s2jckd {
  d: path("M11.205 18.647L10.5 19l-8-4V6.5l8-4l8 4v4.756");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
