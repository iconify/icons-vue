<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j4z9s9blr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pointer-control" /></template>
<style>
.j4z9s9blr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m9.52 8.05l6.46 3.65q.52.3-.05.48l-2.26.74q-.57.18-.83.72l-1.08 2.32q-.26.54-.42-.04L9.16 8.33q-.16-.58.36-.28m-.02-3.3l2.5-2l2.5 2m-5 14.5l2.5 2l2.5-2M4.75 9.5l-2 2.5l2 2.5m14.5-5l2 2.5l-2 2.5");
}

</style>
