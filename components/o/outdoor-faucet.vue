<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lmjjb2-ms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:outdoor-faucet" /></template>
<style>
.lmjjb2-ms {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 3.5V20M3 9h8q.197 0 .392.019q.196.02.388.058q.193.038.381.095t.37.132q.181.076.355.168q.173.093.336.202t.316.234q.151.125.29.264t.264.29t.234.316q.109.163.202.336q.092.174.168.355q.075.182.132.37t.095.381t.058.388T15 13v.077M13.923 14.5H11V13H3m3-8.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m2 2V9m10.5 4.25c1.5 1.75 3.25 3.5 3.25 5a3.25 3.25 0 0 1-6.5 0c0-1.5 1.75-3.25 3.25-5");
}

</style>
