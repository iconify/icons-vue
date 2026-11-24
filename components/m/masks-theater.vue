<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l9gfmlzts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:masks-theater" /></template>
<style>
.l9gfmlzts {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m11.076 11.668l-.868-4.924a2 2 0 0 1 1.622-2.317l5.909-1.042a2 2 0 0 1 2.317 1.623l.868 4.924a5 5 0 0 1-9.848 1.736m1.495 6.36a5.002 5.002 0 0 1-9.495-2.896l.868-4.924a2 2 0 0 1 2.317-1.623l1.264.223m5.81-1.6h.01m3.93-.695h.01m-3.428 3.65a2.267 2.267 0 0 0 3.939-.695M6.725 11.713h.01m-.705 3.94a2.267 2.267 0 0 1 3.94.694");
}

</style>
