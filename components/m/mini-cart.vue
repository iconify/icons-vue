<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v6tkabcez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mini-cart" /></template>
<style>
.v6tkabcez {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.352 10.5h7.407a1.75 1.75 0 0 1 1.697 2.174l-.375 1.5a1.75 1.75 0 0 1-1.697 1.326H9.802a1.75 1.75 0 0 1-1.676-1.247l-.45-1.5A1.75 1.75 0 0 1 9.352 10.5M4.5 7.5H6l2.5 8m0 4a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m6 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m3-9v-7m1.342.671L19 4.25a.839.839 0 0 1 0 1.5l-.158.079A.927.927 0 0 1 17.5 5a.927.927 0 0 1 1.342-.829");
}

</style>
