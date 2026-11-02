<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j2xzm_b_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:reload-alt-round" /></template>
<style>
.j2xzm_b_n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 9a7.616 7.616 0 0 1 14 0m-6 0h6V3m0 12a7.616 7.616 0 0 1-14 0m6 0H5v6");
}

</style>
