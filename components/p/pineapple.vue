<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iu9ahdx9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pineapple" /></template>
<style>
.iu9ahdx9b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 9c-4 0-5.5 3.5-5.5 6.5C6.5 19 9 21 12 21s5.5-2 5.5-5.5c0-3-1.5-6.5-5.5-6.5Zm0 0L8.5 4.5M12 9V3m0 6l3.5-4.5M9 14l6 6m0-6l-6 6");
}

</style>
