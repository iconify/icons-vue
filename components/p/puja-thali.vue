<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="op-su-bvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:puja-thali" /></template>
<style>
.op-su-bvt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3.25c1.5 1.5 2.25 2.75 2.25 4a2.25 2.25 0 0 1-4.5 0c0-1.25.75-2.5 2.25-4m-4 9h8a4 3 0 0 1-8 0m-5.25 5.5h18.5a3 3 0 0 1-3 3H5.75a3 3 0 0 1-3-3");
}

</style>
