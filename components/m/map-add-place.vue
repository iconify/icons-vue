<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ek2c0uy6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:map-add-place" /></template>
<style>
.ek2c0uy6k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.859 19.746L8.5 18.5l-6 2v-15l6-2l7 2l6-2v11.771M8.5 3.5v15m7-13v8.3M18 15v6m-3-3h6");
}

</style>
