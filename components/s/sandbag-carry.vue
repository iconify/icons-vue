<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rtp0-jbnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sandbag-carry" /></template>
<style>
.rtp0-jbnq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 7c-4.5 2-6.5 5.5-6.5 9S5 21.5 9 21.5h3c1.234 0 2.326-.19 3.245-.557m2.441-8.681C16.72 10.158 14.867 8.274 12 7M9 7L7 2.5h7L12 7M7.5 7h6M18 21v-6m-2.5 2.5L18 15l2.5 2.5");
}

</style>
