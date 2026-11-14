<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eso5kug0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:surf-competition" /></template>
<style>
.eso5kug0q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.625 20.564Q12.28 21.5 10 21.5q-5 0-5.5-4.5C4 12 4.5 6.5 10 2.5c3.774 2.745 5.194 6.197 5.552 9.708M10 7.5V18m5.5-3h6v1.25a3 3 0 0 1-6 0Zm3 4.25v2.25m-2.25 0h4.5");
}

</style>
