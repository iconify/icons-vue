<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tfg07bb9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:public-bbq-grill" /></template>
<style>
.tfg07bb9i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 10.5h17a8.5 6 0 0 1-17 0M8 15.75L6.5 21.5m9.5-5.75l1.5 5.75M9 7.75c-1.5-1.5 1.5-3 0-5m6 5c-1.5-1.5 1.5-3 0-5");
}

</style>
