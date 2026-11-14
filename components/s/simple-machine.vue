<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ub8dz9b9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:simple-machine" /></template>
<style>
.ub8dz9b9l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12h19M12 12l-4 7h8ZM5.75 6h2.5A1.75 1.75 0 0 1 10 7.75v2.5A1.75 1.75 0 0 1 8.25 12h-2.5A1.75 1.75 0 0 1 4 10.25v-2.5A1.75 1.75 0 0 1 5.75 6M19 4.5V9m-2-2l2 2l2-2");
}

</style>
