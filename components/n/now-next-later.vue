<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zxi64mtki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:now-next-later" /></template>
<style>
.zxi64mtki {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 2.5H5.5a1.75 1.75 0 0 1 1.75 1.75v2.5A1.75 1.75 0 0 1 5.5 8.5H4.25A1.75 1.75 0 0 1 2.5 6.75v-2.5A1.75 1.75 0 0 1 4.25 2.5M11.5 5h1.25a1.75 1.75 0 0 1 1.75 1.75v2.5A1.75 1.75 0 0 1 12.75 11H11.5a1.75 1.75 0 0 1-1.75-1.75v-2.5A1.75 1.75 0 0 1 11.5 5m7 2.5h1.25a1.75 1.75 0 0 1 1.75 1.75v2.5a1.75 1.75 0 0 1-1.75 1.75H18.5a1.75 1.75 0 0 1-1.75-1.75v-2.5A1.75 1.75 0 0 1 18.5 7.5M3 19h18m-2.5-2.5L21 19l-2.5 2.5");
}

</style>
