<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qqslx_baj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:wine-glass-red" /></template>
<style>
.qqslx_baj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 3h9c1.5 1.5 2 3.5 2 5a6.5 6.5 0 0 1-13 0c0-1.5.5-3.5 2-5M12 14.5V21m-4 0h8M5.5 8.5h13");
}

</style>
