<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ruvn1em0i"/><path class="tiwdxlvxu"/><path class="b5oeb3bzg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:profile-bio" /></template>
<style>
.b5oeb3bzg {
  d: path("M8.5 10.75c0-1.5 1.5-2.5 3.5-2.5s3.5 1 3.5 2.5M7 13.5h10M7 16.25h10M7 19h6.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ruvn1em0i {
  d: path("M7.875 2h8.25A4.375 4.375 0 0 1 20.5 6.375v11.25A4.375 4.375 0 0 1 16.125 22h-8.25A4.375 4.375 0 0 1 3.5 17.625V6.375A4.375 4.375 0 0 1 7.875 2");
}

.tiwdxlvxu {
  d: path("M10.25 6.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0");
}

</style>
