<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kbs4b5ebs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:oil-sands" /></template>
<style>
.kbs4b5ebs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.43 17H2.5C4.5 9.5 8 4.5 12 4.5c2.665 0 5.109 2.22 7.034 5.921M9 9.5h6m-8 4h6.5M18 13c1.5 1.75 3 3.5 3 5.5a3 3 0 0 1-6 0c0-2 1.5-3.75 3-5.5");
}

</style>
