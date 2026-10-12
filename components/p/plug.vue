<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y66mtcczl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:plug" /></template>
<style>
.y66mtcczl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 8.25h10.5v3.5a5.25 5.25 0 0 1-10.5 0Zm2.5-5.5v5.5m5.5-5.5v5.5M12 17v4.25");
}

</style>
