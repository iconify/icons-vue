<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m44zbvbup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:up-next" /></template>
<style>
.m44zbvbup {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 4.75h16.5m-16.5 5h16.5m-8 7.5h8M4.59 14.54l3.32 2.17q.84.54 0 1.08l-3.32 2.17q-.84.54-.84-.46V15q0-1 .84-.46");
}

</style>
