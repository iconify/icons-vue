<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r40up1bbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:staff-uniform-shirt" /></template>
<style>
.r40up1bbt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 3.5L3 6.5L4.5 11l2-.75V20.5h11V10.25l2 .75L21 6.5l-5.5-3c-.75 1-2 1.5-3.5 1.5s-2.75-.5-3.5-1.5M12 5v4m2.5 5.5h.01");
}

</style>
