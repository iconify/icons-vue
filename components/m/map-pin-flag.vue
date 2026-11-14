<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d2k8iobvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:map-pin-flag" /></template>
<style>
.d2k8iobvo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 21.5s-5-4-5-7.5a5 5 0 0 1 10 0c0 3.5-5 7.5-5 7.5m0-7.5h.01M17 2.5V12m1.5-9.5h1.713a.757.757 0 0 1 .662 1.125l-.22.397a1.5 1.5 0 0 0 0 1.456l.22.397A.757.757 0 0 1 20.213 7H18.5A1.5 1.5 0 0 1 17 5.5V4a1.5 1.5 0 0 1 1.5-1.5");
}

</style>
