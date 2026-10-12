<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ditzrto2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:rotunda" /></template>
<style>
.ditzrto2j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 10.5a5 5 0 0 1 10 0Zm5-5V2.75M4.25 10.5h15.5M6.5 13.25v5m2.75-5v5m2.75-5v5m2.75-5v5m2.75-5v5m-14.75 3h18.5");
}

</style>
