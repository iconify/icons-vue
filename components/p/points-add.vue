<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c9vpvqmhm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:points-add" /></template>
<style>
.c9vpvqmhm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.745 16.66L11 16.25l-5.143 2.829l1.101-5.766l-4.28-4.017l5.824-.734L11 3.25l2.498 5.312l5.824.734l-2.596 2.436m-1.531 1.437l-.153.144l.204 1.071M18 14.5v7M14.5 18h7");
}

</style>
