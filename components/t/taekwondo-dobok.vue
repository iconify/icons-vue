<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hs-e_5rjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:taekwondo-dobok" /></template>
<style>
.hs-e_5rjc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 3L3 6.5L4.5 12L7 11v10h10V11l2.5 1L21 6.5L15.5 3Zm0 0L14 14m1.5-11l-3.75 6.5M7 14h10m-7 0l-1.5 4m1.5-4l1.5 4");
}

</style>
