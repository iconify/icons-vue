<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ir57aackv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:receipt" /></template>
<style>
.ir57aackv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 2.75h10.5a2 2 0 0 1 2 2v16.5l-2.4-1.5l-2.45 1.5l-2.4-1.5l-2.4 1.5l-2.45-1.5l-2.4 1.5V4.75a2 2 0 0 1 2-2m2 5h6.5m-6.5 3.5h4m-4 3.75h6.5");
}

</style>
