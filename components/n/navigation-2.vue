<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b_qt0ccxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:navigation-2" /></template>
<style>
.b_qt0ccxo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m17.774 8.534l-3.486 7.891A1.216 1.216 0 0 1 12 16.243l-.624-2.372a1.75 1.75 0 0 0-1.247-1.247L7.757 12a1.216 1.216 0 0 1-.182-2.288l7.891-3.486a1.75 1.75 0 0 1 2.308 2.308");
}

</style>
