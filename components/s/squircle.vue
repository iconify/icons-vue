<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u_f8ibc-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:squircle" /></template>
<style>
.u_f8ibc-p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.5c8.5 0 9.5 1 9.5 9.5s-1 9.5-9.5 9.5s-9.5-1-9.5-9.5s1-9.5 9.5-9.5");
}

</style>
