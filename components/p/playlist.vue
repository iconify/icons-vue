<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="im_1b8b0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:playlist" /></template>
<style>
.im_1b8b0f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 6h13m-13 5h13m-13 5H10m6.263-.663l1.052.622a1.5 1.5 0 0 1 0 2.582l-1.052.622A1.5 1.5 0 0 1 14 17.871v-1.242a1.5 1.5 0 0 1 2.263-1.292");
}

</style>
