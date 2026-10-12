<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rg68-4q9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sort-ascending" /></template>
<style>
.rg68-4q9g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 6.5h4m-4 5.5h6.5m-6.5 5.5h9m4.5 1.75V4.75m-3.5 3.5l3.5-3.5l3.5 3.5");
}

</style>
