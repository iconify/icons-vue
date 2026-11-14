<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z-b6debzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sign-here-tag" /></template>
<style>
.z-b6debzh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12 15.5l-4.5-6l2-6.5h5l2 6.5Zm0 0v-5M3.5 20q2.5-3 5 0t5 0t5 0");
}

</style>
