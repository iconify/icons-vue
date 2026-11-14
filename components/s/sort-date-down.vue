<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uo-q2dy-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sort-date-down" /></template>
<style>
.uo-q2dy-v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 4v16m-3-3l3 3l3-3m5.563-10h2.875A3.063 3.063 0 0 1 21 10.063v3.875A3.063 3.063 0 0 1 17.938 17h-2.875A3.063 3.063 0 0 1 12 13.938v-3.875A3.063 3.063 0 0 1 15.063 7M14.5 5v3.5m4-3.5v3.5M12 11h9");
}

</style>
