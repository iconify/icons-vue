<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ogjqbtrcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pin-dry-cleaner" /></template>
<style>
.ogjqbtrcz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12 10.5l-8.75 6.75Q2.5 18.5 4 18.5h16q1.5 0 .75-1.25ZM9.75 6.75A2.25 2.25 0 1 1 12 9v1.5");
}

</style>
