<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d1wbr5b7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:milkshake-glass" /></template>
<style>
.d1wbr5b7i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 9.5L8 21.5h8l1.75-12M5.5 9.5a3 3 0 0 1 3-3a3.5 3.5 0 0 1 7 0a3 3 0 0 1 3 3ZM17 7l3-3.5");
}

</style>
