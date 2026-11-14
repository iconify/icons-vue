<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="twib-kasm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:porch" /></template>
<style>
.twib-kasm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m8.195 5.29l2.918-2.139a1.5 1.5 0 0 1 1.774 0l2.918 2.139A1.5 1.5 0 0 1 14.918 8H9.082a1.5 1.5 0 0 1-.887-2.71M5.5 8v10.5M18.5 8v10.5M4 21.5v-3h16v3m-17.5 0h19M9 18.5V11h6v7.5m-1.75-3.75h.01");
}

</style>
