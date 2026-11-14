<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lckm6ub5w"/><path class="ifeckcbaf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:plant-growth-ruler" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ifeckcbaf {
  d: path("M7.5 15v-3.5c-.25-2.5-1.75-4-4-4c0 2.25 1.5 4 4 4c.25-2.75 1.75-4.5 4-4.5c0 2.5-1.5 4.5-4 4.5m8-4.5H18m-2.5 5H18m-2.5 5H18");
}

.lckm6ub5w {
  d: path("M5.54 15h3.92a1.75 1.75 0 0 1 1.73 2.016l-.462 3A1.75 1.75 0 0 1 8.999 21.5H6.001a1.75 1.75 0 0 1-1.729-1.484l-.462-3A1.75 1.75 0 0 1 5.54 15M17.25 2.5h1.5a1.75 1.75 0 0 1 1.75 1.75v15.5a1.75 1.75 0 0 1-1.75 1.75h-1.5a1.75 1.75 0 0 1-1.75-1.75V4.25a1.75 1.75 0 0 1 1.75-1.75");
}

</style>
