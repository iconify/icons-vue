<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ypn1ksbxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sail-spinnaker" /></template>
<style>
.ypn1ksbxx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 18.5h16l-2.5 3h-11ZM8 3v15.5M8 3c5-1.5 13 0 13 6.5c0 4.5-4 6-8 6c-2 0-3.5-1-5-2.5");
}

</style>
