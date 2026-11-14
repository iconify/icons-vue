<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yor2w_b9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tax-bracket" /></template>
<style>
.yor2w_b9w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.7 15.5H3v-4h4.75V7.25h4.5V3H17v9.7m-9.25-1.2v4m4.5-8.25v8.25m2.5 5.75l6.5-6.5m-5.75.75h.01m4.99 5h.01");
}

</style>
