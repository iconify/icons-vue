<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y2wcvxb5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sponge-pack" /></template>
<style>
.y2wcvxb5m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 14.5h9a2.5 2.5 0 0 1 2.5 2.5a2.5 2.5 0 0 1-2.5 2.5H5A2.5 2.5 0 0 1 2.5 17A2.5 2.5 0 0 1 5 14.5m2.5-5h9A2.5 2.5 0 0 1 19 12a2.5 2.5 0 0 1-2.5 2.5h-9A2.5 2.5 0 0 1 5 12a2.5 2.5 0 0 1 2.5-2.5m2.5-5h9A2.5 2.5 0 0 1 21.5 7A2.5 2.5 0 0 1 19 9.5h-9A2.5 2.5 0 0 1 7.5 7A2.5 2.5 0 0 1 10 4.5");
}

</style>
