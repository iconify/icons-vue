<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="j84no7hdc"/><path class="z9ia0ab0e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:scouring-pad" /></template>
<style>
.j84no7hdc {
  d: path("M3.5 9.5h17a1 1 0 0 1 1 1V18a1 1 0 0 1-1 1h-17a1 1 0 0 1-1-1v-7.5a1 1 0 0 1 1-1ZM7 6h10v3.5H7Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z9ia0ab0e {
  d: path("m6.5 15.5l2.75-2.75L12 15.5l2.75-2.75l2.75 2.75");
}

</style>
