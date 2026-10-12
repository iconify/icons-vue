<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="usqg9mb4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:redshift" /></template>
<style>
.usqg9mb4b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 14c1.08 4 1.92 4 3 0c1.44-4 2.56-4 4 0c1.8 4 3.2 4 5 0c2.34-4 4.16-4 6.5 0M5.5 2.75q.33 2.42 2.75 2.75q-2.42.33-2.75 2.75q-.33-2.42-2.75-2.75q2.42-.33 2.75-2.75");
}

</style>
