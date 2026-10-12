<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sm95xbbne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:test-fail-sharp" /></template>
<style>
.sm95xbbne {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11 2.75h3.25v6l.56 1.12l5.13 10.26l.56 1.12h-17l.56-1.12L9.19 9.87l.56-1.12v-6zm-1 11.5l4 4m0-4l-4 4");
}

</style>
