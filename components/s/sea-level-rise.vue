<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n1ombvnpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sea-level-rise" /></template>
<style>
.n1ombvnpq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 11.75v-9M8.75 6L12 2.75L15.25 6m-12.5 9.75q1.54-2 3.08 0t3.08 0t3.08 0t3.08 0t3.08 0t3.08 0m-18.48 4.5q1.54-2 3.08 0t3.08 0t3.08 0t3.08 0t3.08 0t3.08 0");
}

</style>
