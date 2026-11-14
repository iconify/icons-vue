<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="uamhkl52y"/><path class="z9gvyp8il"/><path class="b_le361vp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:reorganization" /></template>
<style>
.b_le361vp {
  d: path("M5.25 6.25L7 4.5l1.75 1.25");
}

.uamhkl52y {
  d: path("M9.5 2.5h5v4h-5Zm-7 14h5v4h-5Zm14 0h5v4h-5Zm.5-12c2 1 2.75 5 2 9");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z9gvyp8il {
  d: path("M17.25 11.75L19 13.5l1.75-1.75M14 18.5h-4m1.75-1.75L10 18.5l1.75 1.75M5 13.5c-.75-4 0-8 2-9");
}

</style>
