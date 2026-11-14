<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qlsch-euk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:shelf-facing" /></template>
<style>
.qlsch-euk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 19.5h19M5 13h.5a1.75 1.75 0 0 1 1.75 1.75v3A1.75 1.75 0 0 1 5.5 19.5H5a1.75 1.75 0 0 1-1.75-1.75v-3A1.75 1.75 0 0 1 5 13m6.75 0h.5A1.75 1.75 0 0 1 14 14.75v3a1.75 1.75 0 0 1-1.75 1.75h-.5A1.75 1.75 0 0 1 10 17.75v-3A1.75 1.75 0 0 1 11.75 13m6.75 0h.5a1.75 1.75 0 0 1 1.75 1.75v3A1.75 1.75 0 0 1 19 19.5h-.5a1.75 1.75 0 0 1-1.75-1.75v-3A1.75 1.75 0 0 1 18.5 13M4 7.5h16m-2.25-2.25L20 7.5l-2.25 2.25");
}

</style>
