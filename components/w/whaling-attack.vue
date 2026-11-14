<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fwtv0acub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:whaling-attack" /></template>
<style>
.fwtv0acub {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 15c0-4.5 4-7 9-7c4.5 0 7.5 2.5 8 6.5l2-3V18l-3-1.5c-1.5 2-4 3-7 3c-5 0-9-1-9-4.5m4-1.5h.01m2.99-8V3M12 5.5l.5-2");
}

</style>
