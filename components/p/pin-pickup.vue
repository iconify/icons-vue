<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="r4b6y8h0g"/><path class="r0cgiyb_v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pin-pickup" /></template>
<style>
.r0cgiyb_v {
  d: path("m13.5 18.5l5.25-2.5a1.6 1.6 0 0 1 2 2.5l-5.75 3H2.5M13 3v3.5");
}

.r4b6y8h0g {
  d: path("M8 3h10v8.5H8ZM2.5 14.5h4c1.5 0 2.5 1 4 1h3a1.5 1.5 0 0 1 0 3H10");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
