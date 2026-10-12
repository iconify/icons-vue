<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qmw3pb6sp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:river" /></template>
<style>
.qmw3pb6sp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.6 2.75c2.67 3.08 2.67 6.17 0 9.25s-2.67 6.17 0 9.25m4.75-18.5c2.67 3.08 2.67 6.17 0 9.25s-2.67 6.17 0 9.25");
}

</style>
