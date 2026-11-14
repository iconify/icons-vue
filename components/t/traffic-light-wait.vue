<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="arzuhkb5i"/><path class="bx8m3_-9t"/><path class="dxb93lbjm"/><path class="pvadtm1vs"/><path class="a6k62accz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:traffic-light-wait" /></template>
<style>
.a6k62accz {
  d: path("M18 16.5V18l1.25 1");
}

.arzuhkb5i {
  d: path("M12 18.1V22H3V2h9v15.9");
}

.bx8m3_-9t {
  d: path("M6 6.25a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

.dxb93lbjm {
  fill: currentColor;
  d: path("M6 12a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

.pvadtm1vs {
  d: path("M6 17.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm8.75.25a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
