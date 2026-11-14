<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="viun5vwmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:network-slicing" /></template>
<style>
.viun5vwmd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.654 4h13.442a1.255 1.255 0 0 1 1.154 1.75l-.295.689A1.75 1.75 0 0 1 18.346 7.5H4.904A1.255 1.255 0 0 1 3.75 5.75l.295-.689A1.75 1.75 0 0 1 5.654 4m0 6.5h13.442a1.255 1.255 0 0 1 1.154 1.75l-.295.689A1.75 1.75 0 0 1 18.346 14H4.904a1.255 1.255 0 0 1-1.154-1.75l.295-.689A1.75 1.75 0 0 1 5.654 10.5m0 6.5h13.442a1.255 1.255 0 0 1 1.154 1.75l-.295.689a1.75 1.75 0 0 1-1.609 1.061H4.904a1.255 1.255 0 0 1-1.154-1.75l.295-.689A1.75 1.75 0 0 1 5.654 17");
}

</style>
