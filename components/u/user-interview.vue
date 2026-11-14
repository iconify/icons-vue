<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n29hy8biw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:user-interview" /></template>
<style>
.n29hy8biw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15.25 3h4.25a2 2 0 0 1 2 2v5a2 2 0 0 1-2 2H18l-2.25 2.25V12h-.5a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2M4.5 9.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0m-2 11c0-3.5 2.25-5 5-5s5 1.5 5 5");
}

</style>
