<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jsgls-l1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ship-captain" /></template>
<style>
.jsgls-l1s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 5c0-1.5 15-1.5 15 0L17 8H7ZM8 8v2.5q0 .197.019.392q.02.196.058.388q.038.193.095.381t.132.37q.076.181.168.355q.093.173.202.336t.234.316q.125.151.264.29t.29.264t.316.234q.163.109.336.202q.174.092.355.168q.182.075.37.132t.381.095t.388.058t.392.019q.231 0 .461-.027q.23-.026.455-.079q.226-.053.443-.132q.218-.079.425-.182t.401-.23q.194-.126.372-.274t.338-.315t.299-.353m.623-1.212Q16 11.112 16 10.5V8M4.5 21.5c0-2.44 3.096-4.166 7.197-4.247M15.75 18a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0ZM18 14.5v7M14.5 18h7");
}

</style>
