<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zs4jzyb0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:window-arch" /></template>
<style>
.zs4jzyb0n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 18V9a6.25 6.25 0 0 1 12.5 0v9ZM12 2.75V18m-6.25-7.5h12.5M3.75 21.25h16.5");
}

</style>
