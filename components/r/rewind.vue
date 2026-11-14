<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vlo5upfud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:rewind" /></template>
<style>
.vlo5upfud {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m18.241 7.948l-3.716 2.622a1.75 1.75 0 0 0 0 2.86l3.716 2.622A1.75 1.75 0 0 0 21 14.623V9.377a1.75 1.75 0 0 0-2.759-1.429m-9.5 0L5.025 10.57a1.75 1.75 0 0 0 0 2.86l3.716 2.622a1.75 1.75 0 0 0 2.759-1.429V9.377a1.75 1.75 0 0 0-2.759-1.429");
}

</style>
