<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xwiwqli0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:organic-cosmetics" /></template>
<style>
.xwiwqli0m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.375 11h7.25A4.375 4.375 0 0 1 20 15.375v1.75a4.375 4.375 0 0 1-4.375 4.375h-7.25A4.375 4.375 0 0 1 4 17.125v-1.75A4.375 4.375 0 0 1 8.375 11M7.5 8h9A1.5 1.5 0 0 1 18 9.5a1.5 1.5 0 0 1-1.5 1.5h-9A1.5 1.5 0 0 1 6 9.5A1.5 1.5 0 0 1 7.5 8M12 8c.5-3.25 2.75-5 6.5-5.25C18.25 6 16 8 12 8");
}

</style>
