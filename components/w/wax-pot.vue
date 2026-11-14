<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eeqkn1tyf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:wax-pot" /></template>
<style>
.eeqkn1tyf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 10.5h16V15c0 3.3-2.7 5.5-6 5.5h-4c-3.3 0-6-2.2-6-5.5ZM8 8C7 6.5 9 5.5 8 4m4 4c-1-1.5 1-2.5 0-4m4 4c-1-1.5 1-2.5 0-4");
}

</style>
