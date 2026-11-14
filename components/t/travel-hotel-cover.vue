<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i-avazbrh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:travel-hotel-cover" /></template>
<style>
.i-avazbrh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 4.5V20m0-8.5h16q.162 0 .322.026t.313.078t.297.127t.273.173t.241.214t.204.251t.16.28q.069.147.113.303M12.428 16.5H3m4.5-11h3A1.5 1.5 0 0 1 12 7a1.5 1.5 0 0 1-1.5 1.5h-3A1.5 1.5 0 0 1 6 7a1.5 1.5 0 0 1 1.5-1.5M14.75 18l2 2L21 15.75");
}

</style>
