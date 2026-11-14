<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qfpbf9bvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pet-bath" /></template>
<style>
.qfpbf9bvk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 9v2q0 .197.019.392q.02.196.058.388q.038.193.095.381t.132.37q.076.181.168.355q.093.173.202.336t.234.316q.125.151.264.29t.29.264t.316.234q.163.109.336.202q.174.092.355.168q.182.075.37.132t.381.095t.388.058T7.5 15h5q.788 0 1.517-.299m2.436-3.089q.047-.304.047-.612V9m-14 0h15M6 9V5a2.25 2.25 0 0 1 4.5 0v1m8 7.5s-3 3.25-3 5a3 3 0 0 0 6 0c0-1.75-3-5-3-5");
}

</style>
