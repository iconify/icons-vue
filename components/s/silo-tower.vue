<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="slzfhnwmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:silo-tower" /></template>
<style>
.slzfhnwmp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 5.75a4.5 3 0 0 1 9 0Zm0 3h9v12.5h-9Zm0 4.25h9m-9 4h9M3.25 21.25h17.5");
}

</style>
