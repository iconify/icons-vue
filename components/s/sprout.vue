<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z8nx2gdum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sprout" /></template>
<style>
.z8nx2gdum {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 21.25V11.5m-4 9.75h8m-4-8.75c0-3.5-2.25-6-6.75-6c0 3.75 2.25 6 6.75 6m0-2.5c0-3.75 2.25-6.25 6.75-6.25c0 4-2.25 6.25-6.75 6.25");
}

</style>
