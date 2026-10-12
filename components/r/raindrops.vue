<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pop3iqbvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:raindrops" /></template>
<style>
.pop3iqbvz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7.72 5.86l-3.7 7.05a4.5 4.5 0 1 0 7.96 0l-3.7-7.05q-.28-.53-.56 0m9.25-2.2l-1.93 3.68a2.5 2.5 0 1 0 4.42 0l-1.93-3.68q-.28-.53-.56 0m-.75 10.25l-1.93 3.68a2.5 2.5 0 1 0 4.42 0l-1.93-3.68q-.28-.53-.56 0");
}

</style>
