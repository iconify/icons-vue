<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s7lfx4bju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:navigation" /></template>
<style>
.s7lfx4bju {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m13.618 6.93l3.847 9.343A1.383 1.383 0 0 1 15.5 18l-2.632-1.504a1.75 1.75 0 0 0-1.736 0L8.5 18a1.383 1.383 0 0 1-1.965-1.727l3.847-9.343a1.75 1.75 0 0 1 3.236 0");
}

</style>
