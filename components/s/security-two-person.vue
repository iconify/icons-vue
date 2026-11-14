<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hqjxs_b6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:security-two-person" /></template>
<style>
.hqjxs_b6v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 8a3 3 0 1 0 6 0a3 3 0 1 0-6 0ZM2.5 19.5C2.5 16 4.5 14 7 14c1.993 0 3.668 1.271 4.266 3.56m.191 1.073q.043.417.043.867M14 8a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm1.134 6.418A4.24 4.24 0 0 1 17 14c.548 0 1.073.096 1.557.283M14.75 18l2 2L21 15.75");
}

</style>
