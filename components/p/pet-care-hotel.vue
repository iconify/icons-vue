<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bi1zsabwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pet-care-hotel" /></template>
<style>
.bi1zsabwu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17.43 12.297c-.55-.372-.93-.97-.93-1.797h-9c0 3-5 3-5 0c0-1 1-1.25 1-2s-1-1-1-2c0-3 5-3 5 0h9c0-3 5-3 5 0c0 1-1 1.25-1 2s1 1 1 2c0 .846-.398 1.454-.969 1.823M18 21.25c-2.5-1.75-3.5-3-3.5-4.25s1-2 2-2c.75 0 1.25.5 1.5 1c.25-.5.75-1 1.5-1c1 0 2 .75 2 2s-1 2.5-3.5 4.25");
}

</style>
