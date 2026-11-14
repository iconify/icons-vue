<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c0zo8nbmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sale-burst" /></template>
<style>
.c0zo8nbmn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.751 4.085za1.39 1.39 0 0 0 2.007.458a.862.862 0 0 1 1.353.651a1.39 1.39 0 0 0 1.609 1.284a.862.862 0 0 1 .937 1.174a1.39 1.39 0 0 0 .893 1.854a.862.862 0 0 1 .334 1.465a1.39 1.39 0 0 0 0 2.058a.862.862 0 0 1-.334 1.465a1.39 1.39 0 0 0-.893 1.854a.862.862 0 0 1-.937 1.174a1.39 1.39 0 0 0-1.609 1.284a.862.862 0 0 1-1.353.651a1.39 1.39 0 0 0-2.007.458a.862.862 0 0 1-1.502 0a1.39 1.39 0 0 0-2.007-.458a.862.862 0 0 1-1.353-.651a1.39 1.39 0 0 0-1.609-1.284a.862.862 0 0 1-.937-1.174a1.39 1.39 0 0 0-.893-1.854a.862.862 0 0 1-.334-1.465a1.39 1.39 0 0 0 0-2.058a.862.862 0 0 1 .334-1.465a1.39 1.39 0 0 0 .893-1.854a.862.862 0 0 1 .937-1.174a1.39 1.39 0 0 0 1.609-1.284a.862.862 0 0 1 1.353-.651a1.39 1.39 0 0 0 2.007-.458a.862.862 0 0 1 1.502 0M9 15l6-6m-5.75.25h.01m5.49 5.5h.01");
}

</style>
