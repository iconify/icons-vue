<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yhyfubbda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:picnic-basket" /></template>
<style>
.yhyfubbda {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 11.5a5.75 5.75 0 0 1 11.5 0M4 11.5h16q1.25 0 1 1.22l-1.5 7.31q-.25 1.22-1.5 1.22H6q-1.25 0-1.5-1.22L3 12.72q-.25-1.22 1-1.22m-.58 3.25h17.16M4.08 18h15.84");
}

</style>
