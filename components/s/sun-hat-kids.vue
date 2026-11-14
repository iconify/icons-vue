<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="grlpqbcoe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sun-hat-kids" /></template>
<style>
.grlpqbcoe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7 14.5l1-7C8.25 6 9.5 5 12 5s3.75 1 4 2.5l1 7c2 1.5 4 3 4.5 4.5h-19C3 17.5 5 16 7 14.5m.5-3h9m-9.5 3h10");
}

</style>
