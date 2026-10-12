<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pq7v-bbaa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:university" /></template>
<style>
.pq7v-bbaa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 9.5a5.25 5.25 0 0 1 10.5 0M12 4.25v-1.5M2.75 9.5h18.5m-15.5 3V18m4-5.5V18m4.5-5.5V18m4-5.5V18m-15.5 2.75h18.5");
}

</style>
