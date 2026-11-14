<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vd6lmr8nq"/><path class="znwst_b2t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:water-butt" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vd6lmr8nq {
  d: path("M5 3h10c1.5 5 1.5 13 0 18H5C3.5 16 3.5 8 5 3ZM4 8.25h12");
}

.znwst_b2t {
  d: path("M16 15.5h3.5V18");
}

</style>
