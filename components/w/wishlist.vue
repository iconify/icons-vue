<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u73ysyoub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:wishlist" /></template>
<style>
.u73ysyoub {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 6.25h12.5M3.75 11h7m-7 4.75h4.5M16 21l-4.4-4.35A2.95 2.95 0 0 1 16 12.8a2.95 2.95 0 0 1 4.4 3.85Z");
}

</style>
