<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="k36ce6u1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:wardbullet" /></template>
<style>
.k36ce6u1v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.069 18.565c5.816-5.52 10.431-4.764 10.431-4.764v24.7c0 2.216-1.784 4-4 4h-29c-.86 0-1.656-.269-2.307-.727c0 0 20.871-19.408 24.876-23.21zM5.5 38.501v-29c0-2.216 1.784-4 4-4h27c.137-.11.364 3.66-3.888 8.642c-1.143 1.339-7.785 7.885-14.141 14.096c-6.357 6.212-12.51 12.132-12.51 12.132a4 4 0 0 1-.46-1.87z");
}

</style>
